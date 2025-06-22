# 📉 Customer Churn Prediction App

This project predicts customer churn using a trained **Random Forest Classifier** and provides an interactive **Streamlit web interface** for real-time prediction. Users can input various customer attributes and instantly get the churn status.

## 🎯 Objective

To help businesses identify at-risk customers based on their profile, interaction patterns, and transaction history. Early prediction enables proactive retention strategies.

## 🧠 Model Details

- **Algorithm:** Random Forest Classifier
- **Target Variable:** Churn (1 = Will churn, 0 = Will not churn)

### Features Used:
- Age  
- Amount Spent  
- Login Frequency  
- Gender  
- Marital Status  
- Income Level  
- Product Category  
- Interaction Type  
- Resolution Status  
- Service Usage

## 💻 Tech Stack

- **Python**
- **Streamlit** – Interactive web interface
- **Scikit-learn** – Random Forest model
- **Pandas** – Data handling
- **Joblib** – Model serialization
- **Base64** – (Optional) Background image setup

## 🚀 App Features

- Real-time prediction of churn likelihood
- Manual label encoding for categorical fields
- Optionally includes a background image
- Displays raw input data for reference

## 📂 Folder Structure

churn-prediction-app/
│
├── app.py # Streamlit app code
├── best_rf_low.joblib # Trained model file
├── bg churn.jpg # (Optional) Background image for styling
├── requirements.txt # Python dependencies
├── README.md # Project documentation

## 📊 Example Prediction
- Input: Age = 30, Spent = ₹500, Product = Electronics, Issue = Complaint
- Output: ✅ Result: No Churn

## 📌 Disclaimer
- This app is designed for educational and demonstrative purposes only and should not be used in production without proper validation and testing.
