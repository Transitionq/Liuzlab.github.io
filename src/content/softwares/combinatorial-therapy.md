---
title: "Combinatorial Therapy Discovery using Mixed Integer Linear Programming"
developers: ["Liu Lab"]
link: "http://drug.35.164.194.24/"
date: 2026-01-19
description: "Mathematical algorithms (BTSC and MOTSC) for optimal combinatorial therapy prediction."
---

Combinatorial therapies play increasingly important roles in combating complex diseases. Due to the huge cost associated with experimental methods in identifying optimal drug combinations, computational approaches can provide a guide to limit the search space and reduce cost. However, few computational approaches have been developed for this purpose and thus there is a great need of new algorithms for drug combination prediction.

Here we proposed to formulate the optimal combinatorial therapy problem into two complementary mathematical algorithms, Balanced Target Set Cover (BTSC) and Minimum Off-Target Set Cover (MOTSC). Given a disease gene set, BTSC seeks a balanced solution that maximizes the coverage on the disease genes and minimizes the off-target hits at the same time. MOTSC seeks a full coverage on the disease gene set while minimizing the off-target set. Through simulation, both BTSC and MOTSC demonstrated a much faster running time over exhaustive search with the same accuracy. When applied to real disease gene sets, our algorithms not only identified known drug combinations, but also predicted novel drug combinations that are worth further testing. In addition, we developed a web-based tool to allow users to iteratively search for optimal drug combinations given a user-defined gene set.

![Combinatorial Therapy](../../assets/softwares/Screen-Shot-2014-01-28-at-11.23.10-PM.png)
