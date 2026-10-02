# Integrative Bioinformatics Analysis of hsa-miR-873-5p in Glioblastoma

## Overview

This repository contains the materials for an independent computational research project investigating hsa-miR-873-5p and its predicted target genes in glioblastoma.

The study uses an integrative bioinformatics approach combining microRNA expression analysis, target prediction, cross-referencing of prediction databases, protein-protein interaction analysis, functional enrichment, literature review, and independent gene expression assessment.

## Research Question

What potential target genes and biological relationships can be identified for hsa-miR-873-5p in glioblastoma using an integrative computational approach?

## Datasets

- **GSE103228** — used to assess hsa-miR-873-5p expression in normal brain and glioblastoma samples.
- **GSE90886** — used for independent expression assessment of the candidate target genes.

## Analysis Pipeline

1. hsa-miR-873-5p expression analysis
2. Target prediction using miRDB
3. Cross-referencing with TargetScan-supported predictions through miRCarta
4. STRING protein-protein interaction analysis
5. MCL clustering
6. Functional enrichment analysis using g:Profiler
7. Literature review
8. Independent expression assessment using GSE90886

## Key Findings

- hsa-miR-873-5p showed markedly lower expression in the glioblastoma group in GSE103228.
- 38 higher-scoring candidate genes were obtained from miRDB.
- Cross-referencing produced 17 overlapping candidate genes.
- The original 17-gene set showed no significant protein-protein interaction enrichment in STRING.
- No robust functional enrichment was observed for the original candidate set.
- Independent expression assessment in GSE90886 did not identify statistically significant differential expression after multiple-testing correction.

## Important Note

The candidate genes identified in this project are computationally predicted targets and should not be considered experimentally confirmed hsa-miR-873-5p targets in glioblastoma.

The study is hypothesis-generating, and experimental studies are required to establish direct regulatory relationships and biological significance.

## Project Status

Completed independent research report.

## Author

Nimra
