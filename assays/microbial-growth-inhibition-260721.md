Microbial growth inhibition assay
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

This protocol allows to perform microbial growth inhibition assays in a reproducible, medium-throughput manner.

It allows to directly test a whole 96 well plate of microbial broth extracts against a test strain, without the need of specialized equipment.

This protocol can also be used to test individual extracts

## Prerequisites

### Consumables

- Medium (92 mm diameter) petri dishes
- Large (155 mm diameter) petri dishes

### Reagents

- Liquid and solid medium supporting the growth of the test organism
- Positive control
- Solvent for extract dissolution
- Sterile 50% glycerol/water 


## Steps

### Preparation of test strains

For this protocol, the titer of the test strains must be first determined (colony-forming units, CFUs/mL).
For growth conditions and other variables of test strains, see the [Appendix](#appendix)

#### Preparation of test strain aliquots (working cell bank)

1. Plate test strains using a dilution streak on a 92 mm petri dish with unselective solid medium and incubate at required temperature overnight.
2. Pick single colonies and incubate in 10 mL of medium in a 50 mL flask. Incubate at 200 RPM overnight.
3. Using the overnight culture, inoculate a new flask of 10 mL at the specified inoculation concentration. 
4. Incubate at 200 RPM and grow the strain to a density of 0.4 OD 600nm
5. Prepare aliquots of 250 µL (e.g. in 1.5 mL tubes) and add 250 µL of 50% glycerol/water (w/w) to reach a final glycerol concentration of 25%.
6. Freeze strains at -80 °C. The aliquots now represent your working cell bank (WCB)

#### Determination of titers

1. Retrieve a test strain aliquot from the WCB.
2. Create a serial dilution of 10⁻² to 10⁻⁸.
3. On a 155 mm petri dish, cultivate 20 µL of the 10⁻⁴-10⁻⁸ dilutions using the run-down-streak method (see Figure 1). Perform at least duplicates. Incubate overnight.
4. Next day, count the colony-forming units per dilution step and calculate the titer with the formula (nCFU/(amount of inoculum in mL x dilution)); e.g. (60/(0.02 mL x 10⁻⁴)) = 3 x 10⁷ CFU/mL. Calculate for several dilutions and take the average.
5. The calculated titer is valid for all aliquots in the WCB.







## Outcomes


## Notes

- Do not repeatedly freeze-thaw your test strains to prevent degradation of the CFU/mL count. For perfect reproducibility, each strain aliquot should be only thawed once and then discarded.


## Appendix

| Strain            | Medium           | Inoculation conc | Temperature | Time to OD 0.4 | CFU/mL in bioassay | Solvent for extracts                  | Positive control  | 
|-------------------|------------------|------------------|-------------|----------------|--------------------|---------------------------------------|-------------------|
| Bacillus subtilis | Mueller-Hinton   | 1 %              | 37 °C       | ca 4 hours     | 1 x 10⁵            | 10% DMSO/H2O, 50% MeOH/H2O, 100% MeOH | apramycin 5 mg/mL |
| Escherichia coli  | Mueller-Hinton   | 1 %              | 37 °C       | ca 7 hours     | 1 x 10⁵            | 10% DMSO/H2O, 50% MeOH/H2O, 100% MeOH | apramycin 5 mg/mL |