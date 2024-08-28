
# Credit Card Fraud Detection Using Imbalanced Dataset Techniques

## Description

This project focuses on detecting credit card fraud, a highly imbalanced classification problem where fraudulent transactions are rare compared to non-fraudulent ones. The goal is to build machine learning models that can accurately detect fraudulent transactions while handling the imbalance in the dataset. The project explores various techniques like SMOTE and under-sampling, and evaluates multiple models to improve prediction accuracy.

## Dataset

The dataset consists of anonymized credit card transactions labeled as fraudulent or non-fraudulent. Key features include transaction details, which are scaled to ensure uniformity, and the target variable, indicating whether the transaction is fraudulent.

## Compilation

To run this project, you’ll need the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `imblearn` (for SMOTE)
- `xgboost`

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost
```

The project is implemented in a Jupyter Notebook and should be executed sequentially to ensure that all dependencies are correctly loaded.

## Format

The notebook is structured as follows:

1. **Data Preprocessing:** Includes scaling and handling missing values.
2. **Imbalanced Handling:** Techniques like SMOTE and under-sampling are applied to balance the dataset.
3. **Modeling:** Various machine learning models, including Logistic Regression, Random Forest, and XGBoost, are trained and evaluated.
4. **Evaluation:** Models are assessed using metrics like ROC-AUC, Precision-Recall, and Learning Curves.
5. **Conclusion:** Summary of model performance and insights into handling imbalanced datasets.

## Usage

To use this project:

1. Clone the repository or download the notebook and dataset.
2. Place the dataset in the same directory as the notebook.
3. Open the notebook in Jupyter and run the cells in order.

You can customize the parameters or experiment with different models and techniques to improve detection accuracy.

## Statistics

This project covers:

- **Data Preprocessing:** Handling imbalanced datasets with techniques like SMOTE and under-sampling.
- **Model Building:** Training models including Logistic Regression, Random Forest, and XGBoost.
- **Model Evaluation:** Using metrics such as ROC-AUC, Precision-Recall, and Learning Curves to assess model performance.

## Conclusion

The project demonstrates the challenges and solutions for dealing with imbalanced datasets in fraud detection, highlighting the effectiveness of combining sampling techniques with advanced machine learning models.
