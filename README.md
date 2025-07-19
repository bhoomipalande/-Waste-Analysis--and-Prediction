# -Waste-Analysis-and-Prediction
 Waste Management Analysis &amp; Prediction Using Machine Learning

# ♻️ Predicting Waste Fund Utilization in Indian Cities Using Machine Learning and Deep Learning

## 📌 Project Overview

Efficient urban waste management is one of the most critical challenges faced by Indian municipalities. Although the government allocates substantial funds under initiatives like the **Swachh Bharat Mission**, the actual utilization of these funds often remains suboptimal or undocumented.

This project leverages **machine learning and deep learning techniques** to predict the **funds utilized** by various cities, using features such as waste generation, processing capacity, and financial disbursements. The goal is to assist policy-makers and analysts in identifying inefficiencies and making data-driven decisions for future planning.

---

## 🧾 Problem Statement

The gap between **funds released** and **funds utilized** in urban waste management poses both financial and operational risks. The aim of this project is to develop a predictive system that can:

- Accurately forecast fund utilization for individual cities.
- Highlight discrepancies or underutilization trends.
- Improve the transparency and efficiency of government spending in urban development.

---

## 📂 Dataset Description

- **Source File**: `india_city_waste.csv`
- **Core Features Used**:
  - State and City Names
  - Waste Generated (in Tons Per Day)
  - Waste Processed (TPD)
  - Funds Released by the Government
  - Funds Utilised
  - Unspent Balance

### 📌 Data Preprocessing:
- Removed columns with excessive null values.
- Handled missing data by replacing with zeros or interpolated values.
- Standardized column names and formats.
- Scaled numerical features for better model performance.

---

## 🧠 Models Implemented

| Model                    | Description |
|--------------------------|-------------|
| **Linear Regression**     | Establishes a simple baseline prediction. |
| **Polynomial Regression** | Captures non-linear relationships. |
| **Decision Tree Regressor** | Splits data based on feature thresholds. |
| **Random Forest Regressor** | Combines multiple trees for robust predictions. |
| **Deep Learning Model (Keras)** | A neural network for learning complex patterns. |

---

## 📈 Model Evaluation

Evaluation metrics used:

- **R² Score** (Coefficient of Determination)
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**


✅ Conclusion
This project demonstrates how predictive modeling can be applied to real-world governance challenges. By accurately forecasting fund utilization, we can drive greater accountability, optimize resource allocation, and support sustainable urban planning in India.

The models developed here, particularly the deep learning approach, show strong potential for expanding into other public sector applications such as water management, housing, and infrastructure development.

👩‍💻 Author
Bhoomi Palande
