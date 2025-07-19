## 📁 Dataset
- Source: [Kaggle - Late Delivery Risk](https://www.kaggle.com/datasets/prachi13/customer-analytics)
- Features: Order date, shipping date, product category, mode, customer region
- Target: `Late_delivery_risk` (1 = delayed, 0 = on-time)

## 🧠 ML Models
- Logistic Regression: For explaining key delay factors
- XGBoost: For accurate prediction of late deliveries

## 📊 Project Steps
1. Data Cleaning
2. EDA & Visualizations
3. Feature Engineering
4. Modeling
5. Evaluation & Insights
6. Business Recommendations

## 📈 Results
- XGBoost Accuracy: ~91%
- Logistic Regression Accuracy: ~84%
- Most important features: Shipping Mode, Distance, Product Importance, Prior Purchases

## 📌 Recommendations
- Use model to alert teams about likely delays
- Optimize shipping mode allocation by region
- Prioritize important products in logistics

## 🛠️ Tech Stack
- Python, pandas, seaborn, matplotlib, sklearn, xgboost
