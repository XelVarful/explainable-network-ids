# Explainable Machine Learning for Network Intrusion Detection

A comparative and experimental study of machine learning models
for detecting network attacks and explaining their predictions using SHAP.

## Research Objective

Evaluate the effectiveness of different machine learning models
for network intrusion detection and identify the network traffic
features that most strongly influence their predictions.

## Research Questions

- RQ1: Which machine learning model provides the best performance
  for network intrusion detection?
- RQ2: Which network traffic features have the greatest influence
  on attack detection?
- RQ3: How can SHAP help interpret model predictions and errors?

## Research Hypothesis

Tree-based models achieve better network intrusion detection
performance than a linear model, while SHAP identifies a limited
set of features that strongly influence attack detection.

The hypothesis will be evaluated using experimental results.

## Planned Models

- Logistic Regression
- Random Forest
- XGBoost
- Multilayer Perceptron (MLP)

## Dataset

The dataset will be selected and justified after the initial
literature review.

Candidates:
- CIC-IDS2017
- CSE-CIC-IDS2018
- UNSW-NB15

## Evaluation

Models will use the same data partitions and a consistent
evaluation protocol.

Planned measures:
- Accuracy
- Precision, Recall and F1-score
- Macro-F1 and per-class results
- ROC-AUC
- Confusion matrices
- Training time

SHAP will be used to examine global feature importance,
individual predictions and differences between models.

## Research Stages

- [ ] Review 35–40 scientific publications
- [ ] Select and analyze a dataset
- [ ] Prepare data and define the experimental protocol
- [ ] Analyze and select features
- [ ] Train and compare four models
- [ ] Explain predictions using SHAP
- [ ] Analyze errors and evaluate the hypothesis
- [ ] Complete the research paper

## Current Status

Initial literature review. No final experimental conclusions
have been established.

## Planned Deliverables

Research paper, literature review, dataset analysis,
reproducible Python code, experimental results and SHAP visualizations.
