---
title: Why dogs are dogs, and why Border Collies are Border Collies
---

# Why dogs are dogs, and why Border Collies are Border Collies

## A public-data framework for studying herding specialization

A long-standing question in canine biology is not only why dogs differ from wolves, but also why certain breeds—such as Border Collies—show such stable and recognizable behavioral identities. This project uses public Dog10K genomic and hippocampal single-cell resources to connect **population structure**, **benchmark and candidate loci**, and **hippocampal cell-type context** in the study of herding-related specialization.

**Core claim.** This project asks how Border Collie herding identity can be traced across population structure, candidate loci, and hippocampal cell-type context, while using **EPHB1** as a benchmark anchor rather than the endpoint of the story.

---

## Current progress at a glance

- A public-data framework has already been established using Dog10K genotype and hippocampus single-cell resources.
- A benchmark chr23 signal near **EPHB1** can be partially recovered in independent public data.
- Candidate neurodevelopment genes already show cell-type-biased expression across major hippocampal cell classes.

---

## Why this project matters

This is not intended as a simple replication of a published locus. Instead, the broader aim is to ask how a recognizable and stable breed-specific behavioral identity can be detected across multiple layers of evidence. Border Collies serve as a powerful entry point because their herding phenotype is unusually extreme, recognizable, and biologically interesting. In this framework, **EPHB1** functions as a sanity check and replication anchor, while the real interpretive space lies in the broader regional, regulatory, and pathway-level context beyond a single known signal.

---

## Main preliminary results

### 1. Population structure reveals local clustering of collie and herding-related samples

<img src="assets/figures/Fig1_PCA_panels_refined.png" width="900">

**Interpretation.**  
Collie samples form a compact local cluster within the main Dog10K cohort, while later principal components reveal additional herding-related structure beyond PC1–PC2 alone. These results suggest that breed-linked behavioral identity is genetically detectable in the cohort, even if it is not the dominant axis of variation in the full dataset.

---

### 2. chr23 shows localized differentiation near the published EPHB1 benchmark region

<img src="assets/figures/Fig3_chr23_local_refined.png" width="860">

**Interpretation.**  
A coarse herding vs non-herding contrast reveals localized differentiation on chr23 near the published **EPHB1** benchmark region. The strongest local signal is shifted downstream of the benchmark, supporting the analytical workflow while also indicating that the broader regional context remains worth exploring.

---

### 3. Candidate neurodevelopment genes show cell-type-biased expression in dog hippocampus

<img src="assets/figures/Fig4_singlecell_heatmap_refined.png" width="760">

**Interpretation.**  
Candidate genes do not show uniform background expression across major hippocampal cell classes. Instead, several show preferential enrichment in neuronal or glial contexts, providing an initial biological layer that links population-genetic candidates to neurodevelopmental and circuit-related mechanisms.

---

## Current status

### What has already been demonstrated
- A reproducible public-data workflow has been established.
- The pipeline already yields interpretable results at three levels: cohort structure, chr23 benchmark-region differentiation, and candidate-gene expression across major hippocampal cell classes.
- **EPHB1** can be used as a benchmark anchor while broader candidate mechanisms remain accessible.

### What is currently under exploration
- Re-ranking loci beyond **EPHB1** in herding-related contrasts
- Refining cohort definition to reduce structure-driven inflation
- Integrating pathway-level interpretation, especially along neurodevelopmental axes such as axon guidance, ephrin signaling, and synaptic organization

### Why this project is promising
This project is already producing biologically coherent preliminary results from public data. Because it combines a credible benchmark anchor with clear room for mechanistic expansion beyond a single reported locus, it is both technically feasible at the current stage and well positioned for deeper investigation.

---

## Supplementary figures

<details>
<summary><strong>Supplementary Figure 1. Exploratory autosome-wide differentiation scan</strong></summary>

<br>

<img src="assets/figures/Fig2_QuickGenomeScan_Herding_vs_NonHerding_refined_v2.png" width="920">

This exploratory scan should be interpreted cautiously because strong breed and population structure inflate genome-wide signal. It is included here as a differentiation screen rather than a calibrated genome-wide association result.

</details>

<br>

<details>
<summary><strong>Supplementary Figure 2. Dot-plot view of candidate-gene expression</strong></summary>

<br>

<img src="assets/figures/Fig4_singlecell_dotplot_refined_v9.png" width="860">

Dot color indicates scaled mean expression and dot size indicates the percentage of cells with detectable expression in each cell class. This view complements the heatmap by showing both expression intensity and prevalence.

</details>

---

## Public resources used

- Dog10K genotype PLINK dataset
- Dog10K sample metadata
- Dog hippocampus single-nucleus RNA-seq dataset

---

## Files

- **Figures**: `assets/figures/`
- **Preliminary results PDF**: `assets/docs/Preliminary_Results.pdf`
- **Analysis scripts**: `scripts/`

---

## Author

**Liya Zhang**

---

## Contact / repository navigation

- [Preliminary results PDF](assets/docs/Preliminary_Results.pdf)
- [Repository README](README.md)
