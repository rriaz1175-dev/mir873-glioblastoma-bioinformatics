# Integrative Bioinformatics Analysis of hsa-miR-873-5p in Glioblastoma
## Abstract
This independent bioinformatics project investigated the potential role of hsa-miR-873-5p in glioblastoma through an integrative computational approach. The analysis combined microRNA expression assessment, target prediction, database cross-referencing, protein–protein interaction analysis, functional enrichment, literature review, and independent gene expression assessment. The study identified a set of candidate target genes; however, subsequent analyses did not demonstrate significant functional enrichment or independent differential expression after multiple-testing correction. These findings highlight the exploratory nature of computational target prediction and the need for experimental validation.
## Overview

This repository contains the materials for an independent computational research project investigating hsa-miR-873-5p and its predicted target genes in glioblastoma.

The study uses an integrative bioinformatics approach combining microRNA expression analysis, target prediction, cross-referencing of prediction databases, protein-protein interaction analysis, functional enrichment, literature review, and independent gene expression assessment.

## Research Question

What potential target genes and biological relationships can be identified for hsa-miR-873-5p in glioblastoma using an integrative computational approach?

## Datasets

- **GSE103228** — Public microRNA expression profiling dataset comprising 5 glioblastoma and 5 normal brain samples. Generated using the Exiqon miRCURY LNA microRNA Array (GPL18058). Used for the initial expression assessment of hsa-miR-873-5p. NCBI GEO: GSE103228
- **GSE90886** — Public gene expression profiling dataset comprising 9 glioblastoma and 9 normal brain samples. Generated using the Affymetrix Human Gene Expression Array (GPL15207). Used for independent expression assessment of the 17 candidate target genes. NCBI GEO: GSE90886

## Analysis Pipeline

The analysis followed an integrative computational workflow:

1. MicroRNA expression assessment: Evaluated hsa-miR-873-5p expression in glioblastoma and normal brain samples using GEO dataset GSE103228.

2. Target prediction: Retrieved candidate target genes using miRDB, identifying 38 higher-scoring candidates.

3. Candidate refinement: Cross-referenced predicted targets with TargetScan-supported predictions through miRCarta, resulting in 17 overlapping candidate genes.

4. Protein–protein interaction analysis: Investigated potential interactions among the 17 candidate genes using STRING. The analysis detected no interaction edges and no significant PPI enrichment (p = 1).

5. Network clustering: Explored potential network clusters using the MCL clustering approach.

6. Functional enrichment: Assessed functional enrichment using g:Profiler. No significant enrichment was identified across the main functional categories.

7. Literature review: Reviewed available literature to examine existing evidence related to the candidate genes and their potential biological relevance.

8. Independent expression assessment: Evaluated the 17 candidate genes using the independent GEO dataset GSE90886. No statistically significant differential expression was identified after multiple-testing correction.

## Key Findings

- MicroRNA expression: hsa-miR-873-5p showed markedly lower expression in the glioblastoma group compared with normal brain samples in GSE103228.

- Target prediction: miRDB identified 38 higher-scoring candidate target genes.

- Candidate refinement: Cross-referencing with TargetScan-supported predictions through miRCarta narrowed the candidate set to 17 overlapping genes.

- Protein–protein interaction analysis: STRING detected no interaction edges among the original 17 candidate genes, with no significant PPI enrichment (p = 1).

- Functional enrichment: g:Profiler analysis did not identify robust statistically significant enrichment across the main functional categories.

- Independent expression assessment: Analysis of GSE90886 did not identify statistically significant differential expression among the 17 candidate genes after multiple-testing correction.

## Important Note

The candidate genes identified in this project are computationally predicted targets and should not be considered experimentally confirmed hsa-miR-873-5p targets in glioblastoma.

The study is hypothesis-generating, and experimental studies are required to establish direct regulatory relationships and biological significance.

## Project Status

Completed independent research report.

## Author

Nimra
