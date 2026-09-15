# MSc Thesis – Colorectal Cancer Genomics

## Overview

This repository contains work from my MSc thesis in Bioinformatics Management at George Mason University.

The project investigated somatic mutation patterns across eight key colorectal cancer driver genes :APC, TP53, KRAS, BRAF, SMAD4, TGFBR2, PTEN and PIK3CA, using data from 525 TCGA Pan-Cancer Atlas COADREAD tumours.

The aim was to explore whether recurrent mutations tend to occur at more evolutionarily conserved residues and to assess the biological relevance of these mutation patterns.

## What I did

- Processed and organised somatic mutation data from TCGA
- Identified recurrent mutation hotspots across the eight driver genes
- Performed cross-species sequence conservation analysis
- Applied statistical methods including Mann–Whitney U testing, Spearman correlation and logistic regression
- Interpreted mutation patterns in the context of colorectal cancer biology
- Considered how mutation architecture could influence diagnostic strategy, including when targeted assays may be appropriate versus broader NGS-based profiling

## Tools and methods

- Python
- Pandas
- Biological sequence analysis
- TCGA / cBioPortal data
- Sequence conservation analysis
- Statistical modelling
- Data visualisation

## Key findings

Recurrent mutations generally showed high conservation across species, although the difference between recurrent and non-recurrent residues was not statistically significant.

A weak positive relationship was observed between recurrence frequency and conservation, suggesting that some highly recurrent mutations may preferentially affect biologically constrained residues.

The project also highlighted differences in mutation architecture between genes. For example, hotspot-driven genes such as KRAS and BRAF may be suitable for focused mutation assays, whereas genes with more dispersed mutation patterns, such as APC, may benefit from broader NGS-based profiling.

## Repository contents

- `Thesis_analysis.ipynb` – Jupyter notebook containing the computational analysis
- '798 Research_Project_Final.pdf' – full MSc thesis

## About me

I am a Biomedical Sciences and Bioinformatics graduate interested in cancer genomics, translational research and the use of biological data to support therapeutic and diagnostic decision-making.
