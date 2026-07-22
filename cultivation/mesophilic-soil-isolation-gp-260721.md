Mesophilic soil isolation
=======


| Version | Date       | Changes | Changed by | 
|---------|------------| --------|------------|
| 1       | 20-07-2026 | Initial version | [Mitja M. Zdouc](https://orcid.org/0000-0001-6534-6609) |


**Authors:**

- [Stanislava Kralova](https://orcid.org/0000-0003-3384-5328)
- [Mitja M. Zdouc](https://orcid.org/0000-0001-6534-6609)

**License:**

- [MIT License](licenses/MIT)


# Protocol

## Overview

This protocol focuses on the isolation of spore-forming Gram-positive bacteria from mesophilic soils.

It strikes a balance between the isolation of fastidious strains (pre-cultivation, long cultivation time at low temperatures) and sensible post-isolation processing capabilities (capable of growing without soil extract, on standard maintenance media, at standard temperatures, in liquid culture).

A stepwise post-processing procedure eliminates co-cultures/contaminated isolates while keeping costs low.

A selection of suitable media can be found in the [Appendix](#appendix)

## Prerequisites

### Stock solutions

- Nalidixic acid (CAS Nr. 389-08-2):
  - Stock solution 4 mg/mL (100x) in 0.1 M NaOH, sterile filtration 0.22 µm
  - 10 mL is sufficient for 33 155 mm petri dishes (30 mL)
  - Unstable in aqueous conditions, should be frozen asap
- Cycloheximide (CAS Nr. 66-81-9; caution - toxic!):
  - Stock solution 5 mg/mL (100x) in H20, sterile filtration 0.2 µm 
  - 10 mL is sufficient for 33 155 mm petri dishes (30 mL)
- Sterile 0.9% NaCl solution
- Sterile 50% glycerol/water mixture

### Consumables

- Agar plates (155 mm) w antibiotics and soil extract, 4 per [medium](#appendix)
  - Nalidixic acid 40 µg/mL (0.3 mL of stock) and cycloheximide 50 µg/mL (0.3 mL of stock).
  - [Soil extract](../cultivation_media/soil-extract-260721.md) at 5% (1.5 mL of stock solution).
- Agar plates (60 mm) w antibiotics (as above) but with 1 mL/L [Trace Element Solution](../cultivation_media/trace-element-solution-260720.md) instead of soil extract.
- Liquid medium w antibiotics (as above) but with 1 mL/L [Trace Element Solution](../cultivation_media/trace-element-solution-260720.md) instead of soil extract.
- Sterile toothpicks
- Sterile micropestles compatible with 1.5 mL tubes
- Agar plates (60 mm) with an unspecific medium (LB agar, Mueller-Hinton agar) for contamination testing.

## Steps

### Pre-cultivation

1) Add 3 G of dried, crushed soil in 50 mL flask
2) Add 15 mL of liquid medium
3) Heat in a water bath at 80 °C for 10.0 mins. Rapidly cool to RT using an ice bath.
4) Add cycloheximide to 40 µg/mL (0.15 mL of stock) and nalidixic acid to 50 µg/mL (0.15 mL of stock) to the medium.
5) Incubate at 14 °C at 150 RPM for two weeks. Feed 7.5 mL fresh medium every week
6) After completion of pre-cultivation, decant slurry into 50 mL falcon tube.
7) Allow to settle for 10 mins but do NOT centrifuge. Store one aliquot in 25% glycerol at -80 °C as backup.
8) Perform a serial dilution to -8 using sterile 0.9% saline, starting from 100 µL of the pre-culture.
9) Plate 100 µL of dilution step -5 to -8 on previously prepared 155 mm agar plates.
10) Cultivate plates at 12-14 °C for up to 6 months. Colonies can be picked and processed whenever they appear.

### From plate to cryostock

1) Before picking the colony, document it (including pictures). Pick single colonies with a sterile toothpick and put them in 0.5 mL of sterile saline in 1.5 mL tube.
2) If colony is solid, crush colony with a sterile micropestle
3) Perform a dilution streak on a 60 mm agar plate (containing the medium the strain has initially grown on, with antibiotics, with [TES](../cultivation_media/trace-element-solution-260720.md) replacing [soil extract](../cultivation_media/soil-extract-260721.md))
4) Incubate at 28 °C until colonies appear, for a maximum of two weeks. [1]
5) Repeat steps 1) and 2), inoculating a 50 mL flask containing 15 mL of liquid medium (containing the medium the strain has initially grown on, with antibiotics, with [TES](../cultivation_media/trace-element-solution-260720.md) replacing [soil extract](../cultivation_media/soil-extract-260721.md))
6) Cultivate at 200 RPM at 28 °C for three days.
7) After three days, store 1.5 mL aliquots of the culture at 25% glycerol. Also retrieve an aliquot for [16S colony PCR](../molecular_biology/16S-colony-pcr-260722.md).
8) Continue with [post-processing](#post-processing)

### Post-processing [2]

1) Inspect the culture using light microscopy (1000x magnification, oil immersion). If the culture is visibly mixed (expect for putative spores), discard the isolate, else continue with 2).
2) Streak an aliquot of the culture on unspecific medium and cultivate at 37 °C overnight. If a visible contamination appears, discard the isolate, else continue with 3).
3) Perform [16S colony PCR](../molecular_biology/16S-colony-pcr-260722.md) and sequence the PCR product. Any contamination/co-culture should be visible in the sequencing data.

## Outcomes

This protocol results in isolate aliquots ready for [strain cultivation](../cultivation/actinobacterial-strain-cultivation-260719.md), followed by [extract plate preparation](../analytical_chemistry/actinobacterial-extraction-protocol-260720.md) and [bioactivity testing](../assays/microbial-growth-inhibition-260721.md).

## Notes

- [1] Drop-outs at this stage are incapable of adapting to mesophilic conditions and can be considered incompatible with a medium throughput natural product drug discovery approach.
- [2] The cleanup of co-cultures/contaminated isolates is very costly and should only be attempted in exceptional cases. A bird in the hand is worth two in the bush.

## Appendix

| Medium                                       | Specificity                                                         |
|----------------------------------------------|---------------------------------------------------------------------|
| [SN](../cultivation_media/SN-260721.md)      | Selects for degraders of complex carbohydrates, such as actinomyces |
| [ISP2](../cultivation_media/ISP2-260721.md)  | Rich medium, suitable for actinomyces                               |
