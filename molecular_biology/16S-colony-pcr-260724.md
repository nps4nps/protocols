16S rRNA-DNA colony PCR amplification
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


# Protocol

## Overview

A sturdy 16S rRNA-DNA amplification method directly from a colony/cultivatino broth.

## Prerequisites

### Reagents

- Eubacterial primer F27 at 10 µM concentration 
- Eubacterial primer R1492 at 10 µM concentration 
- PCR mix per sample (50 µL per sample + 50 µL as loss)
  - 12 µL of PCR-grade water
  - 25 µL of DreamTaq Green PCR Master Mix 2X (Thermo Scientific)
  - 3 µL of 10x Denhardt's reagents (Thermo Scientific)
  - 2.5 µL primer F27 (to reach final concentration of 0.5 µM)
  - 2.5 µL primer R1492 (to reach final concentration of 0.5 µM)
  - 5 µL of colony lysate
- Genomic DNA (positive control)
- PCR-grade water (negative control)
- Agarose
- TBE electrophoresis buffer 1%
- Gel stain dye (e.g. SYBR Safe Thermo Scientific 10,000X)
- DNA gel extraction kit


## Steps

### Preparation of template

1. Lyse 10 µL of liquid culture (or a single colony) at 95 °C in 100 μL of PCR-grade water for 5 min.
2. Spin down for ~30 sec @ 15,000 RPM. Store on ice.

### PCR preparation

1. Add 5 µL of culture lysate to 45 µL of prepared PCR mix
2. As a positive control, add 1 µL of genomic DNA + 4 µL of PCR-grade water to 45 µL of prepared PCR mix
3. As a negative control, add 5 µL of PCR-grade water to 45 µL of prepared PCR mix
4. Run the PCR protocol.

### PCR Protocol

- Initial denaturation: 95 °C for 2.0 mins
- 35 cycles of:
  - Denaturation: 95 °C for 0.5 mins
  - Annealing: 60 °C for 0.5 mins
  - Extension: 72 °C for 1.0 mins
- Final elongation: 72 °C for 10.0 min
- Hold: 4 °C inf. This is a safe stop.

### Gel purification

1) Prepare 0.8% agarose in 1% TBE electrophoresis buffer by heating until clear. 
2) Wait 5 mins, then add 5 µL of a 10,000X gel stain per 100 mL of agarose
3) Pour gel, add combs
4) After gel has solidified, put into run chamber and cover with TBE 1%
5) Load PCR reaction mixture into wells. Samples should be separated by an empty chamber to facilitate follow-up cutting and extraction.
6) Add 1 µL of a 1 kb DNA ladder, noting down the vendor
7) Run at 120 eV for 60 min.

### Gel extraction

1) After electrophoresis, keep developed gel on plastic carrier and take a picture in UV chamber, annotate.
2) Install the UV guard. While on the plastic carrier, cut the desired band with a scalpel, taking care to not excise unspecifically amplified DNA. Trim excess gel. Transfer to a weighted 1.5 mL tube, note down weight of excised gel.
3) Perform DNA extraction using an extraction kit. Follow instructions of the gel extraction kit.
4) Prepare a 1% agarose gel to verify extraction. Mix 1 µL of extracted PCR product with 9 µL of loading dye (1X). Run gel at 120 eV for 30 mins to check extraction quality.
5) If extraction is satisfactory, check concentration at nanodrop.

### Sequencing

*Nota bene: follow instructions of your sequencing provider*

### Taxonomic assignment

Blast against NCBI 

## Outcomes

Putative taxonomic assignment of strains based on 16S sequencing and BLAST

## Notes

- Large gels are usually 200 mL, small gels 60 mL
- A small gel can hold ~20 µL of PCR mixture in its chamber.


