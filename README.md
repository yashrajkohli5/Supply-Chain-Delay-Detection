# 🚚 Supply Chain Delay Detection Using Machine Learning

This project predicts whether a shipment will be delayed based on customer, logistics, and order attributes using classification techniques.

## 📁 Dataset
- Source: [Kaggle - Supply Chain Analytics Dataset](https://www.kaggle.com/datasets/prachi13/customer-analytics)
- Records: ~11,000
- Features: Shipping mode, warehouse location, customer location, order dates, product categories
- Target: `Late_delivery_risk` (1 = Late, 0 = On-time)

## 🛠️ Technologies Used
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- xgboost
- Jupyter Notebook

## 🧠 Project Workflow
1. Data Loading & Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training (XGBoost)
5. Evaluation Metrics
6. Business Recommendations

## 📈 Results
- Accuracy: ~83%
- Key Drivers: `Shipping Mode`, `Order to Ship Days`, `Product Importance`, `Customer Segment`
