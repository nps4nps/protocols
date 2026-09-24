Actinobacterial strain cultivation
=======

| Version | Date       | Changes | Changed by | 
|---------|------------| --------|------------|
| 1       | 16-09-2026 | Initial version | [Mitja M. Zdouc](https://orcid.org/0000-0001-6534-6609) |

**Authors:**

- [Mitja M. Zdouc](https://orcid.org/0000-0001-6534-6609)

**License:**

- [MIT License](licenses/MIT)

**References:**

- Partially derived from [Rutz et al.](https://doi.org/10.3389/fpls.2019.01329)


# Protocol

## Overview

This protocol describes the preparation of samples for HR-LCMS (high resolution liquid chromatography mass spectrometry) analysis.

The LCMS method described is a fast "discovery" untargeted metabolomics method in positive ion mode, primarily intended to acquire data from microbial cultivation broth extracts for screening purposes. 
It can also be used for other biological extracts, such as plant extracts.
The method allows to analyze ~6 samples per hour

This protocol is particularly suitable to analyze samples resulting from the [actinobacterial extraction protocol](actinobacterial-extraction-protocol-260720.md), assuming some kind of solid phase extraction of the supernatant. 
For other extraction protocols, a filtering step may be considered during [preparation](#sample-and-pooled-qc-preparation) to remove insoluble particles and protect column and instrument.


## Prerequisites

- 96 well plate with extracts (or alternative storage format).
- A short, reverse phase (HP20) column, mass spectrometry grade, with installed pre-column of the same material (e.g. [MN NUCLEOSHELL RP 18plus, 2.7 µm, 50x2 mm](https://www.mn-net.com/de-en/EC-HPLC-column-analytical-NUCLEOSHELL-RP-18plus-2.7-m-50x2-mm-763232.20))
- High resolution LC-MS instrumentation (e.g. qTOF).

### Consumables

- 2 mL HPLC vials with 100 µL microinserts
- 1.5 mL reaction tubes
- Pipette tips

### Reagents

- MeOH 80%/Water (the same as used in the [extraction protocol](actinobacterial-extraction-protocol-260720.md))

## Steps

### Sample and pooled QC preparation

1. Retrieve 96 well plates with extracts from storage, allow to acclimate for a few minutes
2. Dissolve extracts in 200 µL MeOH 80%/Water in stepwise fashion. First, dissolve the residue in 100 µL solvent, pipetting vigorously before transferring to the 1.5 mL tube. This process is repeated once more.
3. Mix the dissolved sample by brief vortexing.
4. Centrifuge 1.5 mL tubes at 4 °C at 16000 RPM for 10 mins.
5. Transfer 10 µL of supernatant to HPLC vial containing a microinsert. Add 90 µL of solvent. This results in a 1:10 diluted sample.
6. For the pooled quality control sample (QC), add 1 µL of each sample supernatant to a separate reaction tube. Dilute 1:10 and transfer to a HPLC tube with microinsert.

If cultivation media extract blanks are included, prepare them in an identical fashion. Note that these samples are considered blanks and are not included in the pooled QC

### LCMS analysis

#### Liquid chromatography

- Injection volume 2 µL
- Flow rate 0.6 mL/min
- Column oven 40 °C
- Gradient using solvent A (H2O + 0.1% formic acid) and solvent B (MeCN + 0.1% formic acid + 1% H2O)
  - 0 - 0.5 min (5% B)
  - 0.5 - 7.5 min (5-100% B)
  - 7.5 - 8.5 min (100% B)
  - 8.5 - 8.6 min (100%-5% B)
  - 8.6 - 9.5 min (5% B)

#### Mass spectrometry

- Spray voltage: 5200 V
- MS1: 100-2000 Da
- Gas1 (N2): 50 psi
- Gas2 (N2). 70 psi
- Curtain gas: 30 psi
- CAD gas: 7
- Temperature: 500 °C
- Accumulation time: 0.15 s
- Deconvolution potential (DP): 80 V
- DP spread: 0 V
- Collision energy (CE): 10 V
- CE spread: 0 V
- DDA criteria: small molecule
- Maximum candidates: 5
- Intensity threshold: 5 cps
- Dynamic background subtraction: enabled
- Exclude former candidate ions: enabled for 2 s after 1 occurrence
- Dynamic accumulation: enabled
- Exclude isotopes: 2 Da
- MS2 window: 40-1000 Da
- DP: 80 V
- DP spread: 0 V
- Accumulation time: 0.06 s
- Collision energy: 35 V
- CE spread: 15 V

## Outcomes

- LCMS data of samples, ideally converted to an open format such as .mzML

## Notes

- This method is particularly suited for amphiphilic molecules. Highly hydrophilic or hydrophobic molecules will suffer from imperfect resolution.
- To prevent data loss, make sure to submit your newly generated data to a data management plan.
- If working with a [96 well extract plate](actinobacterial-extraction-protocol-260720.md), work on one column at a time to reduce solvent evaporation, which can lead to variability in concentration and decrease reproducibility. Use a multichannel pipette if possible.