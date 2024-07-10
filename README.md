## General Information

This repository contains the notebooks used during the Master's Thesis (TFM) titled *Data-Driven Insights into Ischaemic Heart Disease: Exploring Individual, Environmental and Social Influences through Machine Learning* of the Master's in Data Science (UC-UIMP) for the 2023/2024 academic year.

## Files
The repository contains the following files:

- **README.md**: This text file. Contains information about the distribution of contents.
- **NB1_datacuration**: Notebook (Python code) used to preprocess the data and prepare it for subsequent analysis.
- **NB2_univariateanalysis**: Notebook (Python code) that performs univariate analysis to see the distribution of variables.
- **NB3_bivariateanalysis**: Notebook (Python code) that includes a Cramer's V matrix to analyze the correlations between different variables.
- **NB4_BNanalysis**: Notebook (R code) with the analysis of four Bayesian networks. Includes the graphs of the Bayesian networks obtained using the hc algorithm, uses bootstrap to improve robustness, analyzes the strength of the arcs, and includes graphs with probability distributions and queries to the networks.
- **NB5_gini**: Notebook (R code) with the analysis of variable importance using random forests for the three variables: CVdeath, AMI, and HEMORRHAGE.
- **NB6_clasificationmodels**: A directory with notebooks (R code) used for appendix C, utilizing Bayesian networks, random forests, SVM, KNN, and Naive Bayes.
