# Blockchain Beyond Cryptocurrency: Real-World Impact Analysis

This repository demonstrates how blockchain technology provides measurable business value beyond cryptocurrency — specifically in the **supply chain** and **real estate** sectors.

## 🧠 Objective
To analyze real-world datasets using machine learning and visualization techniques to show how blockchain:
- Reduces fraud
- Enhances transparency
- Lowers operational costs

---

## 📁 Datasets Used

### 1. **Trust Chain Dataset**  
Blockchain-backed supply chain records containing transaction info, fraud flags, delivery stats, and smart contract usage.

### 2. **Real Estate Token Dataset**  
Tokenized property investment data including rent yield, property details, investment amount, and region info.

---

## 🧪 Project Structure

```bash
blockchain-impact-analysis/
├── trust_chain_analysis.py           # ML + visual analysis of fraud & transparency
├── real_estate_yield_prediction.py  # Yield prediction using Random Forest
├── real_estate_clustering.py        # Clustering of properties based on investment traits
├── regional_analysis.py             # Regional average yield comparison
├── data/
│   ├── trust_chain_dataset.csv
│   └── Real_Estate_Token_Data.xlsx
├── plots/
│   ├── fraud_rate_by_smart_contract.png
│   ├── transparency_by_smart_contract.png
│   ├── expected_yield_feature_importance.png
│   └── real_estate_clusters.png
├── README.md
```

---

## 🔍 Trust Chain Analysis (Supply Chain)
- **Goal**: Measure blockchain’s role in fraud prevention & transparency.
- Lower fraud rates in smart contract transactions
- Fewer quantity mismatches
- Faster delivery times

### Tools:
- RandomForestClassifier
- GroupBy analysis
- Bar plots

---

## 🏠 Real Estate Analysis

### Yield Prediction
- **Goal**: Identify key factors driving returns in tokenized properties
- Top features: Rent/Token, Square Footage, Walk Score
- RMSE ~ 0.007 | R² ~ 0.30

### Clustering
- **Goal**: Group properties by similar investment profiles
- Found 3 distinct clusters using KMeans + PCA

### Regional Comparison
- **Goal**: Highlight most profitable regions
- Choropleth & bar charts by region

---

## 📦 Dependencies
```bash
pip install pandas matplotlib seaborn scikit-learn plotly openpyxl
```

---

## 📈 Results
Blockchain-backed processes:
- Cut down fraud in supply chains
- Boosted transparency in deliveries
- Enabled smarter, more transparent real estate investments

---

## ✍️ Author
Bhavagna Shreya Bandaru
