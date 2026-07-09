# Nomogram for Predicting Metastases in Breast Cancer

This repository contains the statistical analysis and R code developed for my Bachelor’s Thesis in *Statistics for Technologies and Sciences* at the University of Padua (A.A. 2024/2025).

## Overview
The project focuses on building the statistical foundations for a **clinical nomogram** to estimate the probability of non-sentinel lymph node (non-SLN) metastases in breast cancer patients.

## Methodology
The analysis was conducted in R and includes:
- **Exploratory Data Analysis (EDA):** Univariate and bivariate analysis using non-parametric tests (Kruskal-Wallis, Mann-Whitney) and Chi-squared tests.
- **Statistical Modeling:** Implementation of a **Generalized Linear Model (GLM)** with a Binomial distribution and *logit* link function, utilizing *forward* selection for variable optimization.

## Key Results
- The final model achieved an **AUC of 0.77** (validated via ROC curve).
- Identification of primary clinicopathological risk factors associated with non-SLN positivity.

## Repository Contents
* `tesi.Rmd`: The complete R Markdown script (data cleaning, EDA, modeling, diagnostics).
* `Perin_Leonardo.pdf`: The full thesis manuscript.
* `Presentazione_Perin_Leonardo.pdf`: Presentation slides from the thesis defense.

## Author
**Leonardo Perin** *Bachelor’s Graduate in Statistics for Technologies and Sciences, University of Padua*
