# 📊 Cereal Dataset - Exploratory Data Analysis (EDA)

This project performs exploratory data analysis on the **Cereal Dataset** from [Kaggle](https://www.kaggle.com/datasets/crawford/80-cereals), which includes nutritional information about 77 cereal brands.

---

## 🔧 Dataset Info

- **Target Variable:** `rating`
- **Categorical Features:** `manufacturer`, `name`
- **Numeric Features:** `calories`, `protein`, `fat`, `sodium`, `fiber`, `carbo`, `sugars`, `potass`, `vitamins`, `weight`, `cups`, `rating`

---

## 📌 EDA Tasks Performed

### ✅ 1. Data Cleaning
- Checked for missing values
- Replaced manufacturer codes (`A`, `G`, `K`, etc.) with full names
- Left `name` column for labeling purposes only (not encoded)

### ✅ 2. Histograms & Boxplots
- Plotted histograms to show distribution of each numeric feature
- Plotted boxplots to identify outliers and spread in each feature

### ✅ 3. Correlation Matrix
- Visualized correlations between numeric features using a heatmap
- Identified which features are most strongly associated with `rating`

### ✅ 4. Categorical Analysis
- Boxplot of `rating` grouped by `manufacturer`
- Bar plot showing average `rating` by manufacturer

### ✅ 5. Top & Bottom Cereals
- Displayed top 5 and bottom 5 cereals based on rating

---

## 📁 Output
- Multiple visualizations (histograms, boxplots, heatmaps)
- Summary tables for best/worst cereals
- Insights into what affects cereal ratings

---

## 🚀 Tools Used
- Python (Pandas, NumPy)
- Seaborn
- Matplotlib

---

## 📌 Conclusion
This EDA helped understand the nutritional factors impacting cereal ratings, and allowed us to visualize trends and outliers in the dataset.

