🚀Movie Genre Classification, SMS Spam Detection & Customer Churn Prediction Projects

Explore a collection of machine learning projects addressing real-world challenges, including SMS spam detection, movie genre classification, and bank customer churn prediction.


🗂️ Projects Overview

1️⃣ SMS Spam Detection

Identify SMS messages as Spam or Ham (not spam) using text preprocessing and an SVM model.
Features
Preprocessed dataset with spam/ham labels.
TF-IDF vectorizer for feature extraction.
Classification reports for model evaluation.
Interactive message classification.

Run Instructions
1. Ensure spam.csv is in the directory.
2. Run the script and classify SMS messages interactively.



2️⃣ Movie Genre Classification

Predict movie genres based on plot descriptions using Logistic Regression.
Features
TF-IDF-based text vectorization.
Genre label encoding for model training.
Confusion matrix visualization for evaluation.
Predict genres using custom plot descriptions.

Run Instructions
1. Add train_data.txt and test_data.txt to the directory.
2. Execute the script and input movie plots for predictions.


3️⃣ Bank Customer Churn Prediction

Predict if customers will leave the bank using Random Forest Classifier.
Features
Encoded categorical features (e.g., Geography, Gender).
Standardized input for better model performance.
Interactive churn predictions with user-provided inputs.

Run Instructions
1. Use dataset.csv or your own dataset.
2. Run the script and predict churn via interactive mode.


🛠️ Setup Requirements

Install the required Python libraries:
pip install pandas scikit-learn matplotlib seaborn



📊 Project Summary Table
## ✨ Features and Models
| *Project*         | *Algorithm*         | *Tools*      |
|----------------------|-----------------------|----------------|
| SMS Spam Detection   | SVM                  | TF-IDF, sklearn |
| Movie Genre Prediction | Logistic Regression | TF-IDF, matplotlib, seaborn |
| Customer Churn       | Random Forest        | sklearn        |



🤝 Contributing
We welcome contributions! Fork the repository, make your changes, and submit a pull request. Let’s build something great together!


📜 License
This repository is licensed under the MIT License. Check LICENSE for details.
