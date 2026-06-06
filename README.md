# Car Insurance Cross-Sell Prediction

## Overview

This project was completed as part of **BZAN 6357 – Final Group Project** and focuses on predicting whether an existing medical insurance customer will purchase a cross-sold car insurance policy after being contacted by a sales representative.

The objective is to build a machine learning solution capable of identifying customers with the highest likelihood of purchasing car insurance, enabling more effective sales targeting and resource allocation.

---

## Project Highlights

- Data quality assessment and validation
- Exploratory Data Analysis (EDA)
- Feature engineering and preprocessing
- Cross-validated target encoding
- Feature selection and scaling
- Class imbalance handling techniques
- Hyperparameter tuning using Grid Search
- Evaluation using 10-Fold Stratified Cross Validation
- Threshold optimization using Precision-Recall analysis
- Ensemble learning through voting and stacking
- Weight optimization using Nelder-Mead optimization
- Final score dataset prediction generation

---

## Models Evaluated

The project evaluates and compares multiple machine learning approaches:

- Logistic Regression
- Random Forest
- Gradient Boosting
- HistGradientBoosting
- Extra Trees
- K-Nearest Neighbors
- MLP Neural Network
- PCA + MLP
- XGBoost
- LightGBM
- CatBoost
- Voting Ensembles
- Stacking Ensembles

---

## Evaluation Metrics

Model performance is evaluated primarily using:

### ROC AUC
Measures the model's ability to rank purchasers above non-purchasers across all possible classification thresholds.

### F1 Score
Balances precision and recall, making it particularly useful for imbalanced classification problems.

---

## Final Solution

The final solution is an optimized ensemble model constructed from the strongest individual learners.

Model selection, weight optimization, threshold tuning, and final evaluation were performed using a rigorous cross-validation framework designed to maximize predictive performance while minimizing overfitting.

---

## Repository Structure

```text
project/
│
├── insurance_cross_sell_prediction.ipynb
├── README.md
├
│
├── data/
│   ├── TRAINING.csv
│   └── SCORE.csv
│
└── outputs/
    └── my_prediction.csv
```

---


## Documentation

All methodology, feature engineering decisions, preprocessing steps, model selection rationale, hyperparameter tuning procedures, ensemble strategies, evaluation techniques, and business interpretations are thoroughly documented within the notebook itself.

To avoid duplication and maintain a concise repository structure, detailed explanations are intentionally kept within the notebook alongside the corresponding code, visualizations, and results.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-Learn
- XGBoost
- LightGBM
- CatBoost
- SciPy
- TensorFlow

---


---

## License

This project was developed for academic and educational purposes.
