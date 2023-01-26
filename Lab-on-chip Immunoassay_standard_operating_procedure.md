![image](https://user-images.githubusercontent.com/123385330/214906547-04878063-bfb9-4e61-acd1-a7732e2e94a3.png)

# **Lab-on-chip Immunoassay Standard Operating Procedure**

## Lab-on-chip competitive immunoassay for the detection of ocean contaminants

**Table 1: Document metadata**

| Edition/Version Number | v0.1 |
| --- | --- |
| Document ID | N/A |
| License | https://creativecommons.org/licenses/by/4.0/ |
| Date released (YYYY-MM-DD) | 2023-01-26 |

**Table 2: Authors**

| **Given name(s)** | **Family name(s)** | **Affiliation** |
| --- | --- | --- |
| Caroline | Murphy | Dublin City University |
| Weili | Guo | Dublin City University |
| Louis | Free | Dublin City University |
| Chloe | Richards | Dublin City University |
| Sean | Power | Dublin City University |
| Ciprian | Briciu-Burghina | Dublin City University |
| Anne | Parle-McDermott | Dublin City University |
| Fiona | Regan | Dublin City University |

## 1.0 Table of Contents

[1.0Table of Contents 2](#_Toc125645100)

[2.0 Executive Summary / Abstract 3](#_Toc125645101)

[3.0 Introduction – competitive immunoassay for detection of marine contaminants 3](#_Toc125645102)

[4.0 Methodology 5](#_Toc125645103)

[4.1Equipment 5](#_Toc125645104)

[4.2 Materials 5](#_Toc125645105)

[4.2.1Analyte standards used and suppliers 5](#_Toc125645106)

[4.2.2Antibodies used and suppliers 5](#_Toc125645107)

[4.2.3Marine contaminant conjugates 5](#_Toc125645108)

[4.3Reagents 6](#_Toc125645109)

[4.4 Assay Protocol 6](#_Toc125645110)

[4.4.1Plasma treatment and silanization of assay surface (PMMA chips or 9795R tape) 6](#_Toc125645111)

[4.4.2 Coating PMMA chips or 9795R tape with contaminant-protein conjugates 6](#_Toc125645112)

[4.5 Analysis 7](#_Toc125645113)

[4.6 Standards used 7](#_Toc125645114)

[4.7 Data Management/Data Delivery (including formats) 7](#_Toc125645115)

[4.8 Contributing Best Practices 7](#_Toc125645116)

[5.0 Annexes 8](#_Toc125645117)

[5.1 LIST OF FIGURES 8](#_Toc125645118)

[5.2 GLOSSARY 8](#_Toc125645119)

[5.3 ACRONYMS 8](#_Toc125645120)

[5.4 REFERENCES 8](#_Toc125645121)

## 2.0 Executive Summary / Abstract

This standard operating procedure (SOP) outlines the protocol for the detection of small molecules (e.g. chemicals of emerging concern and harmful biotoxins) by competitive immunoassay. This document was produced by Dublin City University (DCU) in accordance with Ocean Best Practices and the EU Horizon funded project TechOceanS (Project number 101000858).

## 3.0 Introduction – competitive immunoassay for detection of marine contaminants

This SOP describes the use of a competitive immunoassays to detect three ocean contaminants, an insecticide bifenthrin (BIF), a non-steroidal anti-inflammatory drug (NSAID) diclofenac (DIC), hormone estrone, and harmful algal toxins of interest saxitoxin (STX) and domoic acid (DA), this SOP will be used for the development of a portable lab-on-chip (LOC) microfluidic centrifugal sensor system. Competitive tests are the immunoassay of choice for the detection of small molecules such as chemicals of emerging concern in the ocean and harmful biotoxins. Due to their diminutive size they may only have one epitope (antibody binding region) available for antibody recognition. A competitive enzyme-linked immunoassay (ELISA) requires an antigen specific antibody and a protein-conjugated analyte or 'tracer'. The assay facilitates the determination of the concentration of free analyte (e.g., contaminant) in a sample (Figure 1). The fundamental principle of the competitive immunoassay is that the unknown concentration of analyte competes with a pre-titrated 'tracer' or labelled analyte of known concentration. A competitive curve is generated. The higher the concentration of analyte in the sample, the lower the signal generated, and conversely, the lower the concentration of analyte the higher the signal generated.

The marine contaminants of interest will be detected using a fluorescence-based read-out.

Controls to be included are negative control - blank sample (PBS alone coated on surface) and a positive control - a positive reference standard.

![image](https://user-images.githubusercontent.com/123385330/214906663-22af0f12-9a4e-427e-81b7-db5d5535c65b.png)
Figure 1. Illustration of a competitive immunoassay using bifenthrin detection as an example. Bifenthrin-keyhole limpet haemocyanin (Bif-KLH) is coated on the surface of the well, free bifenthrin is added along with a concentration optimised antibody against bifenthrin (anti-bifenthrin) to the solution. The free bifenthrin competes with Bif-KLH for binding towards anti-bifenthrin. A secondary antibody (anti-species antibody, in this case anti-mouse, because the anti-bifenthrin antibody was generated in a mouse) labelled with or HRP (horse radish peroxidase)) was added (concentration optimised) for detection. A suitable substrate is added and fluorescence is read.

This SOP is intended to facilitate the incorporation ofthese assays onto a multiplex lab-on-chip system for the detection of multiple ocean contaminants bifenthrin, diclofenac **,** estrone and harmful algal toxins saxitoxin and domoic acid (Figure 2).

![image](https://user-images.githubusercontent.com/123385330/214906718-e2afe3dc-fd18-4c39-9ce6-a307cccbf6f5.png)

Figure 2. Incorporation of immunoassays onto a multiplex LOC system. The disc is 120 mm in diameter with each well having a volume of 100 μL. The central hole on the disc is 15mm in diameter allowing it to be placed on a spindle mount of a centrifuge. A microchannel of PSA connects the wells allowing the fluid to flow linearly with manual air valves to control flow from well to well. The detection of contaminants diclofenac, bifenthrin, estrone, domoic acid and saxitoxin using competitive immunoassays will be incorporated onto the multi-plex disc.

This SOP focuses on developing the competitive assay using a '2-well test-chip' (Figure 3), the '2-well test-chip' is comprised of test reservoir (top) and control reservoir (bottom).

![image](https://user-images.githubusercontent.com/123385330/214906764-22bfa86d-339e-4b7c-a5a3-c3328cfd598a.png)

Figure 3. Example of individual PMMA chip. 'Test' - top reservoir, control - bottom reservoir. The chip is fabricated from two layers of PMMA with a PSA layer bonding the layers. The chip has the dimensions of 20mm in width by 25mm in length. A. Shows two reservoirs, top is test and bottom is control, the diagram shows, inlet and outlet valves and microfluidic channel connecting the test and control zone. B. Displays a photographic image of the chip including dimensions.

This document is intended for use by professionals working in the development of technologies for biomonitoring aquatic environments.

## 4.0 Methodology

### 4.1 Equipment

Plasma cleaner linked to oxygen, sonicator water bath, oven (37 ℃, and 60 ℃), fume hood cabinet, fluorescent microscope.

### 4.2 Materials

APTES (3-aminopropyl triethoxysilane), 98% ethanol, phosphate buffer silane (PBS) pH7, Tween-20, polymethyl methacrylate (PMMA), bovine serum albumin (BSA), heyhole limpit haemocyanin (KLH), and detection antibodies were purchased from Merck. Standard analytes were purchased from suppliers shown in section 4.2.1. Contaminant-protein conjugates were either made in-house using Imject kit from Thermo Fisher (product code 11874061) or purchased from a supplier (See section 4.2.3). Capture antibodies were purchased from suppliers or were developed in-house (See section 4.2.2). QuantaRed™ enhanced chemifluorescence kit was purchased from Thermo Fisher (Catalogue number 15159 (Fisher scientific, catalogue number 15159, https://www.thermofisher.com/order/catalog/product/15159)). Microfluidic diagnostic tape material 9795R (polyolefin with silicone adhesive) was purchased from 3M Ireland (https://www.3mireland.ie/3M/en\_IE/p/?Ntt=9795R) (product code 70000126311). Milk marvel was purchased from a local supermarket, Dublin, Ireland.

#### 4.2.1 Analyte standards used and suppliers

- Saxitoxin-dihydrochloride, Merck Ireland, product code 30929, Cas no. 35554-08-06.
- Domoic acid, product code, D6215, Cas no. 14277-97-5
- Diclofenac, Merck, Ireland, Product code SML3086, Cas no. 15037-86-7.
- Estrone, Merck, Ireland, Product code PHR1535, Cas no. 53-1617
- Bifenthrin, Creative Diagnostics, US, product code 343414, Cas no. 99267-18-2.

#### 4.2.2 Antibodies used and suppliers

- Anti-saxitoxin, in-house and agri-sera, Sweden, product code AS11-1690.
- Anti-domoic acid, in-house, product code not applicable
- Anti-diclofenac, Creative Diagnostics, US, product code CABT-L4252.
- Anti-estrone, Abcam, UK, product code AB241064.
- Anti-bifenthrin, Stratech Scientific, Ltd. CABT-L-4603-CRD.

#### 4.2.3 Marine contaminant conjugates

- Saxitoxin-BSA, in-house generated.
- Domoic acid-BSA, in-house generated.
- Estrone-BSA, in-house generated.
- Diclofenac-KLH, Creative Diagnostics, US, DAGA-256-K
- Bifenthrin-KLH, Creative Diagnostics, US, DAG004S

### 4.3 Reagents

- 1-40 μg/mL of coating antigen (small molecule (contaminant/harmful algal toxin) linked to larger carrier protein (BSA or KLH)) in coating buffer (PBS pH7).
- Blocking buffer (e.g., 1-5% milk marvel or bovine serum albumin in PBS pH7).
- Sample antigen (e.g., pollutant, contaminant of interest, appropriately diluted).
- Capture antibody (anti-contaminant e.g., anti-bifenthrin or anti-diclofenac or anti-toxin) diluted in reagent diluent (e.g., 1% BSA-PBS pH7).
- Detection antibody (fluorescently or enzyme-labelled anti-species antibody) in PBS pH7.
- Wash buffer (e.g., phosphate buffer saline (PBS) ph7)
- Enzyme substrate (e.g., QuantaRed™ enhanced chemifluorescence)

### 4.4 Assay Protocol

PMMA chips or 9795R tape are plasma treated before being used in the assay.

#### 4.4.1 Plasma treatment and silanization of assay surface (PMMA chips or 9795R tape)

Perform salinization on poly(methyl methacrylate) (PMMA) chips and 9795R tape to facilitate the binding of the contaminant-protein conjugates to the 'test zone' and the anti-species antibodies to the 'control zone' (Figure 3).

- Plasma-treat chips composed of the 'test' and 'control' zone (See Figure 3) for 5 minutes at approximately 0.7 mBar using oxygen plasma.
- Immediately after plasma treatment, pipette 100 μL volume of 5% APTES in 98% ethanol into each well. Incubate the chips/tape at room temperature for 1 hour in a fume hood.
- Following incubation, wash chips with 10 mL 98% ethanol. Place chips in a 10 cm petri dish and sonicate for 15 minutes in a sonicator water-bath; dry the chips in a 60 °C oven for 1 hour.
- Allow the chips/tape to cool before application of contaminant conjugates (e.g., bifenthrin-BSA).

#### 4.4.2 Coating PMMA chips or 9795R tape with contaminant-protein conjugates

Following plasma and silane treatment (Section 4.4.1of this protocol) allow the chips/tape to cool before application of contaminant-protein conjugates.

- Dilute contaminant-protein conjugates to appropriate dilution (e.g., 1-40 μg/mL bifenthrin-BSA or diclofenac-BSA) in filter sterilised PBS pH7, pipette 100 μL volume into each well, incubate overnight at room temperature (20 °C).
- Wash chips once using 100 μL PBS pH7, and pat dry on tissue paper.
- Block the chips with 200 μL 5% (w/v) milk Marvel in PBS pH7, for 1 hour at 37 °C. (Blocking is carried out to block non-specific binding of antibodies towards non-specific binding sites on the contaminant-protein conjugates (e.g. BIF-KLH)).
- Wash chips once using 100 μL PBS pH7, and pat dry on tissue paper.
- The chips are now ready to progress to the assay.
- A pre-titrated concentration of specific antibody (in a 50 μL volume) (e.g., anti-diclofenac 10 μg/mL or anti-bifenthrin 10 μg/mL)) is added to 50 μL of sample analyte (e.g., diclofenac or bifenthrin (e.g, 0.02, 0.2, 2, 10 and 50 μg/mL) respectively)) diluted in PBS pH7. The mixture is added to the chip/tape. The added sample analyte and surface bound analyte compete for binding sites on the specific antibody. Incubate the samples for up to 1 hour at 37 °C.
- (Serially diluted standards should be included in test development to get a standard curve of known analyte/contaminant concentrations, the analyte of unknown concentration can then be compared to unknown concentrations of contaminant.)
- Discard contents of the chips and wash once using 100 μL PBS pH7, and pat dry on tissue paper.
- Add 100 μL volume of detection antibody (fluorescent or enzyme labelled anti-species antibody, e.g., anti-mouse-FITC or anti-mouse-HRP) appropriately diluted (pre-determined) in PBS pH7. Incubate for up to 1 hour 37 °C.
- Wash chips once using 100 μL PBS pH7, and pat dry on tissue paper.
- (If using an enzyme-labelled substrate, and if the system is using an 'end-point' read-out, the reaction may need to be 'stopped', this is often achieved by changing the pH, for example, by the addition of acid, add 50 μL stop solution (e.g., 10% HCl in water), or use STOP solution supplied by manufacturer of the substate being used).
- Chips/tape are now ready to be imaged/read using a fluorescence microscope or in-house fluorescence detection system.

### 4.5 Analysis

A standard curve can be generated by using a series of dilution standards (for example, using doubling dilutions from 200 to 1.5 ng/mL analyte/contaminant in PBS). Determine the concentration of the sample from the standard curve.

### 4.6 Standards used

For standards, please see section 4.2 of this SOP. The development of an accurate and sensitive sensor is achieved using standards of known concentrations.

### 4.7 Data Management/Data Delivery (including formats)

All data arising from TechOceanS project within DCU is stored on Google drive and on the National Oceanography Centre's Sharepoint, with an additional back-up hard-drive stored in DCU. All experimental work is recorded on DCU laboratory notebook, and all work is referenced on the TechOceanS google drive. All raw data, presentations and meeting minutes are recorded and stored.

### 4.8 Contributing Best Practices

OBP repositories were consulted as reference materials to produce this document. Alliance for Coastal Technologies (ACT) and ARGO data management repositories were the predominant sources of information on OBP structure and style that were used to ensure this document closely adhered to founding principles, and to guarantee its utility in the field of remote biomonitoring technology.

https://repository.oceanbestpractices.org/bitstream/handle/11329/1347/fmars-06-00399.pdf?sequence=1&isAllowed=y

## 5.0 Annexes

### 5.1 LIST OF FIGURES

Figure 1. Illustration of a competitive immunoassay using bifenthrin detection as an example.

Figure 2. Incorporation of immunoassays onto a multiplex LOC system.

Figure 3. Example of individual PMMA chip.

### 5.2 GLOSSARY

| **Term** | **Definition** |
| --- | --- |
| Epitope | Antibody binding region |
| - | - |

### 5.3 ACRONYMS

| **Acronym** | **Expansion** |
| --- | --- |
| ACT | Alliance for Coastal Technologies |
| BIF | Bifenthrin |
| DA | Domoic acid |
| DCF | Diclofenac |
| DCU | Dublin City University |
| ELISA | Enzyme-linked immunosorbent assay |
| FITC | Fluorescein isothiocyanate |
| HRP | Horse radish peroxidase |
| ISO | International Organization for Standardization |
| KLH | Keyhole limpit haemocyanin |
| NOC | National Oceanography Centre |
| NSAID | non-steroidal anti-inflammatory drug |
| OBP | Ocean Best Practices |
| PBS | Phosphate buffer saline |
| PMMA | Polymethyl methacrylate |
| STX | Saxitoxin |
| US | United States |
| w/v | Weight per volume |

### 5.4 REFERENCES

1.Maguire I, Fitzgerald J, Heery B, Nwankire C, O'Kennedy R, Ducrée J, Regan F. Novel Microfluidic Analytical Sensing Platform for the Simultaneous Detection of Three Algal Toxins in Water. ACS Omega. 2018 Jun 30;3(6):6624-6634. doi: 10.1021/acsomega.8b00240. Epub 2018 Jun 20. PMID: 30023955; PMCID: PMC6045346.
