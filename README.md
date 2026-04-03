# Taiwanese Bankruptcy Prediction using Logistic Regression

## Project Overview
This project analyzes the Taiwanese Bankruptcy Prediction dataset from the UCI Machine Learning Repository and builds a Logistic Regression classification model to predict company bankruptcy.

## Dataset Information
- **Source**: UCI Machine Learning Repository
- **Dataset ID**: 572
- **Instances**: 6,819 companies
- **Features**: 95 financial indicators
- **Target**: Binary classification (0 = Non-bankrupt, 1 = Bankrupt)
- **Period**: 1999-2009 (Taiwan Economic Journal)
- **License**: CC BY 4.0

## Project Structure
```
taiwanese+bankruptcy+prediction/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── Taiwanese_Bankruptcy_Prediction.ipynb
└── data/
    └── (dataset will be downloaded here)
```

## Installation

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook

### Setup
1. Clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to `notebooks/Taiwanese_Bankruptcy_Prediction.ipynb`
3. Run cells sequentially

## Project Stages
- [ ] Stage 1: Data Loading and Exploration
- [ ] Stage 2: Exploratory Data Analysis (EDA)
- [ ] Stage 3: Data Preprocessing
- [ ] Stage 4: Model Training
- [ ] Stage 5: Model Evaluation
- [ ] Stage 6: Feature Importance Analysis

## Model
- **Algorithm**: Logistic Regression
- **Regularization**: L2 (Ridge)
- **Class Balancing**: SMOTE (Synthetic Minority Over-sampling Technique)
- **Validation**: 5-Fold Stratified Cross-Validation

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Precision-Recall AUC

## Author
[Your Name]

## License
This project uses the Taiwanese Bankruptcy Prediction dataset which is licensed under CC BY 4.0.
