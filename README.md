# Differential Expression Analysis on Optical Pooled Screens (Feldman et al., 2019)

An end-to-end bulk RNA-Seq pipeline evaluating temporal transcriptomic responses ($1\,\text{h}$ vs. $4\,\text{h}$) in **MED12-KO** and **MED24-KO** HeLa cell lines under cytokine stimulation ($\text{IL-1}\beta$ / $\text{TNF}-\alpha$).

This repository contains the full computational workflow developed as part of a university course project, recreating and extending the differential expression analysis framework from the dataset published by **Feldman et al. (2019)** (*Optical Pooled Screens in Human Cells*).

---

## Biological Background & Objective

- **Biological Context:** The Mediator complex subunits **MED12** and **MED24** act as negative regulators of NF-$\kappa\text{B}$ nuclear translocation dynamics, causing prolonged retention of the p65 subunit in the nucleus at timepoints $> 2\,\text{hours}$.
- **Primary Objective:** Quantify transcriptomic alterations between $1\,\text{hour}$ and $4\,\text{hour}$ post-stimulation timepoints to isolate high-confidence consensus Differentially Expressed Genes (DEGs) and perturbed downstream inflammatory pathways.

---

## Repository Structure

```text
.
├── Dataset.rds                   # Processed SummarizedExperiment dataset (GEO: GSE132704)
├── Differential_Expression.Rmd   # Complete RMarkdown analytical pipeline
├── report.pdf                    # Compiled final technical report
└── README.md                     # Project documentation
```
