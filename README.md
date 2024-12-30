# Codes-to-train-and-test-ML-models-for-scRNA-analysis
# R Codes: 

This GitHub repository contains the R scripts used to generate all analyses for the paper.

In this work, This study evaluates the performance of eight selected machine learning (ML) models for cell annotation in single-cell RNA sequencing (scRNA-seq) datasets, focusing on their ability to generalize across datasets with varying cell populations and transcriptome isolation techniques. 

## ML models selected for this study:

In this study, we systematically assess the performance of eight machine learning models (Support Vector Machine (SVM), Logistic Regression, Decision Tree, Random Forest, Elastic Net Regularization, Gradient Boosting (XGBoost), k-Nearest Neighbors (k-NN), and Naive Bayes), in learning and transferring cell labels. By comparing these models, we aim to demonstrate their utility in advancing scRNA-seq analysis and provide researchers with a comprehensive understanding of these computational tools for robust and accurate cell classification.
 
### Installation 
Step 1: Install the Required R packages and load the libraries

Step 2: Download and process the required Datasets
The data consist of 3k PBMCs from a Healthy Donor and are freely available from 10x Genomics
 https://cf.10xgenomics.com/samples/cell-exp/1.1.0/pbmc3k/pbmc3k_filtered_gene_bc_matrices.tar.gz -o data/pbmc3k_filtered_gene_bc_matrices.tar.gz

or PBMC3k [HERE](https://support.10xgenomics.com/single-cell-gene-expression/datasets/1.1.0/pbmc3k)

The tutorial to process the PBMC10k is available [HERE](https://cellgeni.github.io/notebooks/html/new-10kPBMC-Seurat.html)

the PBMC10K rw files are available [HERE](http://cf.10xgenomics.com/samples/cell-exp/3.0.0/pbmc_10k_v3/pbmc_10k_v3_filtered_feature_bc_matrix.tar.gz)

The Heart datasets were genearted by Selewa, A., Dohn, R., Eckart, H. et al. Systematic Comparison of High-throughput Single-Cell and Single-Nucleus Transcriptomes during Cardiomyocyte Differentiation. Sci Rep 10, 1535 (2020). https://doi.org/10.1038/s41598-020-58327-6
 
All data can be found on [GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE129096)

Step 3: Download and run the codes in the "codes" repository

## Citation
If you use this content, please cite:
```
Tortelote GG., Benchmarking Machine Learning Models for Cell Type Annotation in Single-Cell vs Single-Nucleus RNA-Seq Data 
```
