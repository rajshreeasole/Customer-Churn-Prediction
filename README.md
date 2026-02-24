# Customer Churn Prediction ML Project

## 🔹 Project Overview
This project predicts whether a customer will leave (churn) or stay using machine learning.  
It uses a **Random Forest Classifier** and includes data preprocessing, model evaluation, and visualization of results.  

Key features:
- Predicts customer churn based on customer attributes like Gender, Subscription Type, Contract Length, etc.
- Shows **accuracy**, **confusion matrix**, and **feature importance**.
- Allows **predicting churn for individual customers** using their Customer ID.


## 🔹 Dataset
- Dataset used: `customer_churn_dataset.csv`  
- Contains columns like:
CustomerID: Unique identifier for each customer
Age: Customer’s age
Gender: Male or Female (or encoded numeric)
Tenure: How long they have been a customer
Usage Frequency: How often they use the service
Support Calls: Number of calls to support
Payment Delay: Days or count of late payments
Subscription Type: Type of plan they have
Contract Length: Length of their contract
Total Spend: Total money spent
Last Interaction: Time since last interaction (days or date)
Churn: Target label (1 = Left, 0 = Stayed)

## 🔹 How to Run

### Option 1: Using Jupyter Notebook / Colab
1. Open `Customer_Chuns_Prediction.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Make sure `customer_churn_dataset.csv` is in the same folder.
3. Run all cells sequentially.
4. Input a Customer ID when prompted to see the prediction.

### Option 2: Using Python Script
1. Save `customer_churn.py` in the same folder as `customer_churn_dataset.csv`.
2. Run in terminal or command prompt:
```bash
python customer_churn.py


#Screenshort
![Alt text describing image](confusion_matrix.png)
![Alt text describing image](feature_matrix.png)
