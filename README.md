# BSG_Thesis

Master's thesis on the use of **Brewer's Spent Grain (BSG)** in breadmaking, focusing on enzymatic treatment with xylanase and the analysis of crumb structure through digital image processing.

## Research goal

Evaluate how the addition of BSG (at different substitution levels, with and without enzymatic treatment) affects the technological and structural quality of bread, and develop a reproducible image-based method to quantify crumb porosity.

## Repository structure

```
BSG_Thesis/
├── 02_Proposal/                  Thesis proposal and writing
│   ├── Literature_Review_BSG_Thesis_03.docx
│   ├── Literature_Review_Flowchart.html
│   └── Results_Discussion_ThesisSection.docx
│
├── 03_LabWork/                   Experimental data and bread photos
│   ├── BSG_Experimental_Results.xlsx
│   ├── Bread_control/            0% BSG (reference)
│   ├── Bread_10_/                10% BSG
│   ├── Bread_10_+xyl/            10% BSG + xylanase
│   ├── Bread_20_/                20% BSG
│   ├── Bread_20_+xyl/            20% BSG + xylanase
│   └── Bread_pictures_overview/  Combined sample views
│
└── bread_porosity_analyzer_v5.html
                                  BreadScan — standalone web tool
                                  for crumb porosity analysis
```

## BreadScan

`bread_porosity_analyzer_v5.html` is a self-contained HTML/JS application that loads a photograph of a bread cross-section and computes porosity metrics (pore count, size distribution, total porous area). It runs entirely in the browser — open the file directly, no server required.

## Author

Lucia Buzzeo
