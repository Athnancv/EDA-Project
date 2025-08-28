# 🏬 Retail Superstore EDA: Uncovering Sales, Profit & Discount Dynamics

---

## 🎯 Objective

Explore and analyze retail transactional data to understand **what drives profitability**, how **discounting impacts margins**, and where **sales opportunities** lie across products, customers, and regions.

---

## 📊 Data

- **Source**: Superstore sales dataset  
- **Records**: ~10,000 orders (multi-year coverage)  
- **Features**: 21 (Sales, Profit, Discount, Quantity, Category, Sub-Category, Segment, Region, Dates…)  
- **Target engineered**: **Profitable (1) vs. Loss (0)**  

---

## 🧪 Approach

### Data Preparation
- Parsed Order & Ship Dates, created monthly aggregates  
- Engineered profitability flag (Profit > 0)  
- Cleaned outliers & inconsistencies  

### Exploratory Analysis
- **Univariate:** Histograms, KDE, and box/violin plots for Sales, Quantity, and Profit  
- **Bivariate:** Scatterplots (Sales ↔ Profit, Discount ↔ Profit), pairplots for `['Profit','Sales','Discount']`  
- **Multivariate:** Correlation heatmap to surface feature interdependencies  

### Segmentation Views
- Profitability by **Category, Sub-Category, Segment, and Region**  
- Monthly trend analysis to reveal seasonal patterns  

### Statistical Insight
- Modeled probability of profit using **Bernoulli distribution** on engineered flag  

---

## 📈 Key Insights

- 📉 High discounts strongly erode profit—especially in **Furniture and Technology**  
- 💰 **Office Supplies** contributes steady, profitable sales with low volatility  
- 🌎 Regional disparities: **West region** outperforms, **South** lags in margins  
- 🗓 Monthly sales show **seasonal demand peaks**—timing promotions is crucial  

---

## 🔍 What Stood Out

- ⚖️ **Discount vs Profit Trade-off**: Aggressive discounting often flips profitable orders into losses  
- 🧩 **Category mix matters**: Office Supplies sustains margins, Furniture drags performance  
- 📊 **Visual storytelling**: 9+ curated plots translate raw numbers into executive-ready insights  

---

## 🖼 Visuals & Features

- Correlation heatmap for numeric drivers  
- Category/Sub-Category/Region barplots  
- Discount–Profit scatter & violin plots  
- Monthly resampled sales time series  
- Probability distribution of profitability  

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- SciPy  
- Jupyter Notebook  
