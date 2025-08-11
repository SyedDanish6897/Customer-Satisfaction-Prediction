# 📊 Customer Satisfaction Prediction

## 📌 Overview
The **Customer Satisfaction Prediction** project aims to analyze customer support ticket data and predict customer satisfaction ratings (1–5 scale).  
This can help companies identify problem areas, improve service quality, and retain customers.

The project involves:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Training & Evaluation
- Saving the trained model for deployment

---

## 📑 Table of Contents
1. Dataset
2. Technologies Used]
3. Project Workflow
4. EDA Insights
5. Model Performance
10. Author: Syed Danish 

---

## 📂 Dataset
- **Name:** Customer Support Tickets Dataset
- **Size:** ~8,469 rows, 14 columns
- **Source:** (https://drive.google.com/file/d/1DRdLKOinSNuoMwVyFGH86f3xEhkZMrz6/view)
- **Key Features:**
  - `Customer Age` – Age of the customer
  - `Customer Gender` – Gender of the customer
  - `Product Purchased` – Product name
  - `Ticket Type` – Technical issue, billing inquiry, etc.
  - `Ticket Priority` – Low, Medium, High, Critical
  - `Ticket Channel` – Email, Phone, Chat, Social Media
  - `First Response Time` – Time to first reply
  - `Time to Resolution` – Time taken to close the ticket
  - `Customer Satisfaction Rating` – Rating from 1 to 5 (**Target Variable**)

---

## ⚙️ Technologies Used
- **Programming Language:** Python 🐍
- **Libraries:**
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Machine learning model training
  - `joblib` – Saving the trained model
  - `jupyter` – Interactive notebook environment
- **Algorithm:** Random Forest Classifier 🌳

---

## 🔄 Project Workflow
1. **Data Loading**
   - Import dataset into Pandas DataFrame
2. **Data Cleaning**
   - Handle missing values
   - Encode categorical variables
   - Convert date columns to `datetime`
3. **EDA (Exploratory Data Analysis)**
   - Analyze satisfaction distribution
   - Compare ticket types, channels, and priorities
   - Find patterns in age groups and product purchases
4. **Feature Engineering**
   - Remove unnecessary columns
   - Encode categorical features
5. **Model Building**
   - Train-Test split (70:30)
   - Feature scaling
   - Random Forest Classifier
6. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report
7. **Model Saving**
   - Save the trained model using `joblib`

---

## 📊 EDA Insights
Some key insights found from EDA:
- Most tickets are related to **Refund requests**, **Software bugs**, and **Product compatibility**.
- Customers with **High or Critical priority tickets** tend to give lower satisfaction ratings.
- Ticket channel distribution shows **Email** and **Chat** are the most used.
- **Middle-aged customers (31–50)** raise the most tickets.
- Certain products have consistently high or low ratings.

*(💡 Add screenshots of plots here for better presentation on GitHub)*

---

## 📈 Model Performance
- **Algorithm:** Random Forest Classifier
- **Accuracy:** ~XX% (replace with your actual score)
- **Precision, Recall, F1-score:** Detailed in the notebook
- Feature importance analysis shows that **Ticket Priority**, **Ticket Type**, and **Product Purchased** are major predictors.

👤 Author
Name: Syed Danish 

GitHub: [SyedDanish6897](https://github.com/SyedDanish6897)

LinkedIn: (https://www.linkedin.com/in/syed-danish-9a9298233/)
Date: 2025
