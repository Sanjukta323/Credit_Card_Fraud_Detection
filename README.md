Credit Card Fraud Detection using Logistic Regression


Overview

This repository contains the code and resources for a credit card fraud detection project using logistic regression. The goal of this project is to build a binary classification model that can identify whether a credit card transaction is fraudulent or legitimate based on historical transaction data and various transaction features.

Dataset

The dataset used for this project is not included in this repository due to its large size. However, you can find the dataset at source_link and download it to the data folder in the project directory before running the code.

The dataset contains the following features:

Time: 
Number of seconds elapsed between this transaction and the first transaction in the dataset.

Amount: 
Transaction amount.

V1, V2, ..., V28: Anonymized features resulting from a PCA transformation to protect user identities.

Class: 
Binary label indicating whether the transaction is fraudulent (1) or legitimate (0).

Getting Started

Prerequisites
Make sure you have the following dependencies installed:

Python (>=3.6)
pandas
numpy
scikit-learn
You can install these dependencies using pip with the following command:

Copy code
pip install pandas numpy scikit-learn
Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
Download the dataset from source_link and place it in the data folder.
Usage
Navigate to the project directory:
bash
Copy code
cd credit-card-fraud-detection
Run the credit_card_fraud_detection.py script:
Copy code
python credit_card_fraud_detection.py
The script will load the dataset, preprocess the data, split it into training and testing sets, train the logistic regression model, and evaluate its performance. The final evaluation metrics will be displayed on the console.
Model Evaluation
The logistic regression model is evaluated using the following metrics:

Accuracy: 

The proportion of correctly classified transactions.
Precision: The ability of the model to correctly identify fraudulent transactions out of all transactions predicted as fraudulent.
Recall: The ability of the model to correctly identify fraudulent transactions out of all actual fraudulent transactions.
F1-score: The harmonic mean of precision and recall, providing a balanced measure between the two.
ROC-AUC: The area under the Receiver Operating Characteristic (ROC) curve, indicating the model's ability to discriminate between fraudulent and legitimate transactions.
Results
Based on the evaluation metrics, the logistic regression model demonstrates promising results in detecting credit card fraud. However, please note that this is just one approach, and real-world fraud detection systems may combine various techniques to achieve higher accuracy and robustness.

Future Enhancements
The project can be extended in the following ways:

Explore other machine learning algorithms and compare their performance with logistic regression.
Implement feature engineering techniques to improve the model's predictive power.
Investigate anomaly detection algorithms to detect fraud based on unusual patterns.
Contributing
Contributions to this project are welcome! If you find any bugs or have ideas for improvement, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
Special thanks to Dataset Source for providing the credit card fraud dataset.

If you use this project or the dataset, please consider citing the source to give credit to the original creators.
