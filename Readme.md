# Greenwashing Wordplay AI Prediction Pipeline

## Overview
This repository contains the code for a proof-of-concept AI model 
that predicts consumer purchase behavior under misleading brand naming 
(e.g., "Real 100% Juice" with only 10% juice content).

## Data
- `A.csv`: Survey responses (deceptive-first condition, n=9)
- `B.csv`: Survey responses (transparent-first condition, n=11)

## Pipeline
1. Survey data cleaning and psychographic scoring
2. Pilot regression to estimate demographic baselines
3. Synthetic population generation (n=10,000) with injected wordplay effect
4. Logistic regression classifier training
5. Segment-wise purchase-rate prediction

## Requirements
- Python 3.10+
- pandas, numpy, scikit-learn, matplotlib

## Citation
[Your Name] (2025). Greenwashing wordplay prediction pipeline. 
DOI: 10.5281/zenodo.XXXXXXX

## License
MIT