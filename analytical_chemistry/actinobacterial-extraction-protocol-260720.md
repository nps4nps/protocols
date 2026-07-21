Actinobacterial extraction protocol
=======

| Version | Date       | Changes | Changed by | 
|---------|------------| --------|------------|
| 1       | 21-07-2026 | Initial version | [Mitja M. Zdouc](https://orcid.org/0000-0001-6534-6609) |

**Authors:**

- [Mitja M. Zdouc](https://orcid.org/0000-0001-6534-6609)

**License:**

- [MIT License](licenses/MIT)

**References:**

- Partially derived from [doi:10.1021/acs.jnatprod.0c00807](https://doi.org/10.1021/acs.jnatprod.0c00807)


# Protocol

## Overview

This protocol describes the extraction of bacterial cultivation broths.

It extends the [actinobacterial strain cultivation](../cultivation/actinobacterial-strain-cultivation-260719.md) protocol, starting from bacterial cultivation broths, and resulting in 96 well plates with extract aliquots.
Due to the storage format, this protocol is primarily intended to process batches of 80 cultivation broths.
However, also smaller batches can be processed and stored until sufficient extracts for a 96 well plate are generated.

While primarily designed for mycelium-forming actinomyces, this protocol can also be used for other bacterial strains with well-developed biomass.


## Prerequisites

### Consumables

- 80 cultivation vessels with bacterial cultures
- Per cultivation vessel, prepare and label 5 x 15 mL tubes:
    - One for mycelium pellet (abbreviation: MYC)
    - One for resin (HP)
    - One for mycelium extract (MYC2)
    - One for supernatant extract (SNT)
    - One as preliminary storage (FIN)
- 25 x 96 well microtiter plate with 300 µL volume, conical bottom
- 25 x 96 well microtiter plate covers
- 1 x 96 well deepwell plate with 1.5 mL volume (ideally conical bottom)

### Reagents

- MeOH 100%
- MeOH 80%/Water
- Activated HP20 resin (Diaion)

### Special equipment

- Multichannel pipettes

## Steps

### Aliquot microbial culture

1. Transfer 10 mL of microbial culture into MYC
2. Centrifuge at 4000 rpm for 10 minutes. Take care to balance the centrifuge. 
3. Decant the resulting supernatant to HP. 
4. Leave pellet in MYC.

### Mycelium extract preparation

*Nota bene: can be run in parallel with [Supernatant extract preparation](#supernatant-extract-preparation)*

1. Add 4 mL MeOH 100% to MYC
2. Vortex to resuspend the mycelium (sonication can help)
3. Shake for 10 mins at room temperature (RT) (tubes should be horizontal)
4. Centrifuge at 4000 rpm for 10 minutes. 
5. Transfer the supernatant to MYC2 and keep at -20 °C

### Supernatant extract preparation

*Nota bene: can be run in parallel with [Mycelium extract preparation](#mycelium-extract-preparation)*

1. Add ca 2 mL of suspended HP20 resin to HP tube containing supernatant (corresponding to 1mL packed HP-20 resin). Use a 5 mL serological pipette with pre-cut tip (wide bore).
2. Shake for 30 mins at RT to load the resin (tubes should be horizontal)
3. Centrifuge at 4000 rpm for 3 minutes. 
4. Carefully decant and discard the spent supernatant without losing the resin.
5. Wash by adding 6 mL of demineralized (DEMI) water to the resin (with 25mL H2O pipette)
6. Vortex for a few seconds and then centrifuge at 4000 rpm for 3 minutes
7. Carefully decant the wash water and discard.
8. Add 4 mL 80% MeOH to HP tube
9. Shake for 30 minutes at RT to unload the resin (tubes should be horizontal)
10. Centrifuge at 4000 rpm for 3 minutes. 
11. Carefully decant the methanolic supernatant to SNT tube and keep at -20 °C
12. (Optional: Resuspend the spent HP20 resin in a few mL of MeOH 100% and store for future use)

### Prepare storage

1. Retrieve MYC2 and SNT from storage at -20 °C
2. Centrifuge at 4000 rpm at 4 °C for 10 minutes to clear any suspended particles.
3. Combine 3 mL of mycelium extract (MYC2) and 3 mL of supernatant extract (SNT) in the FIN tube.
4. Store at -20 °C and continue with the point [Extract aliquotation and storage](#extract-aliquotation-and-storage)

### Extract aliquotation and storage

*Nota bene: extracts are at ~90% MeOH, which evaporates quickly. Always cover the reservoir with covers to prevent evaporation and work in a well-ventilated environment.*

#### Preparation

1. Take the FIN tubes from cold storage and let them reach RT. Centrifuge for 10 min at 3000 RPM to remove any suspended particles. Extracts must be clear before further processing.
2. Prepare a document to relate extract metadata with well positions.
3. For each extract, transfer 1 mL to a position on the deepwell plate.
4. Depending on the remaining extract, continue with either [microtiter](#96-well-microtiter-plate-preparation) or [deepwell](#96-well-deepwell-plate-preparation) preparation.


#### 96-well microtiter plate preparation

1. Transfer 200 µL of the extract from the deepwell plate into each well of the microtiter plate, ideally using a multichannel pipette.
2. In this way, prepare 25 copies of the deepwell plate. Re-fill the deepwell-plate after every 5 plates [as described](#preparation)
3. Dry plates in the vacuum oven at 40 °C overnight, keeping the pressure at ~200 mbar to prevent bumping.
4. After removal of methanol, evaporate the residual water at ~50 mbar.
5. After the plates are fully dried, seal them appropriately to prevent rehydration, and keep at -20 °C.

### 96-well deepwell plate preparation

1. After preparation of 25 x 96 well microtiter plates, the deepwell plate should contain a residual volume 1 mL of FIN extract.
2. Dry the plate in the vacuum oven at 40 °C overnight, keeping the pressure at ~200 mbar to prevent bumping.
3. After removal of methanol, evaporate the residual water at ~50 mbar. Oftentimes, this needs to be decreased close to 0 mbar to remove all residual water.
4. After the plates are fully dried, seal them appropriately to prevent rehydration, and keep at -20 °C.

## Outcomes

This protocol results in a set of 25 x 96 well microtiter plates and 1 x 96 well deepwell plate.

## Notes

- The microtiter extract plates are the first real endpoint of the cultivation-extraction workflow. From this point in time, all further analyses are performed (e.g. bioactivity testing, LCMS analysis)
- The deepwell extract plate serves as an initial stock from which promising extracts can be cherry-picked.
- Extract plates are not indefinitely stable. Try to acquire LCMS data as soon as possible after preparation to have a reference point.

















