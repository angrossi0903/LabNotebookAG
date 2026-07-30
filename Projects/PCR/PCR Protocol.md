#### I. PCR

[](https://github.com/GWLab-UML/Protocols/blob/main/Molecular_labwork/16S_library_prep.md#i-pcr
- ==spray BSC and pipettes in BSC with 10% bleach, dry, and then spray with 70% ethanol, then dry before use==
- ==UV sterilize ALL tubes==
- **Repeat 3x for all samples that are to be included in the metabarcode library**
- _always include water (negative control - indication of no contamination) and very dilute positive controls (1-5ng of DNA) in every experiment_
- **Mix the following agents via vortex:** Buffer, MgCl2, primers
- **DO NOT vortex:** BSA or Hot Start Polymerase
    - Polymerase should _never_ be left at room temperature - **stays in freezer or in freezer box**
- use aliquoted reagents (limits contamination)
- **all PCR prep is done in the biosafety cabinet in the lab***
	- ==when getting PCR tubes out, DO NOT reach your hand in, ease them out of the bag from the outside==
	- ==cut tubes from each other for each triplicate (ex. if doing 3 samples and a negative, cut 3 sets of 4 tubes)==
		- label tube bag with initials and date opened
	- ==2 eppendorf tubes (1 for water aliquot, 1 for mastermix)==
	- ==UV pipette tips with the boxes open, pipettes flat on the base of the BSC, open water aliquot, and open PCR tubes for ~5 minutes==
	- ==Label tube rack used for holding mastermix components==
	- ==DO NOT UV mastermix components==
	- ==Label your PCR tubes unique numbers based on the triplicate (ex 1,4,7 for one triplicate, 2,5,8 for another, 3,6,9 for the last); label with initials, number, and date==
		- dont put hands inside the tubes and close them one at a time as your using them


 
copy & paste table off of mm_calculations, note which primer you are using each day (0N,1N...)

| Reagent                                      | Amount per 1 rxn (uL) | MasterMix Amount (uL) + 5% | Triplicate (uL) + 5% |
| -------------------------------------------- | --------------------- | -------------------------- | -------------------- |
| Buffer                                       | 5                     | 0                          | 0                    |
| dNTP (10mM)                                  | 0.5                   | 0                          | 0                    |
| F Primer (10uM)                              | 1                     | 0                          | 0                    |
| R Primer (10uM)                              | 1                     | 0                          | 0                    |
| DNA                                          | 1                     | 0                          | 0                    |
| Polymerase                                   | 0.25                  | 0                          | 0                    |
| Water                                        | 16                    | 0                          | 0                    |
| Albumin                                      | 0.25                  | 0                          | 0                    |
| Total                                        | 25                    | 0                          | 0                    |
| _adapted from Sarah's evernote 02/02/21 16S_ |                       |                            |                      |

1. Create master mix for each sample
	1. ==aliquot from sterile molecular water==
	2. ==copy mastermix component concentration table from google sheets everytime you use it==
	3. ==mix reagents with pipette tip before removing==
		- ==make sure especially to mix the polymerase== 
	4) ==vortex mastermix before pipetting into pcr tubes==
	
2. Pipette 24uL of master mix into each replicate tube (3 replicates per sample)
3. Pipette 1uL of DNA into each replicate tube
    1. use new pipette tip for each replicate
4. Run thermocycler program:
    1. 98C for 30 seconds
    2. **28 cycles** (reduced from 30 cycles to) of:
        1. 98C for 10 seconds
        2. 50C for 30 seconds
        3. 72C for 20 seconds
    3. 72C for 2 mins (extension)
    4. 12C forever
- ==When running a gel, do not run or load in the lab (use 614)== 
- ==Add 1 mL GelRed for every 50mL of gel solution==
- ==spin down pcr tubes before loading into the gel==
- ==10 microliters of loading dye to make 10 dots of 1 microliter loading dye spots on parafilm==
	- ==1 microliter of dna from each sample divided amongst these 10 dots==
- ==ALWAYS make a note of how you loaded the gel==
- ==If PCR products sit in the fridge for an extended period, spindown before use==

## **PCR Training First Round Test; 7/23/2026
Primers Used: 0N 515F, 0N 806R
Sample 1: NSW2, August, Oyster 2, 2025, Gill
Sample 2: NSW1, August, Oyster 6, 2025, Gill
Sample 3: NSW1, August Oyster 20, 2025, Gill

1) NSW2, August, Oyster 2, 2025, Gill
2) NSW1, August, Oyster 6, 2025, Gill
3) NSW1, August Oyster 20, 2025, Gill
4) NSW2, August, Oyster 2, 2025, Gill
5) NSW1, August, Oyster 6, 2025, Gill
6) NSW1, August Oyster 20, 2025, Gill
7) NSW2, August, Oyster 2, 2025, Gill
8) NSW1, August, Oyster 6, 2025, Gill
9) NSW1, August Oyster 20, 2025, Gill
 Used 16S Touchdown program, started at 11:17

## Master Mix Table

|                 |                       |                            |                      |
| --------------- | --------------------- | -------------------------- | -------------------- |
| Reagent         | Amount per 1 rxn (uL) | MasterMix Amount (uL) + 5% | Triplicate (uL) + 5% |
| Buffer          | 5                     | 21                         | 63                   |
| dNTP (10mM)     | 0.5                   | 2.1                        | 6.3                  |
| F Primer (10uM) | 1                     | 4.2                        | 12.6                 |
| R Primer (10uM) | 1                     | 4.2                        | 12.6                 |
| Polymerase      | 0.25                  | 1.05                       | 3.15                 |
| Albumin         | 0.25                  | 1.05                       | 3.15                 |
| Water           | 16                    | 67.2                       | 201.6                |
| DNA             | 1                     |                            |                      |
| Total           | 25                    | 100.8                      | 302.4                |
Gel Order
Row 1: DNA Ladder, 1, 4, 7, 2, 5, 8, 3, 6, DNA Ladder
Row 2: DNA Ladder, 9, Neg 1, Neg 2, Neg 3, DNA Ladder

![[Screenshot 2026-07-23 143354.png]]
## **PCR Training Second Round Test; 7/30/2026
- trying 1:10 dilution to fix band brightness problem
	- doing the dilution in separate PCR tubes 
	- band at the bottom (target band) is the same brightness as host band
- same samples as First Round Test
## Master Mix Table:

|                 |                       |                            |                      |
| --------------- | --------------------- | -------------------------- | -------------------- |
| Reagent         | Amount per 1 rxn (uL) | MasterMix Amount (uL) + 5% | Triplicate (uL) + 5% |
| Buffer          | 5                     | 21                         | 63                   |
| dNTP (10mM)     | 0.5                   | 2.1                        | 6.3                  |
| F Primer (10uM) | 1                     | 4.2                        | 12.6                 |
| R Primer (10uM) | 1                     | 4.2                        | 12.6                 |
| Polymerase      | 0.25                  | 1.05                       | 3.15                 |
| Albumin         | 0.25                  | 1.05                       | 3.15                 |
| Water           | 16                    | 67.2                       | 201.6                |
| DNA             | 1                     |                            |                      |
| Total           | 25                    | 100.8                      | 302.4                |
	- includes concentrations for all 4 samples (3 DNA and 1 negative)

Primers Used: 1N 515F, 1N 806R
Sample 1: NSW2, August, Oyster 2, 2025, Gill
Sample 2: NSW1, August, Oyster 6, 2025, Gill
Sample 3: NSW1, August Oyster 20, 2025, Gill

1) NSW2, August, Oyster 2, 2025, Gill
2) NSW1, August, Oyster 2, 2025, Gill
3) NSW1, August Oyster 2, 2025, Gill
4) NSW2, August, Oyster 6, 2025, Gill
5) NSW1, August, Oyster 6, 2025, Gill
6) NSW1, August Oyster 6, 2025, Gill
7) NSW2, August, Oyster 20, 2025, Gill
8) NSW1, August, Oyster 20, 2025, Gill
9) NSW1, August Oyster 20, 2025, Gill
 Used 16S Touchdown program, started at 11:17

Gel Well Order
Row 1: Ladder, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, Ladder
Row 2: Ladder, Ladder (far right well)

![[Screenshot 2026-07-30 161347.png]]


