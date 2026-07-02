# Fraud Detection in Banking

A Machine Learning project that analyzes banking transaction data to identify fraudulent activities. The project applies data preprocessing, exploratory data analysis (EDA), visualization, and classification algorithms to accurately distinguish between genuine and fraudulent transactions.

---

## Project Overview

Fraudulent banking transactions are becoming increasingly common with the rapid growth of digital payments and online banking. Detecting fraud at an early stage helps financial institutions reduce financial losses and improve customer security.

This project builds a fraud detection system using machine learning techniques to classify transactions as **Fraudulent** or **Genuine** based on various transaction attributes.

---

## Objectives

* Clean and preprocess banking transaction data.
* Perform Exploratory Data Analysis (EDA).
* Visualize transaction patterns and fraud trends.
* Encode categorical features for model training.
* Train and evaluate machine learning models.
* Predict whether a transaction is fraudulent.

---

## Dataset

The dataset contains synthetic banking transaction records with features such as:

* Transaction ID
* Customer ID
* Account Age
* Transaction Date
* Transaction Type
* Transaction Amount
* Merchant Category
* Transaction Location
* Device Type
* Banking Channel
* International Transaction
* Login Attempts
* Failed OTP Attempts
* Card Present
* Previous 24-Hour Transactions
* Average Monthly Spending
* Risk Score
* Fraud Status (Target Variable)

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Machine Learning Models

The following algorithms are implemented:

* Logistic Regression
* Random Forest Classifier

---

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Handle missing values
5. Encode categorical variables
6. Perform Exploratory Data Analysis
7. Select features and target variable
8. Split data into training and testing sets
9. Train machine learning models
10. Evaluate model performance
11. Predict fraudulent transactions

---

## Project Structure

```text
Fraud-Detection-in-Banking/
│
├── Fraud_Detection_in_Banking.ipynb
├── Fraud_Detection_in_Banking_Dataset.xlsx
├── README.md
└── (Optional) Report.pdf / Presentation.pptx
```

---

## How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Place the dataset in the project directory.
4. Open the notebook in Jupyter Notebook or Google Colab.
5. Run the cells sequentially.

---

## Results

The machine learning models are evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report
* Feature Importance (Random Forest)

The trained model can successfully classify transactions as genuine or fraudulent based on the provided transaction details.

---

## Future Enhancements

* Use real-world banking datasets.
* Apply deep learning techniques.
* Perform hyperparameter tuning.
* Deploy the model as a web application.
* Integrate real-time fraud detection.

---

## License

This project is created for educational and learning purposes.
