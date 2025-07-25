# 🚚 Supply Chain Delay Detection

This project detects whether a supply chain order will be delayed based on features like shipment mode, customer engagement, product importance, and discounts. We use both XGBoost (for predictive power) and Logistic Regression (for interpretability).

## 📁 Dataset
- Source: [Kaggle - Late Delivery Risk](https://www.kaggle.com/datasets/prachi13/customer-analytics)
- Features: Warehouse block, shipping mode, customer care calls, product importance, discount, weight
- Target: `Late_delivery_risk` (1 = on-time, 0 = delayed)

## 🧠 ML Models
- Logistic Regression: For explaining key delay factors
- XGBoost: For accurate prediction of late deliveries

## 📊 Project Steps
1. Data Cleaning
2. EDA & Visualizations
3. SMOTE for class balancing
4. Feature Engineering
5. Modeling & ROC AUC Evaluation
6. Hyperparameter Tuning & SHAP Interpretation
7. Recommendations

## 📈 Results
- XGBoost ROC AUC: ~0.83 (after tuning)
- Logistic Regression ROC AUC: ~0.78
- Most important features: Discount Offered, Customer Calls, Product Importance, Shipping Mode

## 📌 Recommendations
- Use model to alert teams about likely delays
- Optimize shipping mode allocation by region
- Prioritize important products in logistics
- Monitor customer call volumes as early warning indicators

## 🛠️ Tech Stack
- Python, pandas, seaborn, matplotlib, sklearn, xgboost, imbalanced-learn, SHAP
