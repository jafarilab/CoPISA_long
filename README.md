# CoPISA_long

Analysis code associated with the manuscript:

**Residual Acute Myeloid Leukemia Cells Identifies Candidate Therapeutic Vulnerabilities via Chemical Proteomics**

*Preprint forthcoming on bioRxiv.*

## Overview

This repository contains the R code used for the analysis and visualization of chemical proteomics (CoPISA) and expression proteomics data from the study.

The main analysis workflow is provided in:

- `VenAza.Rmd` — R Markdown file containing the primary data analysis and visualization workflow.

## Requirements

All downstream analyses were performed in **R**.

The repository uses `renv` for R package and environment management. After cloning the repository and opening the R project, the package environment can be restored with:

```r
renv::restore()
```

## Data availability

The mass spectrometry proteomics data generated in this study have been deposited in the **ProteomeXchange Consortium** via the **PRIDE** partner repository under the dataset identifier:

**PXD084405**

DOI: **10.6019/PXD084405**

The deposited dataset includes the **mzML mass spectrometry files** and associated **MaxQuant output files**, including files such as `evidence.txt` and `msms.txt`, which can be downloaded from PRIDE and used as input for the downstream analyses provided in this repository.

ProteomeXchange dataset:

http://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=PXD084405

Source data are also provided with the manuscript. There are no restrictions on data availability.

## Code availability

The R code used for the downstream analyses in this study is publicly available in this repository:

https://github.com/jafarilab/CoPISA_long

## Citation

If you use the data or code from this repository, please cite the associated manuscript:

**Residual Acute Myeloid Leukemia Cells Identifies Candidate Therapeutic Vulnerabilities via Chemical Proteomics**

A complete citation and bioRxiv DOI will be added following preprint publication.