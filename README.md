# 🛒 Big Mart Sales Prediction

## 📖 Overview
The **Big Mart Sales Prediction** project uses **Machine Learning** to predict the sales of products across different Big Mart outlets.  
By analyzing historical data and identifying key factors such as product type, outlet size, and location, this project aims to help retailers make **data-driven decisions** to optimize inventory and boost revenue.

---

## 🎯 Objective
To build a **predictive model** that accurately estimates **product sales** based on multiple features using regression algorithms.

---

## 🧠 Key Features
- Data cleaning and preprocessing (handling missing values, encoding categories)
- Exploratory Data Analysis (EDA) for insights and visualization
- Feature engineering for improving model performance
- Implementation of multiple ML models:
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor
- Model evaluation using metrics such as:
  - R² Score  
  - Mean Absolute Error (MAE)  
  - Root Mean Square Error (RMSE)

---

## 📂 Dataset
The dataset contains product and store-level attributes, including:

| Feature | Description |
|----------|-------------|
| `Item_Identifier` | Unique ID for each product |
| `Item_Weight` | Weight of the product |
| `Item_Fat_Content` | Fat category of the product |
| `Item_Visibility` | Visibility of the product in the store |
| `Item_Type` | Category of the product |
| `Item_MRP` | Maximum Retail Price |
| `Outlet_Identifier` | Unique ID for each outlet |
| `Outlet_Size` | Size of the outlet (Small/Medium/Large) |
| `Outlet_Location_Type` | Type of city the outlet is in |
| `Outlet_Type` | Grocery store, supermarket, etc. |
| `Item_Outlet_Sales` | Target variable – product sales |

**Dataset Source:**  
[Big Mart Sales Dataset on Kaggle](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data)

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:**
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - jupyter / VS Code  

---

## 🚀 Steps Performed
1. **Data Import & Inspection**
2. **Data Cleaning:** Handling missing values and standardizing inconsistent labels
3. **EDA:** Visualizing sales trends and feature relationships
4. **Feature Encoding:** Converting categorical variables into numerical form
5. **Model Training:** Testing multiple regression algorithms
6. **Model Evaluation:** Comparing model performance
7. **Prediction:** Making final sales predictions on test data

---

## 📊 Results
The final model achieved strong predictive accuracy and a high **R² score**, proving that machine learning can effectively forecast sales trends based on store and product characteristics.

---

## 🌟 Future Improvements
- Hyperparameter tuning for better accuracy
- Adding deep learning regression models
- Deploying a **web dashboard** for real-time prediction and visualization

---

## 👩‍💻 Author
**Mahnoor Hassan**  
BS (Artificial Intelligence)  
---
