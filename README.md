# 🚗 Used Car Price Prediction

## 📌 Objective
This project builds a machine learning model to predict the price of a used car based on various vehicle attributes. The goal is to support car sellers, buyers, and dealerships in making more informed pricing decisions — helping reduce underpricing and maximize profitability.

---

## 🔧 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Regression Modeling
- Data Preprocessing & Feature Engineering

---

## 📈 Business Context
The used car market often suffers from pricing inconsistencies that can result in revenue loss or buyer distrust. A data-driven pricing model helps:
- Standardize vehicle valuations
- Detect undervalued/overpriced listings
- Improve transparency and efficiency in online car marketplaces

---

## 🔍 Project Workflow

### 1. Data Cleaning
- Handled missing values
- Encoded categorical variables (e.g., fuel type, transmission)
- Removed outliers

### 2. Exploratory Data Analysis (EDA)
- Analyzed relationships between features and price
- Used heatmaps, scatterplots, and histograms to detect trends

### 3. Feature Engineering
- Created new variables like `car_age` from registration year
- Normalized features with skewed distributions

### 4. Modeling
- Trained multiple models: Linear Regression, Ridge, Lasso, Random Forest
- Evaluated using R², RMSE, and cross-validation

### 5. Model Selection
- Random Forest delivered the best performance with R² ≈ 0.89

---

## ✅ Key Insights
- **Engine size, mileage, and car age** were the most influential features
- **Random Forest** captured nonlinear relationships better than linear models
- The model generalizes well on unseen data, making it useful for deployment

---



## 🚀 Future Enhancements
- Deploy using Streamlit or Flask for real-time predictions
- Integrate current market data via web scraping APIs
- Expand model to account for regional price variations

---

## 📂 Repository Structure
