![image](https://user-images.githubusercontent.com/2276146/214634819-74452c30-fc7d-4b8e-9017-1410a9b55d31.png)


# **CRISPR Cas – RPA Assay**

## _Standard Operating Procedure_

**Table 1: Document metadata**

|Key | Value |
| --- | --- |
| Edition/Version Number | v0.1 |
| Document ID | N/A |
| License | https://creativecommons.org/licenses/by/4.0/ |
| Date released (YYYY-MM-DD) | 2023-01-17 |

**Table 2: Authors**

| **Given name(s)** | **Family name(s)** | **Affiliation** |
| --- | --- | --- |
| Fiona | Bracken | Dublin City University |
| Paola | Drago | Dublin City University |
| Anne | Parle-McDermott | Dublin City University |
| Fiona | Regan | Dublin City University |

# Table of Contents

- 1 **Executive Summary**
- 2 **Introduction** 
- 3 **CRISPR Cas – RPA Assay Protocol**
  - 3.1 **Recombinase Polymerase Amplification (RPA)**
  - 3.2 **CRISPR-Cas Detection**
  - 3.3 **Schematic summary**
- 4 **Materials**
  - 4.1 **Instruments**
  - 4.2 **Reagents**
- 5 **Contributing Methods**
-6 **References**


# 1 Executive Summary

This standard operating procedure (SOP) outlines the protocol for the detection of eDNA from target species using a combined RPA/CRISPR-Cas protocol, which allows for the amplification of target-specific DNA, followed by its detection (fluorescence-based). This document was produced by the Dublin City University in accordance with Ocean Best Practices and the TechOceanS project.

# 2 Introduction

This isothermal method for the capture and analysis of eDNA makes use of Recombinase Polymerase Amplification (RPA) in combination with CRISPR-Cas detection methods (Williams et al., 2019). Recombinase-primer complexes allow for strand exchange at cognate sites, which are formed and disassembled continuously in the amplification of target DNA. The amplified RPA product is subsequently added to the CRISPR‐Cas12a fluorescent detection system. CRISPR-Cas12 mechanisms recognize DNA targets that are complementary to a short CRISPR RNA (guide RNA) sequence. In order for the Cas12a nuclease to function (i.e., activate cleavage activity), a specific protospacer adjacent motif (PAM) is required. The collateral cleavage activity of Cas12a is initiated upon recognition of a target DNA sequence and PAM site and consequently cleaves a single-stranded DNA fluorescent reporter (from TechOceans report Deliverable 3.1 Design of high-capacity ecogenomic sampler, processor, and molecular assays).

# 3 CRISPR Cas – RPA Assay Protocol

## 3.1 Recombinase Polymerase Amplification (RPA)

- Combine 2.4 µl forward primer (10 µM), 2.4 µl reverse primer (10 µM), 29.5 µl rehydration buffer (TwistDX), and 5.7 µl molecular grade water in 0.2 ml PCR tube.
- Transfer 41 µl to the RPA pellet and mix.
- Add 5 µl eDNA extract (for environmental sample- 2 µl when using DNA extracted from tissue).
- Add 5 µl MgOAc to the lid of the RPA tube.
- Centrifuge to combine MgOAc into the tube and initiate the reaction.
- Incubate at 37 °C for 10 mins.
- Manually mix the RPA tube and centrifuge to bring the liquid to the bottom of the tube. Incubate at 37 °C for 30 mins. (If visualising on a gel, incubate for 10 mins at 65 °C – not needed if going straight to the CRISPR step).
- Ensure positive and negative controls are also carried out at this step.

## 3.2 CRISPR-Cas Detection

- Combine 3.2 µl PBS, 1.6 µl gRNA (10 µM) and 0.2 µl _As Cas12a_ nuclease in 0.2 ml tube and incubate at room temperature for 20 mins to form Ribonucleoprotein (RNP).
- Dilute RNP 1:10 (e.g., add 45 µl molecular grade water to 5 µl RNP).
- Make CRISPR detection master mix as follows: 4 µl RNP, 0.1µl FQ reporter (100 µM), 2 µl NEB buffer 2.1 (10X) and 11.9 µl molecular grade water.
- Dispense 18 µl master mix per reaction into a 96-well plate. Three reactions are required per sample (including positive and negative RPA controls in triplicate and a CRISPR negative in triplicate).
- Add 2 µl of RPA product into each well. Seal plate and centrifuge.
- Incubate at 37 °C for 30 Mins (or longer) with fluorescence measurements taken every 30 secs (FAM ƛex = 485 nm, ƛem = 535 nm).

## 3.3 Schematic summary

**RPA MasterMix** (per reaction, 45 µl)

| Reagent | Volume |
| --- | --- |
| Fwd primer (10 µM) | 2.4 µl |
| Rev primer (10 µM) | 2.4 µl |
| TwistDX Buffer | 29.5 µl |
| eDNA | 5 µl |
| H2O | 5.7 µl |
| MgOAc | 5 µl |

**Add the MgOAc to start the reaction**

Incubate at 37°C for 40 min total.

**RNP Mix** (per reaction, 5µl)

| Reagent | Volume |
| --- | --- |
| PBS: | 3.2 µl |
| gRNA (10 µM): | 1.6 µl |
| As Cas12a (62 µM): | 0.2 µl |

Dilute 1:10 before adding it to the CRISPR Mix.

**CRISPR Master Mix** (per reaction, 18 µl)

| Reagent | Volume |
| --- | --- |
| Diluted RNP | 4 µl |
| FQ Reporter (100 µM) | 0.1 µl |
| NEB 2.1 Buffer (10X) | 2 µl |
| H2O | 11.9 µl |
| RPA product | 2 µl |

**Add the RPA product to start the reaction**

Incubate in Light Cycler at 37°C for 30 to 120 min.

# 4 Materials

## 4.1 Instruments

- Thermo Block / Incubator
- Roche Light Cycler 480

## 4.2 Reagents

| Product | Manufacturer | Catalogue Number |
| --- | --- | --- |
| RPA kit | Twist DX | TABAS03KIT |
| Alt-R® A.s. Cas12a (Cpf1) V3, 500 µg | IDT | 1081069 |
| Primers | IDT (or others) | -- |
| Alt-R® A.s. Cas12a crRNA, 10 nmol (gRNA) | IDT | -- |
| Custom ssDNA-FQ Reporter | IDT | -- |
| PBS | Gibco | 14190094 |
| Molecular grade water | Sigma-Aldrich | W4502-1L |

# 5 Contributing Methods

OBP repositories were consulted as reference materials for the production of this document. Alliance for Coastal Technologies (ACT) and ARGO data management repositories were the predominant sources of information on OBP structure and style that were used to ensure this document closely adhered to founding principles, and to guarantee its utility in the field of remote biomonitoring technology.

https://repository.oceanbestpractices.org/bitstream/handle/11329/1347/fmars-06-00399.pdf?sequence=1&isAllowed=y

# 6 References

Williams, M.-A., O'Grady, J., Ball, B., Carlsson, J., de Eyto, E., McGinnity, P., Jennings, E., Regan, F., & Parle-McDermott, A. (2019). The application of CRISPR-Cas for single species identification from environmental DNA. _Molecular Ecology Resources_, _19_(5), 1106–1114. https://doi.org/10.1111/1755-0998.13045
