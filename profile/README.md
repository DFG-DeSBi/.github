<div align="center">

# [DeSBi](https://desbi.de/)

### Deep Learning × Statistics for Biomedical Data

**DFG Research Unit KI-FOR 5363 · Project 459422098**

[![DFG Research Unit](https://img.shields.io/badge/DFG-KI--FOR%205363-555555?style=flat-square)](https://gepris.dfg.de/gepris/projekt/459422098?language=en)
[![Release standard](https://img.shields.io/badge/releases-curated%20%26%20citable-2f855a?style=flat-square)](https://github.com/dfg-desbi/software-catalogue/blob/main/RELEASE_POLICY.md)
[![Software catalogue](https://img.shields.io/badge/software-catalogue-1f6f8b?style=flat-square)](https://github.com/dfg-desbi/software-catalogue)
[![DeSBi website](https://img.shields.io/badge/desbi.de-website-7a4eab?style=flat-square)](https://desbi.de/)
[![Publications](https://img.shields.io/badge/research-publications-a44a3f?style=flat-square)](https://desbi.de/publications/)

</div>

DeSBi develops **statistically grounded artificial intelligence for biomedical data**. We combine the modelling flexibility of deep learning with statistical inference, uncertainty quantification, explanation, confounder-aware and causal analysis, and structured modelling—so that learned representations can support reliable scientific conclusions rather than prediction alone.

```mermaid
flowchart TB
    A["Biomedical data<br/>images · sequences · time series · multimodal cohorts"] --> B["Deep representations"]
    B --> C1["Statistical testing<br/>& inference"]
    B --> C2["Explanations<br/>& concepts"]
    B --> C3["Uncertainty<br/>& failure detection"]
    B --> C4["Confounding<br/>& causal reasoning"]
    B --> C5["Hybrid statistical–deep<br/>models"]
    C1 --> D["Reliable, interpretable<br/>biomedical evidence"]
    C2 --> D
    C3 --> D
    C4 --> D
    C5 --> D
```
## From biomedical questions to reusable methods

DeSBi methods are co-developed and evaluated across **neuroimaging and imaging genetics**, **histopathology and clinical imaging**, **functional genomics and biological sequence models**, and **longitudinal and multimodal biomedical data**. The application domains expose methodological failure modes; the resulting methods return to the applications as reproducible analysis pipelines and validated scientific tools.


## Curated DeSBi releases (v1.0.0, desbi-2026.09.1)

All 10 repositories with verified v1.0.0 releases:

| | | |
|---|---|---|
| [![DNCIT](https://img.shields.io/badge/DNCIT-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/DNCIT/releases/tag/v1.0.0) | [![transferGWAS](https://img.shields.io/badge/transferGWAS-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/transferGWAS/releases/tag/v1.0.0) | [![DualXDA](https://img.shields.io/badge/DualXDA-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/DualXDA/releases/tag/v1.0.0) |
| [![cocodeel](https://img.shields.io/badge/cocodeel-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/cocodeel/releases/tag/v1.0.0) | [![Pathology-FMB](https://img.shields.io/badge/Pathology--FMB-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/Pathology-Foundation-Model-Benchmark/releases/tag/v1.0.0) | [![MFD](https://img.shields.io/badge/MFD-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/MFD/releases/tag/v1.0.0) |
| [![semanticlens](https://img.shields.io/badge/semanticlens-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/semanticlens/releases/tag/v1.0.0) | [![rrclarc](https://img.shields.io/badge/rrclarc-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/rrclarc/releases/tag/v1.0.0) | [![udbench-benchmark](https://img.shields.io/badge/udbench--benchmark-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/udbench-benchmark/releases/tag/v1.0.0) |
| [![dnn-shapes](https://img.shields.io/badge/dnn--shapes-v1.0.0-2f855a?style=flat-square)](https://github.com/dfg-desbi/dnn-shapes/releases/tag/v1.0.0) | | |

Each release includes provenance-verified snapshots, citation metadata (CITATION.cff, DESBI_RELEASE.md), and full upstream history. See **[what a DeSBi release means](#what-desbi-release-means)** for details.


## Flagship software

Key methodological contributions spanning statistical inference to mechanistic interpretability:

| | | |
|---|---|---|
| <a href="https://github.com/dfg-desbi/DNCIT"><strong>DNCIT</strong></a><br/>Conditional-independence testing with learned representations.<br/><sub>Inference · R · v1.0.0 ✓</sub> | <a href="https://github.com/dfg-desbi/transferGWAS"><strong>transferGWAS</strong></a><br/>Genome-wide association analysis on whole medical images.<br/><sub>Imaging genetics · Python · v1.0.0 ✓</sub> | <a href="https://github.com/dfg-desbi/semanticlens"><strong>SemanticLens</strong></a><br/>Semantic interpretation and validation of components in large vision models.<br/><sub>Mechanistic XAI · Python · v1.0.0 ✓</sub> |
| <a href="https://github.com/dfg-desbi/MFD"><strong>MFD</strong></a><br/>Metadata-guided feature disentanglement for functional genomics.<br/><sub>Genomics · Python/Snakemake · v1.0.0 ✓</sub> | <a href="https://github.com/dfg-desbi/quanda"><strong>quanda</strong></a><br/>Quantitative evaluation of training-data attribution methods.<br/><sub>Evaluation · Python · candidate ⏳</sub> | <a href="https://github.com/dfg-desbi/PURE"><strong>PURE</strong></a><br/>Turning polysemantic neurons into pure features by identifying relevant circuits.<br/><sub>Mechanistic XAI · Python · candidate ⏳</sub> |
| <a href="https://github.com/dfg-desbi/DualXDA"><strong>DualXDA</strong></a><br/>Sparse, efficient and feature-explainable data attribution.<br/><sub>Data attribution · Python · v1.0.0 ✓</sub> | <a href="https://github.com/dfg-desbi/pcx"><strong>pcx</strong></a><br/>Prototypical concept-based explanations for model validation.<br/><sub>Mechanistic XAI · Python · candidate ⏳</sub> | <a href="https://github.com/dfg-desbi/aggrigator"><strong>aggrigator</strong></a><br/>Spatially-aware aggregation of segmentation uncertainty.<br/><sub>Uncertainty · Python · candidate ⏳</sub> |

**Status labels:** v1.0.0 ✓ = curated release · candidate ⏳ = undergoing review


## Release candidates

These repositories are undergoing independent review and will receive curated DeSBi releases:

- **[quanda](https://github.com/dfg-desbi/quanda)** – Quantitative evaluation of training-data attribution methods
- **[PURE](https://github.com/dfg-desbi/PURE)** – Turning polysemantic neurons into pure features
- **[pcx](https://github.com/dfg-desbi/pcx)** – Prototypical concept-based explanations
- **[aggrigator](https://github.com/dfg-desbi/aggrigator)** – Spatially-aware aggregation of segmentation uncertainty
  

## Software catalogue

Additional research software is documented in the **[complete software catalogue](https://github.com/dfg-desbi/software-catalogue)**:

- **[zennit](https://github.com/dfg-desbi/zennit)** – Layer-wise relevance propagation for PyTorch
- **[LRP-eXplains-Transformers](https://github.com/dfg-desbi/LRP-eXplains-Transformers)** – Explaining transformer models
- **[toybrains](https://github.com/dfg-desbi/toybrains)** – Causal synthetic neuroimaging benchmark
- **[arctique](https://github.com/dfg-desbi/arctique)** – Controllable synthetic histopathology
- **[DeepRepViz](https://github.com/dfg-desbi/DeepRepViz)** – Diagnostics for confounder encoding
  

## What "DeSBi release" means

An official release is more than a fork. Each curated DeSBi release must:

- preserve the upstream authors, commit history, licence and canonical development link;
- identify the DeSBi projects, publication, funding and scientific contribution;
- provide machine-readable citation metadata and a versioned release note;

The detailed requirements are defined in the **[release policy](https://github.com/dfg-desbi/software-catalogue/blob/main/RELEASE_POLICY.md)** and **[repository checklist](https://github.com/dfg-desbi/software-catalogue/blob/main/REPO_CHECKLIST.md)**.


## Use, cite and contribute

Use the licence and citation instructions of the individual repository. Unless explicitly stated otherwise, the original repository remains the canonical development home and the DeSBi repository provides a provenance-preserving, independently-verified research release.

New or previously unlisted software can be proposed through the **[release-candidate form](https://github.com/dfg-desbi/software-catalogue/issues/new?template=release-candidate.yml)**.

---

<div align="center">
<sub>DeSBi is funded by the German Research Foundation (DFG) under project 459422098, KI-FOR 5363. Repository licences and copyright remain those of the respective upstream projects.</sub>
</div>
