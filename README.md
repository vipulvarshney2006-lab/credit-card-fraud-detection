# Credit Card Fraud Detection

## 📌 Project Overview

This project detects fraudulent credit card transactions using Machine Learning.

The dataset is highly imbalanced because normal transactions are much more common than fraudulent transactions.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* SMOTE
* Matplotlib
* Google Colab

## 🔄 Project Workflow

1. Load the dataset
2. Perform basic data analysis
3. Separate features and target
4. Split data into training and testing sets
5. Apply SMOTE to the training data
6. Train an XGBoost classifier
7. Generate fraud probabilities
8. Tune the decision threshold
9. Evaluate using precision, recall and F1-score
10. Analyze the confusion matrix
11. Check feature importance

## 📊 Evaluation Metrics

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

For fraud detection, precision and recall are especially important because the dataset is highly imbalanced.

## 📈 Feature Importance

XGBoost feature importance was used to identify which transaction features contributed most to the model's predictions.

## 📂 Dataset

The project uses the Kaggle Credit Card Fraud Detection dataset.

The dataset file is not included in this repository because of its large size.

## ▶️ How to Run

The notebook can be opened using Google Colab.

1. Download the dataset.
2. Upload `creditcard.csv` to the Colab session.
3. Open the notebook.
4. Run the cells sequentially.

## 👨‍💻 Author

Vipul Varshney
