# -Car-Insurance-Cross-Sell-Prediction

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Insurance Cross-Sell Prediction</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px;
            line-height: 1.7;
            color: #333;
        }

        h1, h2 {
            color: #1f4e79;
        }

        .container {
            background: #fafafa;
            padding: 30px;
            border-radius: 10px;
            border: 1px solid #ddd;
        }

        ul {
            margin-left: 20px;
        }

        code {
            background: #f4f4f4;
            padding: 2px 5px;
            border-radius: 4px;
        }

        footer {
            margin-top: 40px;
            font-size: 0.9em;
            color: #666;
        }
    </style>
</head>
<body>

<div class="container">

    <h1>🚗 Car Insurance Cross-Sell Prediction</h1>

    <h2>Overview</h2>
    <p>
        This project was completed as part of <strong>BZAN 6357 – Final Group Project</strong> and focuses on
        predicting whether an existing medical insurance customer will purchase a cross-sold car insurance policy
        after being contacted by a sales representative.
    </p>

    <p>
        The objective is to build a machine learning solution capable of identifying customers with the highest
        likelihood of purchasing car insurance, enabling more effective sales targeting and resource allocation.
    </p>

    <h2>Project Highlights</h2>
    <ul>
        <li>Data quality assessment and validation</li>
        <li>Exploratory Data Analysis (EDA)</li>
        <li>Feature engineering and preprocessing</li>
        <li>Cross-validated target encoding</li>
        <li>Feature selection and scaling</li>
        <li>Class imbalance handling techniques</li>
        <li>Hyperparameter tuning using Grid Search</li>
        <li>Evaluation using 10-Fold Stratified Cross Validation</li>
        <li>Threshold optimization using Precision-Recall analysis</li>
        <li>Ensemble learning through voting and stacking</li>
        <li>Weight optimization using Nelder-Mead optimization</li>
        <li>Final score dataset prediction generation</li>
    </ul>

    <h2>Models Evaluated</h2>
    <ul>
        <li>Logistic Regression</li>
        <li>Random Forest</li>
        <li>Gradient Boosting</li>
        <li>HistGradientBoosting</li>
        <li>Extra Trees</li>
        <li>K-Nearest Neighbors</li>
        <li>MLP Neural Network</li>
        <li>PCA + MLP</li>
        <li>XGBoost</li>
        <li>LightGBM</li>
        <li>CatBoost</li>
        <li>Voting Ensembles</li>
        <li>Stacking Ensembles</li>
    </ul>

    <h2>Evaluation Metrics</h2>
    <ul>
        <li><strong>ROC AUC</strong> – Measures ranking performance across all classification thresholds.</li>
        <li><strong>F1 Score</strong> – Balances precision and recall for imbalanced classification tasks.</li>
    </ul>

    <h2>Final Solution</h2>
    <p>
        The final solution is an optimized ensemble model constructed from the strongest individual learners.
        Model selection, weight optimization, threshold tuning, and final evaluation were performed using a
        rigorous cross-validation framework designed to maximize predictive performance while minimizing overfitting.
    </p>

    <h2>Repository Structure</h2>

<pre>
project/
│
├── insurance_cross_sell_prediction.ipynb
├── README.html
├── requirements.txt
│
├── data/
│   ├── TRAINING.csv
│   └── SCORE.csv
│
└── outputs/
    └── my_prediction.csv
</pre>

    <h2>Running the Project</h2>
    <ol>
        <li>Install the required dependencies from <code>requirements.txt</code>.</li>
        <li>Open the Jupyter Notebook.</li>
        <li>Run all cells sequentially from top to bottom.</li>
    </ol>

    <p>
        The notebook contains the complete workflow, from data preparation and exploratory analysis
        to model development, ensemble construction, evaluation, and final prediction generation.
    </p>

    <h2>Documentation</h2>
    <p>
        All methodology, feature engineering decisions, preprocessing steps, model selection rationale,
        hyperparameter tuning procedures, ensemble strategies, evaluation techniques, and business interpretations
        are thoroughly documented within the notebook itself.
    </p>

    <p>
        To avoid duplication and maintain a concise repository structure, detailed explanations are intentionally
        kept within the notebook alongside the corresponding code, visualizations, and results.
    </p>

    <footer>
        <hr>
        <p><strong>BZAN 6357 – Final Group Project</strong><br>
        University of Texas at Dallas</p>

        <p>
            This project was developed for academic and educational purposes.
        </p>
    </footer>

</div>

</body>
</html>
