# Bank Customer Churn Prediction Using Machine Learning 😎💲
This project predicts whether a bank customer will leave ("churn") or stay with the bank using machine learning techniques. It includes data preprocessing, model training, and an interactive GUI for real-time predictions.

# Table of Contents
1. Overview
2. Project Structure
3. Setup and Installation
4. How to Run
5. Features
6. Results
7. Technologies Used
8. Contributing

# Overview
Customer churn is a critical problem for banks. Identifying at-risk customers can help businesses target retention strategies effectively. This project uses a machine learning pipeline to predict churn and provides a Tkinter-based GUI for end-user interaction.

# Setup and Installation
Prerequisites:
Python 3.7 or higher
Jupyter Notebook
pip or conda for package management

# How to Run
## Run the Notebook
Open the Jupyter Notebook:
bash
Copy code
jupyter notebook
Navigate to Bank_Customer_Churn_Pred.ipynb and run all cells to see data preprocessing, feature engineering, and model training.
## Run the GUI for Predictions
Ensure the saved model (churn_model.pkl) is in the project directory.
Execute the GUI script:
bash
Copy code
python GUI_Churn_Prediction.py
Input the customer details in the GUI form, and click "Predict" to get the prediction:
Exit: The customer is likely to leave the bank.
No Exit: The customer is likely to stay.

## Features
## Machine Learning
Data cleaning, one-hot encoding, and scaling.
Multiple model training (Logistic Regression, Random Forest, Gradient Boosting, etc.).
Random Forest selected as the best model with 87% accuracy.
## Interactive GUI
Tkinter-based interface for user-friendly predictions.
Real-time prediction with "Exit" (red) or "No Exit" (green) feedback.
