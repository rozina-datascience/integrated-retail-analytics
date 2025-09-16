# 🛒 Integrated Retail Analytics for Store Optimization

## 📌 Project Objective
To leverage machine learning and analytics to:
- Detect anomalies in sales data
- Forecast demand across stores & departments
- Segment stores/customers
- Identify cross-selling opportunities (market basket analysis)
- Incorporate external economic factors
- Deliver actionable recommendations for retail optimization

## 📊 Components
1. **Anomaly Detection** – Unusual sales patterns detected and cleaned  
2. **Time-Based Trends** – Seasonal, holiday, and weekly sales insights  
3. **Feature Engineering** – Store size/type, CPI, fuel price, unemployment  
4. **Customer Segmentation** – Cluster analysis for store optimization  
5. **Market Basket Analysis** – Department-level cross-selling rules  
6. **Demand Forecasting** – Machine learning models with evaluation (RMSE, MAE, R²)  
7. **Strategic Recommendations** – Personalized promotions & inventory strategies  

## 🚀 Results
- Best Forecasting Model: **DecisionTree_default**
- Validation Performance:  
  - RMSE: 4866.34  
  - MAE: 1878.19  
  - R²: 0.9546  

## 📂 Repository Contents
- `notebooks/` – Full Colab notebook  
- `data/` – Processed datasets  
- `models/` – Saved forecasting model  
- `outputs/` – Predictions, frequent itemsets, association rules  
- `reports/` – Final Report  

## 🛠️ Installation
```bash
git clone https://github.com/<your-username>/integrated-retail-analytics.git
cd integrated-retail-analytics
pip install -r requirements.txt


📚 Requirements

Python 3.8+

pandas, numpy, scikit-learn

mlxtend (for Market Basket Analysis)

matplotlib, seaborn

joblib

👩‍💻 Author

Rozina Mohsin Pathan

---

👉 Next Step for you:  
1. Create a **new GitHub repo** named `integrated-retail-analytics`.  
2. Copy this structure into your repo (I can also generate all starter files for you).  
3. Push your Colab notebook + outputs into it.  

