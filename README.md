# TCGA-LUAD-DEG-Analysis

## Project Overview

This project investigates transcriptomic differences between lung adenocarcinoma tissues and normal lung tissues using TCGA-LUAD RNA-seq data.

## Dataset

- Project: TCGA-LUAD
- Cancer Type: Lung Adenocarcinoma (LUAD)
- Source: GDC Data Portal
- Samples:
  - 540 Primary Tumor
  - 59 Solid Tissue Normal

## Bioinformatics Workflow

1. Download TCGA-LUAD RNA-seq data
2. Data preprocessing
3. Differential expression analysis using DESeq2
4. Volcano Plot visualization
5. Principal Component Analysis (PCA)
6. Heatmap of top DEGs
7. GO enrichment analysis
8. KEGG pathway analysis

## Results

### Differential Expression Analysis

Summary of DESeq2 results:

- Upregulated genes (padj < 0.1): 21,886
- Downregulated genes (padj < 0.1): 8,086

### Volcano Plot

Volcano plot highlighting significantly dysregulated genes between tumor and normal tissues.

## Tools

- R
- TCGAbiolinks
- DESeq2
- ggplot2
- EnhancedVolcano
- clusterProfiler

## Author

HASSINI NISRINE 
