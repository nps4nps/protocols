Actinobacterial strain cultivation
=======

| Version | Date       | Changes | Changed by | 
|---------|------------| --------|------------|
| 1       | 20-07-2026 | Initial version | [Mitja M. Zdouc](https://orcid.org/0000-0001-6534-6609) |

**Authors:**

- [Mitja M. Zdouc](https://orcid.org/0000-0001-6534-6609)

**License:**

- [MIT License](licenses/MIT)

**References:**

- Partially derived from [doi:10.1021/acs.jnatprod.0c00807](https://doi.org/10.1021/acs.jnatprod.0c00807)


Protocol
=======

### Overview

This protocol describes the cultivation of bacterial isolates from cryo-stocks/aliquots in a strain library to extraction-ready cultivation broths.
It also includes the creation of a working cell bank for downstream use.

This protocol is designed for mycelium-forming actinomyces, but can also be used for other slow-growing Gram-positive strains.

### Prerequisites

- Strain isolates located in a strain library.
- Cultivation conditions (cultivation media, temperature, pH) determined.

#### Consumables

- Sterile 1.5 mL tubes
- Sterile toothpicks

#### Reagents

- Per strain, a taxon specific liquid medium (30 mL) and solid medium (1 plate) is needed. Additionally, a non-specific solid medium (1 plate) is needed.
- Sterile 0.9% saline (NaCl) 
- Sterile 50% glycerol/water


### Steps

#### Strain plating

*Duration: a few days to weeks, depending on strain physiology*

1. Retrieve strains from the -80°C freezer, put on ice. Ideally, batches of 10 strains should be retrieved. Return strains to freezer asap.
2. Streak strains using sterile loop w dilution streak. Per strain, two plates should be streaked:
   - one for regular cultivation, using taxon-specific cultivation conditions (medium, temperature). 
   - one for contamination check for fast-growing strains, cultivated at 37 °C overnight.
3. After drying, plates are taped shut to prevent accidental opening. 
4. Plates are kept in a closed plastic box and cultivated in an incubator. 
5. Plates are checked daily for growth/contamination.

#### Vegetative cultivation - from colony

*Duration: three days*

1. Prepare 1.5 mL tubes with 0.75 mL of sterile saline.
2. Pick a single colony with a sterile toothpick, put into saline, crush as much as possible (e.g. with a sterile pestle).
3. Transfer inoculated medium into 50 mL flasks with 15 mL medium
4. Cultivate on an orbital shaker at 200 RPM for three days
5. After vegetative cultivation, check for contamination by plating on non-specific solid medium and cultivating at 37 °C overnight and by inspecting the culture under a light microscope.

#### Preparation working cell bank

*Duration: a few minutes per strain*

*Nota bene: A working cell bank (WCB) acts as a unitary point in time to have reproducible cultivation conditions. Do not repeatedly thaw and freeze your aliquots.*

1. Fill cryovials are 750 µL 50% sterile glycerol/water mixture. 
2. Add 750 µL vegetative culture (ideally in exponential phase)
3. Prepare at least three cryovials: one for production cultivation, one as backup, and one for DNA extraction/sequencing.

#### Vegetative cultivation - from working cell bank

*Duration: two days*

1. Inoculate 15ml medium in 50ml flask with 1.5 mL of thawed WCB aliquot (inoculation volume ca. 10%)
2. Cultivate on an orbital shaker at 200 RPM for two days
3. After three days, continue with [the next step](#production-cultivation---from-vegetative-cultivation)

#### Production cultivation - from vegetative cultivation

*Duration: seven days*

1. Inoculate 15ml medium in 50ml flask with 1.5 mL of exponentially growing culture (inoculation volume ca. 10%)
2. Cultivate on an orbital shaker at 200 RPM for seven days
3. After seven days, continue with [the extraction protocol](../analytical_chemistry/actinobacterial-extraction-protocol-260720.md)

### Outcomes

- A WCB
- Cultivation broths ready for extraction

### Notes

- Plates should be taped shut to prevent accidental opening. Never use paper tape - it can become moldy and represents a contamination source.
- For actinomyces, a good all-round liquid medium is [AF](../media/AF-260720.md), while a good all-round solid medium is [SFM](../media/SFM-260720.md)
- For actinomyces, addition of glass beads to the liquid medium can be useful to break up mycelium clusters 
- For actinomyces, 28 °C is a good all-round cultivation temperature.
