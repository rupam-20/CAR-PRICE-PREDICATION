# 🚗 Car Price Prediction using Machine Learning

## 📌 Problem Definition
Predicting the selling price of used cars is a challenging task as it depends on multiple factors such as car age, fuel type, transmission, and kilometers driven.  
This project aims to build machine learning models to predict used car prices more accurately and help both buyers and sellers make informed decisions.

---

## 🎯 Objectives
- Collect and clean the dataset for modeling.
- Perform exploratory data analysis (EDA) with visualizations.
- Build machine learning models to predict car prices.
- Compare model performance using evaluation metrics.
- Provide insights on the most important features affecting car prices.

---

## 📊 Dataset
- **Source**: [CarDekho Used Cars Dataset](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho)  
- **Size**: ~4,000 rows, 8 columns  
- **Target Variable**: `Selling Price`  
- **Features**: `Year`, `Present Price`, `Kms Driven`, `Fuel Type`, `Seller Type`, `Transmission`, `Owner`

---

## 🛠️ Tools & Libraries
- **Languages**: Python  
- **Libraries**:
  - `pandas`, `numpy` → Data Handling
  - `matplotlib`, `seaborn` → Visualization
  - `scikit-learn` → ML Models & Evaluation
- **IDE/Notebook**: Jupyter / Google Colab  

---

## 🧹 Data Processing Steps
1. Checked and handled missing values.  
2. Removed duplicate records.  
3. Converted `Year` → `Car Age`.  
4. Encoded categorical columns (`Fuel Type`, `Seller Type`, `Transmission`, `Owner`).  
5. Scaled numerical features where required.  

---

## 📈 Methodology
1. Problem Understanding  
2. Data Collection & Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Building (Linear Regression, Decision Tree, Random Forest, Gradient Boosting)  
6. Model Evaluation (MAE, RMSE, R²)  
7. Results & Insights  

---

## 🤖 Model Performance
| Model              | MAE      | RMSE     | R² Score |
|--------------------|----------|----------|----------|
| Linear Regression  | ~221203  | High     | Moderate |
| Decision Tree      | Lower    | Better   | Higher   |
| Random Forest      | Best     | Lowest   | Highest  |
| Gradient Boosting  | Good     | Low      | High     |

➡️ **Random Forest performed best** in predicting car prices.

---

## 🔑 Key Insights
- **Car Age** and **Kms Driven** significantly affect the resale price.  
- **Fuel Type** (Diesel cars have higher prices compared to Petrol).  
- **Transmission**: Automatic cars generally have higher prices.  
- **Seller Type** impacts pricing.    

---
## 🖥️ How to Run

🔧 Requirements

Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```


 
