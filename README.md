# Customer Churn Prediction with Deep Learning

A polished end-to-end machine learning project that predicts whether a customer is likely to churn using a deep neural network built with TensorFlow and deployed through a Streamlit web app.

---

## 🌟 Project Overview

This project analyzes customer behavior and banking attributes to estimate the probability of churn. It combines data preprocessing, neural network training, and an interactive prediction interface to make the solution practical and easy to use.

The model is trained on the Bank Customer Churn dataset and predicts whether a customer is likely to leave the service.

### 🌐 Live Demo

Try the deployed app here: https://customerchurnpredictor-een6qfk9svfoevgmjcvddt.streamlit.app/

---

## ✨ Key Features

- Predicts customer churn probability from real-world features
- Uses a trained Artificial Neural Network (ANN)
- Includes preprocessing for categorical and numerical variables
- Provides a simple and interactive Streamlit dashboard
- Designed for both learning and deployment purposes

---

## 📊 Model Performance

The trained model achieved the following results during training:

| Metric | Value |
|---|---:|
| Training Accuracy | 87.16% |
| Training Loss | 0.3076 |
| Validation Accuracy | 85.70% |
| Validation Loss | 0.3601 |

These results indicate that the model successfully learned meaningful patterns for churn prediction while maintaining strong generalization on validation data.

---

## 🧠 Tech Stack

- Python
- TensorFlow / Keras
- Streamlit
- scikit-learn
- pandas
- numpy
- matplotlib

---

## 📁 Project Structure

- app.py — Streamlit application for interactive prediction
- ANN_implement.ipynb — model training and experimentation notebook
- prediction.ipynb — prediction workflow and inference notebook
- model.h5 — trained neural network model
- scaler.pkl — feature scaling object
- label_encoder_gender.pkl — gender label encoder
- onehot_encoder_geo.pkl — geography one-hot encoder
- Churn_Modelling.csv — dataset used for training

---

## ▶️ How to Run

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Start the app:
   ```bash
   streamlit run app.py
   ```

3. Enter customer details in the web interface and view the churn prediction.

---

## 🔍 Prediction Logic

The app accepts customer inputs such as:

- Geography
- Gender
- Age
- Balance
- Credit Score
- Estimated Salary
- Tenure
- Number of Products
- Credit Card status
- Active membership status

Based on these inputs, the model returns a churn probability score. If the probability is above 0.5, the customer is considered likely to churn.

---

## 🎯 Why This Project Matters

Customer churn prediction helps businesses identify at-risk customers early, allowing them to take proactive retention actions and improve customer satisfaction and profitability.

---

## 🙌 Author

Built and maintained by Vedant Thakar.

- LinkedIn: [Vedant Thakar](https://www.linkedin.com/in/vedant-thakar-4ba561292/)
- GitHub: [vedant070206](https://github.com/vedant070206)
- Email: thakar2006@gmail.com