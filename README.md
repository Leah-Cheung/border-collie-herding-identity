# Why dogs are dogs, and why Border Collies are Border Collies

A public-data framework for studying the genetic architecture of herding specialization.

This project asks a broader question than simple locus replication: how stable breed-specific behavioral identity—especially the extreme herding specialization of Border Collies—can be traced across population structure, candidate loci, and hippocampal cell-type context. Publicly available Dog10K genomic and hippocampal single-cell resources are used here to build a proof-of-concept workflow linking cohort structure, locus-level differentiation, and neurobiological interpretation.

**Current position of the project**
- A public-data pipeline has been established using Dog10K genotype and hippocampus single-cell resources.
- A benchmark chr23 signal near **EPHB1** can be partially recovered in independent public data.
- Candidate neurodevelopment genes already show cell-type-biased expression across major hippocampal cell classes.

## Project page
The GitHub Pages version of this project is available here:

**[Open the project page](./index.md)**

Once GitHub Pages is enabled, this link can be replaced with the full site URL.

## Central question
A long-standing question in canine biology is not only why dogs differ from wolves, but also why certain breeds—such as Border Collies—show such stable and recognizable behavioral identities. This project uses public canine genomic and transcriptomic resources to ask how that identity can be detected across:
1. population structure,
2. benchmark and candidate loci,
3. hippocampal cell-type expression context.

In this framework, **EPHB1** is treated as a **benchmark anchor**, not as the endpoint of the story.

## Main preliminary results
### 1. Population structure
PCA of the Dog10K cohort shows that collie samples form a compact local cluster within the broader cohort, while later principal components reveal additional herding-related structure not fully captured by PC1–PC2 alone.

### 2. chr23 benchmark-region follow-up
A coarse herding vs non-herding contrast reveals localized differentiation on chr23 near the published **EPHB1** benchmark region. The strongest local signal is shifted downstream of the benchmark, suggesting that the broader regional context remains worth exploring.

### 3. Cell-type context in dog hippocampus
Candidate neurodevelopment and axon-guidance genes show non-uniform, cell-type-biased expression across major dog hippocampal cell classes, providing an initial biological interpretation layer beyond a single known locus.

## Main figures
### Figure 1. Population structure
![Figure 1](assets/figures/Fig1_PCA_panels.png)

### Figure 2. chr23 localized differentiation
![Figure 2](assets/figures/Fig3_chr23_local.png)

### Figure 3. Cell-type-biased expression
![Figure 3](assets/figures/Fig4_singlecell_heatmap.png)

## Supplementary figures
### Supplementary Figure 1. Exploratory autosome-wide differentiation scan
![Supplementary Figure 1](assets/figures/Fig2_QuickGenomeScan_Herding_vs_NonHerding_v2.png)

### Supplementary Figure 2. Dot-plot view of candidate-gene expression
![Supplementary Figure 2](assets/figures/Fig4_singlecell_dotplot_v9.png)

## Public resources used
- Dog10K genotype PLINK dataset
- Dog10K sample metadata
- Dog hippocampus single-nucleus RNA-seq data

## Repository contents
- `assets/figures/`: final figure outputs used for the project page and preliminary report
- `assets/docs/`: PDF version of the preliminary results brief
- `scripts/`: plotting and analysis scripts used to generate the current figures

## Current interpretation
The project is not framed as a simple replication exercise. Instead, it asks how a recognizable herding identity can be detected across multiple analytical layers. Current results support the feasibility of this framework and motivate deeper investigation beyond **EPHB1**, especially toward pathway-level interpretation involving neurodevelopment, axon guidance, ephrin signaling, and synaptic organization.

## Status
This is an active preliminary-results repository. The current version focuses on:
- establishing analytical feasibility,
- defining a benchmark replication anchor,
- identifying candidate directions for deeper follow-up.

## Author
Liya Zhang

## License
For academic display and research communication. Add a formal license here if needed.
