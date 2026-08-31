<div align="center">

# [DeSBi](https://desbi.de/)

### Deep Learning × Statistics for Biomedical Data

**DFG Research Unit KI-FOR 5363 · Project 459422098**

[![DFG Research Unit](https://img.shields.io/badge/DFG-KI--FOR%205363-555555?style=flat-square)](https://gepris.dfg.de/gepris/projekt/459422098?language=en)
[![Software catalogue](https://img.shields.io/badge/software-catalogue-1f6f8b?style=flat-square)](https://github.com/dfg-desbi/software-catalogue)
[![Release standard](https://img.shields.io/badge/releases-curated%20%26%20citable-2f855a?style=flat-square)](https://github.com/dfg-desbi/software-catalogue/blob/main/RELEASE_POLICY.md)
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

## Flagship software

<table>
<tr>
<td width="33%"><a href="https://github.com/dfg-desbi/DNCIT"><strong>DNCIT</strong></a><br/>Conditional-independence testing with learned representations.<br/><sub>Inference · R</sub></td>
<td width="33%"><a href="https://github.com/dfg-desbi/transferGWAS"><strong>transferGWAS</strong></a><br/>Genome-wide association analysis on whole medical images.<br/><sub>Imaging genetics · Python</sub></td>
<td width="33%"><a href="https://github.com/dfg-desbi/quanda"><strong>quanda</strong></a><br/>Quantitative evaluation of training-data attribution methods.<br/><sub>Data attribution · Python</sub></td>
</tr>
<tr>
<td width="33%"><a href="https://github.com/dfg-desbi/arctique"><strong>Arctique</strong></a><br/>Controllable synthetic histopathology for uncertainty benchmarking.<br/><sub>Uncertainty · Python/Blender</sub></td>
<td width="33%"><a href="https://github.com/dfg-desbi/semanticlens"><strong>SemanticLens</strong></a><br/>Semantic interpretation and validation of components in large vision models.<br/><sub>Mechanistic XAI · Python</sub></td>
<td width="33%"><a href="https://github.com/dfg-desbi/MFD"><strong>MFD</strong></a><br/>Metadata-guided feature disentanglement for functional genomics.<br/><sub>Genomics · Python/Snakemake</sub></td>
</tr>
<tr>
<td width="33%"><a href="https://github.com/dfg-desbi/DeepRepViz"><strong>DeepRepViz</strong></a><br/>Diagnostics for confounder encoding in deep representations.<br/><sub>Confounding · Python</sub></td>
<td width="33%"><a href="https://github.com/dfg-desbi/toybrains"><strong>Toybrains</strong></a><br/>Causal synthetic neuroimaging benchmark with known ground truth.<br/><sub>Simulation · Python</sub></td>
<td width="33%"><a href="https://github.com/dfg-desbi/DualXDA"><strong>DualXDA</strong></a><br/>Sparse, efficient and feature-explainable data attribution.<br/><sub>Data attribution · Python</sub></td>
</tr>
</table>

**[Browse the complete software catalogue →](https://github.com/dfg-desbi/software-catalogue)**

## From biomedical questions to reusable methods

DeSBi methods are co-developed and evaluated across **neuroimaging and imaging genetics**, **histopathology and clinical imaging**, **functional genomics and biological sequence models**, and **longitudinal and multimodal biomedical data**. The application domains expose methodological failure modes; the resulting methods return to the applications as reproducible analysis pipelines and validated scientific tools.

## What “DeSBi release” means

An official release is more than a fork. Each curated DeSBi release must:

- preserve the upstream authors, commit history, licence and canonical development link;
- identify the DeSBi projects, publication, funding and scientific contribution;
- provide an installable environment, a minimal reproducible example and automated checks;
- carry machine-readable citation metadata and a versioned release note;
- be archived with a persistent identifier where appropriate.

The detailed requirements are defined in the **[release policy](https://github.com/dfg-desbi/software-catalogue/blob/main/RELEASE_POLICY.md)** and **[repository checklist](https://github.com/dfg-desbi/software-catalogue/blob/main/REPO_CHECKLIST.md)**.

## Use, cite and contribute

Use the licence and citation instructions of the individual repository. Unless explicitly stated otherwise, the original repository remains the canonical development home and the DeSBi repository provides a provenance-preserving, quality-checked research release.

New or previously unlisted software can be proposed through the **[release-candidate form](https://github.com/dfg-desbi/software-catalogue/issues/new?template=release-candidate.yml)**.

---

<div align="center">
<sub>DeSBi is funded by the German Research Foundation (DFG) under project 459422098, KI-FOR 5363. Repository licences and copyright remain those of the respective upstream projects.</sub>
</div>
