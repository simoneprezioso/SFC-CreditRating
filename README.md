# SFC Credit Rating Project

## Overview

This project aims to build a machine learning model to predict **credit ratings** based on financial and/or behavioral data. The goal is to design a reproducible pipeline covering data processing, feature engineering, and model development.

---

## Objectives

* Develop a predictive model for credit rating classification
* Identify key features influencing creditworthiness
* Build a reproducible end-to-end pipeline
* Evaluate model performance using appropriate metrics

---

## Project Structure

```
SFC-CreditRating/
│
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks (EDA, experiments)
├── src/                   # Source code
│   ├── data/              # Data preprocessing scripts
│   ├── features/          # Feature engineering
│   ├── models/            # Model training & evaluation
│   └── utils/             # Helper functions
│
├── results/               # Outputs (plots, metrics, models)
├── README.md
└── requirements.txt
```

---

## Methodology

### 1. Data Processing

* Data collection from Kaggle
* Handling missing values and outliers
* Encoding categorical variables
* Train/validation/test split

### 2. Feature Engineering

* Financial ratios
* Aggregated statistics
* Feature selection (correlation, importance)

### 3. Modeling

* Baseline: Logistic Regression
* Advanced models:
  * Random Forest
  * Gradient Boosting (XGBoost / LightGBM)

### 4. Evaluation

* Accuracy
* Precision / Recall / F1-score
* ROC-AUC
* Confusion Matrix

---

## Team Structure

### Data Team

* Data collection and cleaning
* Feature engineering
* Dataset versioning

### Model Team

* Model development and tuning
* Performance evaluation
* Model selection

---

## Timeline (1 Month)

| Week   | Focus                                       |
| ------ | ------------------------------------------- |
| Week 1 | Setup, data exploration, problem definition |
| Week 2 | Data cleaning, baseline model               |
| Week 3 | Feature engineering, model tuning           |
| Week 4 | Final model, evaluation, reporting          |

---

## Installation

```bash
git clone <repo-url>
cd SFC-CreditRating
pip install -r requirements.txt
```

---

## Usage

Run notebooks for exploration:

```bash
jupyter notebook
```

Run training pipeline:

```bash
python src/models/train.py
```

---

## Results

Results and evaluation outputs are stored in:

```
results/
```

Includes:

* Model performance metrics
* Visualizations (ROC, confusion matrix)
* Saved models

---

## Future Improvements

* Incorporate more diverse datasets
* Try deep learning approaches
* Improve model interpretability (e.g., SHAP)
* Deploy as an API or web app

---

## Notes

* Ensure no data leakage during preprocessing
* Maintain reproducibility via fixed random seeds
* Keep dataset versions consistent across teams

---

## Contributors
- Claudio Bizzarri
- Luca Turco
- Matteo Lagona
- Luca Tartaglione
- Giacomo Mazzarella
- Francesco Ferraro
- Simone Prezioso (Lead)
