---
title: "SPA-STOCSY"
developers: ["Liu Lab"]
link: "https://github.com/LiuzLab/SPA-STOCSY"
date: 2023-09-01
description: "Spatial clustering algorithm – Statistical total correlation spectroscopy for identifying annotated and non-annotated metabolites in high-throughput NMR spectra."
---

SPA-STOCSY is an automated tool for identifying annotated and non-annotated metabolites in high-throughput NMR spectra. Metabolomics (the study of all metabolites in a given sample) can be a promising candidate for quantitative phenotyping and biomarker discovery. Nuclear magnetic resonance (NMR) is one of the main platforms used to acquire metabolomic data. To accelerate the application of NMR metabolomics in medicine and biology, we present SPA-STOCSY.

SPA exploits strong correlations among datapoints from the multiplets (multiple peaks belonging to the same metabolite) and identifies local spatial clusters of contiguous datapoints highly likely to arise from the same metabolite cluster. With the SPA-derived clusters as input, STOCSY is then used to highlight the correlation map and arrange clusters into highly correlated groups containing signals from the same metabolite. This work has been published in Bioinformatics (https://doi.org/10.1093/bioinformatics/btad593).

![SPA-STOCSY](../../assets/softwares/SPA-STOCSY.png)
