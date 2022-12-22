# Human Activity Classification and Explainability

## Authors

[Yana Muliarska](https://github.com/muliarska), [Oleksandra Stasiuk](https://github.com/oleksadobush)

UofT Ph.D. student mentor: Sujay Nagaraj

## Problem

Two central problems that we aim to solve in this work are:
1. Classification problem on the Human Activity Data
2. Explainability of the results

## Data

The Human Activity Recognition Using Smartphones (HAR) dataset from UC Irvine Machine Learning Repository (UCI).

## Implementation

We tried many different models (Linear, Tree-Based, and Neural Networks) and measured their performance on the dataset.

For best-performing models, we used two different interpretability methods:
* Model coefficients
* Shapley Values

To validate our results, we experimented with dropping the most important features and re-evaluating the model performance.

The working code for Linear and Tree-Based models are available in the [human_activity_classification_ML_models.ipynb](https://github.com/muliarska/health-state-detection-from-human-activity/blob/main/human_activity_classification_ML_models.ipynb) file. There were also some trials to perform interpretability for LSTM; you can see the code in the corresponding notebooks. 
