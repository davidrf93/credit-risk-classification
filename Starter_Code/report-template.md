# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Average of 93% precision, between low-risk loans and high-risk loans
  * Accuracy at 94%
  * Average of 95% recall between low-risk at 100% and high-risk at 89%

* Machine Learning Model 2:
  * Average at 93% precision, between low-risk at 100% and high-risk at 87%
  * Accuracy at 100%
  * Recall at 100%

## Summary

Fase positives were more predominant during model 2, but less likely to predict false negatives.
Model 2 had more true predictions, but neither model achieved 90% or more for precision.
Therefore, model 2 is prone to predict less false positives.
