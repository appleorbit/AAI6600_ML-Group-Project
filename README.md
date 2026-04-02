# AAI6600 ML Group Project — EDA Notebook (Wei Dong)

This repository contains a full-data EDA on the NSL-KDD dataset — all 125,973 training records included, without any filtering or subsetting.

## Notebook
`notebooks/01_eda_nsl_kdd.ipynb`

Exploratory Data Analysis on the NSL-KDD network intrusion detection dataset, including:
- Dataset overview and data quality checks
- Target label distribution (binary and multi-class)
- Feature type analysis (numerical vs categorical)
- Descriptive statistics and visualizations
- **Fine-grained attack type breakdown** (Section 11): maps all 22 individual attack types to the 5 standard families (Normal, DoS, Probe, R2L, U2R), revealing why R2L and U2R are nearly undetectable by standard classifiers

## Dataset
NSL-KDD — [Kaggle mirror](https://www.kaggle.com/datasets/hassan06/nslkdd)
