# BioComp-CESC
## Squamous Cell Carcinoma vs Adenocarcinoma

This repository contains the final project for the **Computational Biology Lab**, focused on the analysis of RNA-seq expression data from **TCGA Cervical Cancer (CESC)** samples.

The goal of the project is to identify and characterize molecular differences between  
**Squamous Cell Carcinoma** and **Adenocarcinoma** subtypes.

---

## Project Objectives

- Explore TCGA CESC expression data and metadata  
- Identify **differentially expressed genes (DEGs)** between Squamous and Adenocarcinoma samples  
- Perform **unsupervised analyses** (PCA, clustering) to explore sample structure  
- Conduct **functional enrichment analyses** (GO, Reactome, GSEA)  
- Stratify samples based on selected gene signatures  
- Evaluate subtype separation using **machine learning approaches** (k-NN)

---

## Data Source

- TCGA Cervical Cancer (CESC) RNA-seq data  
- Downloaded using the **recount3** Bioconductor package  
- Only **Primary Tumor** samples were included in the analysis

---

## Methods and Tools

- **R / Bioconductor**
- recount3  
- DESeq2  
- ggplot2, pheatmap  
- clusterProfiler, ReactomePA  
- GSEA  
- k-nearest neighbors (k-NN)

---

## Repository Structure

```text
├── data/               # Processed datasets and metadata
├── scripts/            # R scripts for analysis
├── results/            # Tables and figures (DEGs, enrichment, plots)
├── figures/            # PCA, heatmaps, volcano plots
├── report/             # RMarkdown / PDF report
└── README.md
