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

### Equipment

- Multichannel pipette

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

<img src="../media/cfu-count.png" style="width: 25vw"/>

Figure 1: Schematic of run-down method. 
A serial dilution is pipetted on the medium plate, which is tilted so that the inoculum can run down. 
After an overnight cultivation, the colony-forming units are counted and the titer calculated.

#### Preparation of inoculated agar plates

1. Liquify an appropriate solid medium by reheating it. Store at ~50 °C to keep agar from solidifying.
2. Take 30 mL of liquified solid medium and put it into a 50 mL sterile tube. Wait until hand-warm.
3. Add test strain to liquified solid medium, diluting to the desired concentration (usually 1x10⁵, depending on the test strain). E.g. for a strain with a determined titer of 5.1x10⁸ CFU/mL, inoculate (1x10⁵ * 30 mL)/5.1x10⁸ CFU/mL = 0.00588 = 5.88 µL in 30 mL.
4. Gently mix to distribute the strain in the medium, evading the creation of bubbles. This must only take a few seconds.
5. Quickly pour the medium in an 155 mm petri dish.
6. After cooling, the plate is ready to use in

### Bioactivity testing

#### Dissolve extracts

1. Dissolve the extracts in 100 µL of an appropriate vehicle, compatible with the test strains.
2. Ideally, add the volume in multiple steps, ensuring good dissolution with frequent pipetting (up/down)

#### Apply extracts

1. On the previously prepared [inoculated agar plate](#preparation-of-inoculated-agar-plates), pipet 5 µL of the dissolved extract. Ideally, this is done with a multichannel pipette. Take care to not let the drops flow into each other.
2. Let the vehicle evaporate
3. Incubate overnight.
4. The next day, measure the diameter of growth inhibition halos in milimeters.

## Outcomes

- A WCB of the test organism with determined titers.
- Information on growth inhibition effects of extracts against the organism.

## Notes

- Do not repeatedly freeze-thaw your test strains to prevent degradation of the CFU/mL count. For perfect reproducibility, each strain aliquot should be only thawed once and then discarded.
- With small volumina of inoculum, perform a 1:10 dilution first → 58.8 µL is easier to evenly mix in agar.
- Potential pitfalls are: too cold medium, leading to aggregates; too hot medium, killing the test strain; both lead to non-uniform growth.
- In bioactivity testing, always use an appropriate prositive/negative control.
- Strong biological activity of one extract can sometimes "overshadow" other extracts, making interpretation difficult. In such cases, extracts need to be re-tested with more generous spacing to have a clear readout.
- When transferring the extract onto the plate, the agar can be slightly scratched to indicate the center of the droplet.

## Appendix

| Strain            | Medium           | Inoculation conc | Temperature | Time to OD 0.4 | CFU/mL in bioassay | Solvent for extracts | Positive control  | 
|-------------------|------------------|------------------|-------------|----------------|--------------------|----------------------|-------------------|
| Bacillus subtilis | Mueller-Hinton   | 1 %              | 30 °C       | ca 4 hours     | 1 x 10⁵            | 1, 2, 3              | apramycin 5 mg/mL |
| Escherichia coli  | Mueller-Hinton   | 1 %              | 37 °C       | ca 7 hours     | 1 x 10⁵            | 1, 2, 3              | apramycin 5 mg/mL |

1. 10% DMSO/H2O
2. 50% MeOH/H2O
3. 100% MeOH