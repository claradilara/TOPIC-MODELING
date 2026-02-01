# Supervised Topic Modeling of U.S. State Department Reports

## Problem
Unsupervised topic models often produce topics that are
statistically coherent but poorly aligned with known policy domains.

This project applies supervised topic modeling to improve
semantic alignment and interpretability.

## Dataset
- Source: U.S. Department of State Country Reports
- Time span: 2013–2015
- Total text chunks: ~26,000
- Binary label: EU vs Non-EU references

## Methodology
1. Text preprocessing and chunking
2. Baseline unsupervised topic modeling
3. Supervised BERTopic with label guidance
4. Hyperparameter optimization using coherence metrics

## Results
- Optimal number of topics: 17
- Supervised topics showed higher semantic alignment
- Clear separation between EU-related policy themes

## Key Insight
Supervision improves interpretability without sacrificing
topic coherence, making topic models more suitable for
policy-oriented text analysis.

## Tech Stack
Python, BERTopic, scikit-learn, pandas, NumPy, matplotlib

## Reproducibility
pip install -r requirements.txt
