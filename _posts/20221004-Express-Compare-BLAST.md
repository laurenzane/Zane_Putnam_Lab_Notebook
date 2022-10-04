# Goal: revist Express Compare Aim 3: Taxonomic Annotation
# date: 20221004

1. locate unmapped FASTA files on Andromeda
  - located in Express_Compare/REF/MCap2 and Express_Compare/REF/MCap2
2. "FASTA" files are somehow still FASTQ files so I converted one to FASTA to test the BLAST+ command line

```
sed -n '1~4s/^@/>/p;2~4p' 1041.1 > 1041.1.fasta
```
3. created shell script for BLAST+ with just basic commands from NCBI website, ran sbatch

```
#!/bin/bash
#SBATCH --job-name="BLASTtest"
#SBATCH -t 100:00:00
#SBATCH --export=NONE
#SBATCH --mail-type=BEGIN,END,FAIL
#SBATCH --mail-user=laurenzane@uri.edu
#SBATCH -D /data/putnamlab/shared/Express_Compare/REF/PAcuta2/unmapped
#SBATCH --exclusive #SBATCH -c 2

module load BLAST+/2.11.0-gompi-2020b

blastn -db nt -query 1041.1.fasta -out test.out -remote
grep RID test.out

```
* job 181897 failed
* job 181901 
