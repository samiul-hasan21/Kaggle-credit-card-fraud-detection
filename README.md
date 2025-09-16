🛡️ Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions using the Kaggle Credit Card Fraud Detection dataset.

📊 Dataset

Source: Kaggle Credit Card Fraud Detection

Total Transactions: 284,807

Fraudulent Transactions: 492

Features: 30 numerical features (V1–V28, Time, Amount)

Highly imbalanced dataset (fraud < 0.2%)

🛠️ Approach

Data Preprocessing:

Checked for missing values

Scaled numerical features

Split into training & testing sets

Model Building:

Implemented ML models (e.g., Logistic Regression)

Evaluated with Accuracy, Precision, Recall, and F1-score

Performance:

Training Accuracy: 94.16%

Test Accuracy: 93.91%

✅ The model performs well on unseen data, but due to dataset imbalance, additional metrics like precision & recall are recommended for a more complete evaluation.

🚀 Usage

Clone this repository:

git clone <your-repo-link>


Install dependencies:

pip install -r requirements.txt


Run the notebook or script:

jupyter notebook CreditCardFraud.ipynb

🔮 Future Improvements

Explore advanced models like XGBoost or Neural Networks

Handle class imbalance with techniques like SMOTE

Deploy as a web app for real-time fraud detection

📜 License

This project is open-source and available under the MIT License.
