# Analysis Workflow

## 1. Expression Assessment

First, hsa-miR-873-5p expression was assessed using the GEO dataset GSE103228 to compare expression between normal brain and glioblastoma samples.

## 2. Target Prediction Using miRDB

The miRDB database was used to identify higher-scoring candidate target genes for hsa-miR-873-5p. This resulted in 38 candidate genes.

## 3. Cross-Referencing Using TargetScan-Supported Predictions

The 38 candidate genes were cross-referenced with TargetScan-supported predictions accessed through miRCarta. This resulted in 17 overlapping candidate genes.

## 4. STRING and MCL Analysis

The 17 candidate genes were analysed using STRING to examine protein-protein interaction relationships. MCL clustering was also performed to explore potential clusters within the resulting network.

The initial STRING analysis showed 0 detected edges and no significant protein-protein interaction enrichment (PPI enrichment p = 1).

## 5. Functional Enrichment Analysis

g:Profiler was used to investigate functional enrichment among the 17 candidate genes. No significant enrichment was identified across the main functional categories examined.

## 6. Independent Expression Assessment

The 17 candidate genes were independently assessed using the GEO dataset GSE90886. Gene expression was compared between glioblastoma and normal samples, with multiple-testing correction applied to the resulting statistical tests.

No statistically significant differential expression was identified among the 17 candidate genes after multiple-testing correction.

## Overall Workflow

GSE103228 expression assessment → miRDB target prediction → TargetScan-supported cross-referencing through miRCarta → STRING analysis → MCL clustering → g:Profiler enrichment analysis → literature review → independent expression assessment using GSE90886.

## Reproducibility Notes

The analysis was conducted using publicly available bioinformatics databases and gene expression datasets.

- Dataset accession numbers: GSE103228 and GSE90886.
- Target prediction: miRDB.
- Target cross-referencing: TargetScan-supported predictions accessed through miRCarta.
- Protein–protein interaction analysis: STRING.
- Network clustering: MCL.
- Functional enrichment: g:Profiler.

The analysis workflow and principal findings are documented in this repository.

Exact database versions, access dates, software settings, and analysis parameters should be added where available to support independent reproduction of the workflow.

Computationally predicted targets should be considered candidate interactions and require experimental validation.
