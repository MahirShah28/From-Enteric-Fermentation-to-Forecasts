# 🌾 From Enteric Fermentation to Forecasts  
### *A Data-Driven Approach to Agricultural Emission Modeling (1961–2019)*

This project analyzes global agricultural greenhouse gas emissions using FAOSTAT data (1961–2019).  
It focuses on understanding and forecasting emissions—especially from **enteric fermentation**—through data cleaning, visualization, and machine learning.

---

## 📘 Overview

Agriculture is a key contributor to climate change, and enteric fermentation (methane from livestock) is one of the largest emission sources.  
This notebook takes a **data-science approach** to study emission patterns, trends, and predictions.

The goal is to transform decades of raw data into clear insights and reliable forecasts using modern analytical methods.

---

## 🔍 Workflow

### 1️⃣ Data Cleaning  
- Loaded FAOSTAT dataset (1961–2019)  
- Removed duplicates and filled missing values  
- Grouped yearly data into **5-year intervals** for smoother trend analysis  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Visualized emissions by country and year  
- Identified top emitting nations  
- Explored global distribution using histograms and heatmaps  

### 3️⃣ Scaling & Outlier Handling  
- Applied **StandardScaler** and **Min-Max normalization**  
- Capped outliers beyond 3 standard deviations  
- Compared before-after distributions visually  

### 4️⃣ Feature Engineering  
- Created mean and standard deviation features per 5-year group  
- Encoded categorical columns for ML models  

### 5️⃣ Modeling & Validation  
- Built **Linear Regression**, **Random Forest**, and **XGBoost** models  
- Evaluated using **R²**, **MAE**, and **MSE** metrics  
- Used **K-Fold cross-validation** for reliable comparison  
- Plotted **Actual vs Predicted** emissions  

---

## 🧠 Key Insights

- Global agricultural emissions show a **steady upward trend** since 1961.  
- **India, Brazil, China, USA, and Indonesia** are consistently top emitters.  
- **Random Forest** and **XGBoost** captured nonlinear patterns best.  
- Data scaling and outlier capping improved model stability and accuracy.

---

## 🧩 Tech Stack

| Category | Tools |
|-----------|-------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Modeling | Scikit-learn, XGBoost |
| Environment | Jupyter Notebook |

---

## 📊 Model Performance

| Model | R² Score | MAE | MSE | Remarks |
|--------|-----------|------|------|----------|
| Linear Regression | Moderate | Low | Moderate | Baseline linear fit |
| Random Forest | High | Lower | Lower | Best overall |
| XGBoost | High | Low | Low | Robust and stable |

---

## 📁 Repository Structure

📦 from-enteric-fermentation-to-forecasts
├── 📘 Enteric_Fermentation_to_Forecasts.ipynb # Main analysis notebook

├── 📄 README.md # Project documentation

├── 📜 LICENSE # License information

├── 🧹 .gitignore # Ignored files & folders

└── 📂 data/ 
    
  └── FAOSTAT_raw.csv  # Raw FAOSTAT dataset


---

## 🧾 Results Snapshot

- 📈 **Historical patterns** clearly reflect industrialization and livestock growth.  
- 🌍 **Top 5 emitters** dominate over 60% of total emissions.  
- 🧮 **Model forecasts** indicate a continuing upward trend if practices remain unchanged.  

---

## 📬 Author

**Mahir Deep Shah**  
🎓 B.Tech – Computer Science & Engineering  
📚 Minor in Finance, Strategic Management & Economics  
📧 [mahirshah2815@gmail.com](mailto:mahirshah2815@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/mahirshah2815)  

---

⭐ *If you found this notebook useful, consider starring the repo or sharing your feedback!*
