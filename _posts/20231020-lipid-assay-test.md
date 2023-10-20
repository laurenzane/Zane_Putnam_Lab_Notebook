---
layout: post
title: 96-well plate lipid assay
date: '2023-10-20'
category: Protocol
tags: [Protocol],[IntBio]
---

## 20230915 Lipid assay test

This protocol was modified from [Bove & Baumann 2021](https://www.protocols.io/view/coral-lipid-assay-for-96-well-plates-q26g789pqlwz/v1) and L. Fuess lipid protocol. We are testing the lipid assay with coral eggs, embryos, and larvae.

Following the [lipid assay trials](https://github.com/JillAshey/JillAshey_Putnam_Lab_Notebook/blob/master/_posts/2023-09-26-Lipid-Assay-Test.md?plain=1) completed with Jill, we talked through some troubleshooting steps. We noticed that in previous trials that the addition of phosphoric acid during the second read resulted in overfilled values on the spec for tubes 1-5. In tubes 6 and 7 (7 is the chloroform BLANK), spec values exceeded 3.8, which is almost the maximum value for the spec.

I followed [this protocol](https://github.com/JillAshey/JillAshey_Putnam_Lab_Notebook/blob/master/_posts/2023-09-10-Lipid-Assay-Test.md) with a few modifications.

Additionally,  in the original protocol, it is confusing to understand when to add the standards, so I am clarifying it here.

1. Modification 1: adding less phosphoric acid for the second read
2. Modification 2: diluting standard range

### Protocol

**Remember** to do this protocol in fume hood whenever possible! Reagents are very toxic!

**Please [schedule](https://web.uri.edu/ehs/online-pickup/) EHS pickups regularly so that the satellite accumulation areas do not become overfilled.**

### Equipment

- SpeedVac
- Vortex
- Shaker
- Centrifuge
- 96-well PCR plate
- Water bath (up to 70°C)
- Thermocycler
- 96-well plate
- Plate reader
- Pipettes + tips
- 1.5 mL tubes
- Fume hood

### Reagents

- CH<sub>3</sub>OH (Methanol)
- CHCl<sub>3</sub> (Chloroform)
- 0.05 M NaCl in water
- H<sub>3</sub>PO<sub>4</sub> (17% phosphoric acid)
- 0.2 mg/mL vanillin in 17% phosphoric acid
- Concentrated (18M) sulfuric acid (H<sub>2</sub>SO4)
- 1.5 mg/mL corn oil

### Protocol

#### The day before, you must desiccate your samples in a SpeedVac!

1. Prior to the assay, homogenize the eggs/embryos/larvae in 700 uL of PBS.
2. Aliquot out 150 uL of sample extract and desiccate samples overnight in a SpeedVac.

#### Turn on bead bath
1. Turn on bead bath
2. Set temperature to 70°C

#### Make reagents

Prepare reagents according to Putnam lab lipid [protocol](https://github.com/Putnam-Lab/Lab_Management/blob/master/Lab_Resources/Physiology_Protocols/Lipids/Bove_Baumann_96well_Protocol/Coral_Lipid_Protocol.md).

##### 0.05 NaCl

In a 50 mL labeled falcon tube, add 0.1461g of NaCl in 50 mL DI water.

##### Stock 1.5 mg/mL corn oil

In a 15 mL labeled falcon tube, add 245 uL of corn oil in 14.755 mL of CHCl<sub>3</sub> (chloroform)

Calculations:

- Density = 0.9188 g/ml (Noureddini et al., 1992)
- Total volume of ampule = 1 g* (1ml / 0.9188g) =1.08837614 ml
- Known concentration of ampule= 1000mg / 1.088ml = 918.8 mg/ml (same as known density)
- Therefore: (1.5 mg/mL * 15mL) / 918mg/mL = 0.0245 mL (or 245 μL) of 918mg/mL Corn oil standard concentrate

##### Stock 0.2 mg/mL vanillin in 17% phosphoric acid (H3PO4):

- 20 mL of 17% H<sub>3</sub>PO<sub>4</sub>
	- In a labeled 50 mL Falcon tube, add 4 mL 85% H<sub>3</sub>PO<sub>4</sub> to 16 mL of DI water
- Stock vanillin solution
	- In a labeled 50 mL Falcon tube, add 4 mg vanillin to 20 mL 17% H<sub>3</sub>PO<sub>4</sub>

##### Make subsets of the following reagents in labeled 50 mL falcon tubes daily

- CH<sub>3</sub>OH (Methanol)
- CHCl<sub>3</sub> (Chloroform)
- Concentrated (18M) sulfuric acid (H<sub>2</sub>SO4)

#### Making standards

I have found that it is best to make the standards after pouring/prepping reagents. You will treat the standards like the normal samples starting on **step 4.**

- Make a stock serial dilution in 7 1.5 mL tubes for each plates
- label tubes as 1-7

	a. Add 300 uL of chloroform to standard tubes 2-7.

	b. Add 600 uL (Standard Set A) or 300 uL (Standard Set B) of 1.5 mg/mL stock corn oil to standard tube 1.
    - for the 10/20/23 trial, I prepared two sets of standards (A and B, concentrations below) to test if the standard curve lipid concentrations were too high of concentrations for the spec

	c. Transfer 300 uL from tube 1 into tube 2. Pipette up and down to mix.

	d. Transfer 300 uL from tube 2 into tube 3. Pipette up and down to mix.

	e. Repeat this process for tubes 3 through 6. **Do not add corn oil to tube 7!** This is the blank.

	f. Discard 300 uL from tube 6 so total volume equals 300 uL (optional)

	| Standard A | Corn oil concentration (mg/mL) | Standard B | Corn oil concentration (mg/mL)
	| --------- | ------------------------------ | ---- | ------------------------
	| 1A         | 1.5                            | 1B   |   0.75     
	| 2A         | 0.75                           | 2B | 0.375
	| 3A         | 0.375                          | 3B | 0.188
	| 4A         | 0.188                          | 4B | 0.094
	| 5A         | 0.094                          | 5B | 0.047
	| 6A         | 0.047                          | 6B | 0.235
	| 7A (blank) | 0                              | 7B | 0

#### Lipid Assay

1. Add 500 uL of a 2:1 chloroform:methanol mixture and 100 uL of 0.05 M NaCl to each desiccated sample.
	- 333.33 uL of chloroform and 166.67 uL of methanol
2. Vortex samples to dissolve lipids.
3. Place samples on a shaker for 1 hour, vortexting the samples every 15 minutes.
4. Centrifuge samples at 3000 rpm for 5 minutes.

**from now on, treat standards 1-7 like your normal samples**

5. Move 100uL of Standards 1-7 to the 96-well PCR plate in duplicate
6. Move 100 uL of the bottom layer of the centrifuged sample to a 96-well PCR plate in duplicate
7. Add 50 uL of methanol to each well.
8. Put plate in bead bath (70°C) for 15 minutes.
9. Following solvent evaporation, add 100 uL of 18 M sulfuric acid to each well. **note: add sulfuric acid slowly and carefully as it may bubble out of the well**
10. Put the PCR plate in a thermocycler at 90°C for 20 minutes, followed by 4°C for 20 minutes.
- On PPP thermocycler 1, change user to PUTNAM
- the password is 1234
- scroll through protocols to locate "LIPID" protocol.
11. Transfer 75 uL from the PCR well plate into a new 96 well plate.

![]()
12. Run an initial absorbance reading on the plate reader at 540 nm. This is a baseline measurement that will be used for correcting the final plate absorbance.

![]()

13. Remove the plate from the plate reader and add 34.5 uL of 0.2 mg/mL vanillin in 17% phosphoric acid to each well.
- for this trial, I added 17.2uL of 0.2 mg/mL vanillin in 17% phosphoric acid to standards 1A-7A.
- I was planning on adding 34.5 uL of 0.2 mg/mL vanillin in 17% phosphoric acid to each well to standards 1B-7B, but I did not properly prep the standards.
14. Incubate the plate in the dark at room temperature for 5 minutes.
15. Read the plate again at 540 nm.

![]()

### Next Steps

1. phosphoric acid volume range
- make six sets of standards
a. 17.2uL
b. 20.7 uL
c. 24.2 uL
d. 27.7 uL
e. 31.2 uL
f. 34.5 uL
2. homogenate volume range
