# Water Potability Prediction Project

## Overview
This project aims to develop a machine learning model to predict water potability based on various water quality parameters. The dataset contains measurements of pH value, hardness, total dissolved solids (TDS), chloramines, sulfate, conductivity, organic carbon, trihalomethanes, turbidity, and the potability label.

## Dataset
- [Water Potability Dataset](https://drive.google.com/file/d/1ypGrF8Gjj2DzqPvoebBH1C5USFC1DtIw/view)
- The dataset consists of 3276 rows and 10 columns.
- Columns with null values: pH, sulfate, and Trihalomethanes.
- Datatypes: Potability (integer), other columns (float).
- Target variable: Potability (1 for potable water, 0 for non-potable water).

## Models and Accuracy Scores
- **XGBoost**: 66.54%
- **Decision Tree**: 64.51%
- **AdaBoost**: 63.40%
- **Logistic Regression**: 62.85%
- **Random Forest**: 62.85%
- **Support Vector Machine (SVM)**: 62.85%
- **KNeighbours**: 59.06%

## Conclusion
The XGBoost model achieved the highest accuracy score, making it the preferred choice for predicting water potability. Further analysis, including hyperparameter tuning and cross-validation, may be required to improve the model's performance and ensure its reliability.
