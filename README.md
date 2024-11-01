# Online Payment Fraud Detection

This project implements various machine learning algorithms to detect fraudulent transactions in online payments. The project explores different classification approaches to identify patterns and anomalies that might indicate fraudulent activity.

## Dataset

The project uses the Online Fraud Detection dataset (`onlinefraud.csv`) which contains transaction records with the following features:
- Transaction type (transfer, cash_out, etc.)
- Amount
- Source and destination account details
- Transaction flags and indicators
- Transaction outcome (fraudulent or legitimate)

## Implemented Models

The project implements several machine learning algorithms to compare their performance in fraud detection:

### 1. Payment Fraud Analysis (paymentfraud.ipynb)
- Main analysis notebook
- Data preprocessing and feature engineering
- Model training and evaluation
- Performance metrics comparison

### 2. K-Nearest Neighbors (knn.ipynb)
- Implementation of KNN classifier
- Parameter tuning and optimization
- Performance evaluation

### 3. Support Vector Machine (svm.ipynb)
- SVM implementation for classification
- Kernel selection and parameter optimization
- Model evaluation

### 4. Decision Tree (decisiontree.ipynb)
- Decision tree classifier implementation
- Tree visualization and interpretation
- Feature importance analysis

### 5. Linear Regression and Random Forest (lr_rf.ipynb)
- Comparison of linear regression and random forest approaches
- Ensemble method implementation
- Performance analysis

## Project Structure

```
.
├── onlinefraud.csv           # Dataset file
├── paymentfraud.ipynb        # Main analysis notebook
├── knn.ipynb                 # K-Nearest Neighbors implementation
├── svm.ipynb                 # Support Vector Machine implementation
├── decisiontree.ipynb       # Decision Tree implementation
├── lr_rf.ipynb              # Linear Regression and Random Forest implementation
└── README.md                # Project documentation
```

## Requirements

The project requires the following Python libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## Usage

1. Clone the repository
2. Install the required dependencies
3. Open the Jupyter notebooks to run the analyses
4. Start with `paymentfraud.ipynb` for the main analysis
5. Individual algorithm implementations can be found in their respective notebooks

## Model Performance

Each notebook contains detailed performance metrics including:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC curves
- Confusion matrices

The models are evaluated using cross-validation to ensure robust performance assessment.
