Fatigue Life Prediction Using Machine Learning

Overview : 
This project predicts the fatigue life of steel using machine learning. Fatigue life determines how long a material withstands repeated stress before failure. Fatigue strength is the maximum stress a material can withstand at a given number of cycles without failing.

The model is built using the XGBoost regression algorithm, leveraging material property data for predictions.

Features
-XGBoost Model: Efficient and accurate fatigue strength predictions.
-Comprehensive Pipeline: Data preprocessing, feature engineering, and performance evaluation.
-Performance Metrics: Includes R-squared (R²) and Mean Squared Error (MSE).

Repository Contents :
-`MMD 301 -2.ipynb`: Jupyter Notebook with code for data processing, EDA, model training, and evaluation.
-`Fatigue_Dataset_for_Steel.csv`: Dataset containing material properties and fatigue strength values.

Requirements :
- Python 3.11
- Key Libraries: `xgboost`, `pandas`, `numpy`, `matplotlib`, `scikit-learn`

Dataset Overview :
- Material Properties: Includes features such as chemical composition, hardness, and tensile strength.
- Target Variable: Fatigue strength (MPa).

Model Performance : 
- Evaluation Metrics :
  - R-squared (R²): Measures the proportion of variance explained by the model.
  - Mean Squared Error (MSE): Indicates prediction accuracy.

Contribution Guidelines : 
Contributions are welcome! Fork this repository, make your improvements, and submit a pull request.



