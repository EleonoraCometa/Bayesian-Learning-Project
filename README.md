# Bayesian Regression for Industrial Production Index Estimation

Bayesian linear regression analysis to model the U.S. Industrial Production Index 
(INDPRO) using 11 macroeconomic indicators as predictors.

## Overview

The project compares two Bayesian priors, g-prior and JZS-prior, for estimating 
the relationship between INDPRO and a set of macroeconomic indexes. Model refinement 
is performed via BIC-based variable selection, and robustness is assessed by analyzing 
the impact of different hyperparameter (α) values on predictive performance.

## Methods

- Bayesian linear regression with g-prior and JZS-prior
- Variable selection via Bayesian Information Criterion (BIC)
- Posterior inference and credible interval analysis
- Robustness analysis across multiple α values
- Model evaluation via residual analysis and MSE

## Key Results

- BIC selected 5 predictors out of 11 (including VIXCLS, PAYEMS, TOTALSA)
- Reduced model maintained predictive accuracy comparable to the full model
- JZS-prior proved more robust to hyperparameter choice than g-prior
- Best MSE: g-prior with α=0.1 (MSE=0.235), JZS-prior with α=0.1 (MSE=0.305)

## Authors

Eleonora Cometa, Nicola De March  
*Bayesian Learning — Politecnico di Milano, 2025*
