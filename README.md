# 🏨 Hotel Booking Cancellation Prediction using Random Forest

## 📌 Project Overview
This project focuses on predicting **hotel booking cancellations** using a **Random Forest classification model**. By analyzing booking details and customer behavior, the model helps identify reservations that are likely to be canceled, enabling better revenue management and operational planning.

---

## 🎯 Objectives
- Clean and preprocess hotel booking data
- Perform exploratory data analysis (EDA)
- Engineer relevant features for modeling
- Train and evaluate a Random Forest classification model
- Measure model performance using classification metrics

---

## 🗂️ Dataset Description
The dataset contains hotel reservation information, including:

- Hotel Type
- Lead Time
- Arrival Date details
- Number of Adults, Children, and Babies
- Meal Type
- Country
- Market Segment
- Distribution Channel
- Deposit Type
- Customer Type
- Previous Cancellations
- Booking Changes
- Special Requests
- Target variable: **Cancellation Status** (Canceled / Not Canceled)

---

## 🧹 Data Preprocessing & Exploratory Data Analysis
The following steps were performed:

- Loaded and explored the dataset
- Removed irrelevant or duplicate columns
- Handled missing values appropriately
- Encoded categorical variables into numerical format
- Treated outliers in numerical features
- Visualized relationships between cancellation status and key features such as:
  - Lead Time
  - Previous Cancellations
  - Deposit Type
  - Market Segment

---

## 🤖 Machine Learning Model
### Model Used
- **Random Forest Classifier**

### Feature Engineering
- Encoded categorical variables
- Scaled numerical features where required
- Split the dataset into training and testing sets

---

## 📊 Model Evaluation
The model performance was evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix
- Classification Report

These metrics help assess the model’s ability to correctly predict booking cancellations.

---

## 🧠 Key Insights
- Lead time and previous cancellations strongly influence cancellation behavior
- Random Forest provides robust performance and handles feature interactions well
- Ensemble models outperform single-tree models in complex datasets

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
