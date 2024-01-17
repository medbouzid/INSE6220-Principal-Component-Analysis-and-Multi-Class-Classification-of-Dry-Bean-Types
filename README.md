# INSE 6220: Advanced Statistical Approaches to Quality Prject
**Project Name:** Principal Component Analysis and Multi-Class Classification of Dry Bean Types
**Course:** INSE 6220: Advanced Statistical Approaches to Quality Prject

## Bean Type Classification using Machine Learning and PCA
Dry beans, as the most produced legume crops globally, play a vital role in various cultures' culinary products. Managing their genetic diversity is crucial for marketing, production, and smart agricultural practices. This project analyzes a dataset of 13,000 dry bean samples, employing Principal Component Analysis (PCA) and three Machine Learning (ML) algorithms (LightGBM, Random Forest, Gradient Boosting Classifier) for automatic classification.

## Highlights:
**PCA Dimensionality Reduction**: Applied to achieve uncorrelated features with maximum information.
**ML Algorithms**: Utilized LightGBM, Random Forest, and Gradient Boosting for classification.
**Metrics**: Evaluated using F1-Score, Confusion Matrix, and ROC.
**Results**: LightGBM demonstrated superior capability in distinguishing bean types.
## Motivation:
Dry beans, being essential in global agriculture, face challenges due to climate changes. Identifying seed characteristics through classification aids in enhancing plant resistance and market competitiveness.

## Approach:
**PCA for Dimensionality Reduction**: Reduced feature space from 16 to 2 dimensions, preserving over 80% of the variance.
**Classification Algorithms**: Applied ML algorithms on the original, transformed, and two-dimensional datasets.
**Evaluation Metrics**: F1-Score, Confusion Matrix, and ROC used to assess and compare model performance.

## Dataset:
Multivariate dataset containing 13k samples of dry beans.
Collected using computer vision to extract bean shape features from images.
7 classes, including "Dermason" and "Bombay," with 16 features per sample.
## Results:

**Original Dataset:**

LightGBM: F1-Score 0.932
Random Forest: F1-Score 0.908
Gradient Boosting: F1-Score 0.931

**Transformed Dataset (PCA):**

LightGBM: F1-Score 0.932
Random Forest: F1-Score 0.92
Gradient Boosting: F1-Score 0.931

**Two-Dimensional Dataset (PCA):**

LightGBM: F1-Score 0.855
Random Forest: F1-Score 0.844
Gradient Boosting: F1-Score 0.855

## Explainable AI (XAI):
Utilized SHAP (Shapley Additive Explanations) for model explainability.
Provided insights into feature contributions globally and on a sample level.
For a detailed analysis, refer to the complete project paper.

