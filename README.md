# Single Cell Analysis Tutorial Capsule

This repository serves as the starting point for creating a GitHub-integrated Capsule for preprocessing and exploratory analysis of single cell data from 2700 Peripheral Blood Mononuclear Cells.  

### Runtime environment

Choose the **Python and R (Jupyterlab/RStudio) (python3.10.12-R4.2.3-IRkernel-ubuntu22.04)** starter environment and add the following packages to the mamba package manager:

anndata==0.9.2

leidenalg==0.10.1

matplotlib==3.7.2

pandas==2.0.3

scanpy==1.9.5

### Required Data

Running this notebook requires a data asset which can be created from the following S3 storage:

**S3 bucket:** codeocean-public-data

**Path:** example_datasets/single-cell-tutorial/pbmc3k/filtered_gene_bc_matrices/

**Data Asset Metadata**

**Title:** Single Cell Tutorial - 3k PBMCs

**Folder name:** filtered_gene_bc_matrices

**Description:** Peripheral Blood Mononuclear Cells (PBMC) dataset freely available from 10X Genomics. There are 2,700 single cells that were sequenced on the Illumina NextSeq 500. The raw data can be found at https://cf.10xgenomics.com/samples/cell/pbmc3k/pbmc3k_filtered_gene_bc_matrices.tar.gz


*Note: do **not** import this repository directly. Instead, create a new repo from this template.*

Notebook based on the original [Scanpy Tutorial](https://scanpy-tutorials.readthedocs.io/en/latest/pbmc3k.html). 
