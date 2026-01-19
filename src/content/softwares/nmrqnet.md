---
title: "NMRQNet"
developers: ["Liu Lab"]
link: "https://github.com/LiuzLab/NMRQNet"
date: 2026-01-19
description: "Deep-learning-based pipeline for automatic identification and quantification of dominant metabolites within human plasma samples using NMR spectra."
---

Nuclear magnetic resonance (NMR) is a powerful platform that reveals the metabolomic profile of biofluids or tissues and holds great promise for precision medicine. However, its clinical application has been hindered by the volume and complexity of NMR spectra data as well as the lack of fast and accurate computational tools that can automatically identify and quantify essential metabolites. We present NMRQNet, a deep-learning-based pipeline that can quickly, automatically identify and quantify dominant metabolite candidates within human plasma samples.

NMRQNet takes advantage of CNN, with its achievements in image classification, highlights the spectral features that best separate different metabolites. GRU, with its signal processing abilities, uses the CNN-extracted signals to learn the positional dependencies for clusters belonging to the same metabolite. By combining these two model architectures, the CRNN framework (CNN and GRU) efficiently captures the dominant metabolites.

![NMRQNet](../../assets/softwares/NMRQNet.png)
