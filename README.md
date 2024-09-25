# Customer Churn Analysis and Prediction

This repository contains two Jupyter notebooks for analyzing and predicting customer churn using a dataset from Kaggle.

## Dataset

The original dataset is sourced from Kaggle: [Customer Churn Dataset](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset)

## Notebooks

### 1. data-augmentation.ipynb

This notebook focuses on data preprocessing, feature engineering, and data augmentation. Key components include:

- Data loading and initial exploration
- Feature engineering to create additional metrics
- Data augmentation techniques:
  - Synthetic data generation
  - Introduction of anomalies
  - Addition of missing values
- Visualization of original vs. augmented data:
  - Distribution comparisons
  - Correlation heatmaps
  - Churn rate by categorical features
  - Feature importance
  - Scatter plots and box plots of key features

### 2. churn-predictor.ipynb

This notebook builds and evaluates a neural network model for predicting customer churn. Main steps include:

- Data loading and preprocessing
- Neural network model architecture design
- Model training with early stopping
- Model evaluation on a separate test set
- Visualization of training history and model performance

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow

## Usage

1. Clone this repository
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the notebooks in the following order:
   a. `data-augmentation.ipynb`
   b. `churn-predictor.ipynb`

## File Structure

```
.
├── data/
│   ├── customer_churn_dataset-training-master.csv
│   ├── customer_churn_dataset-testing-master.csv
│   └── augmented-training data.csv
├── notebooks/
│   ├── data-augmentation.ipynb
│   └── churn-predictor.ipynb
├── README.md
└── requirements.txt
```

## Results

The notebooks provide insights into customer churn patterns and demonstrate the process of building a predictive model. Key outputs include:

- Visualizations comparing original and augmented datasets
- Feature importance analysis
- Neural network model performance metrics
- Confusion matrix and classification report for the final model
