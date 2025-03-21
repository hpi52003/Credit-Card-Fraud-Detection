# Credit-Card-Fraud-Detection
## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset consists of anonymized transaction features with a binary label indicating fraud or legitimate transactions.

## Objectives
- Perform data preprocessing and exploratory data analysis (EDA)
- Apply feature scaling and handling class imbalance
- Train machine learning models to classify transactions as fraudulent or legitimate
- Evaluate model performance using classification metrics

## Dataset
The dataset contains the following features:
- `Time` - Seconds elapsed between the transaction and the first transaction in the dataset
- `V1` to `V28` - Anonymized principal components from PCA transformation
- `Amount` - Transaction amount
- `Class` - Target variable (0: Legitimate, 1: Fraudulent)

## Requirements
Ensure you have the following installed:
- Python (>=3.8)
- Jupyter Notebook or any Python IDE
- Required libraries:
  ```bash
  pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
  ```

## Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```
2. Place the `credit_card_transactions.csv` dataset in the project directory.
3. Open and run the script in a Jupyter Notebook or execute `main.py`:
   ```bash
   python main.py
   ```
4. The script will preprocess the data, handle class imbalance, train models, and output evaluation metrics.

## Machine Learning Models Used
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Neural Networks (optional)

## Evaluation Metrics
- Accuracy Score
- Precision, Recall, and F1-Score
- ROC-AUC Score
- Confusion Matrix

## Handling Class Imbalance
Since fraudulent transactions are rare, the project implements:
- **Oversampling** (SMOTE - Synthetic Minority Over-sampling Technique)
- **Undersampling** of majority class

## Contributing
Feel free to submit pull requests or report issues. Contributions are welcome!

## License
This project is licensed under the MIT License.

