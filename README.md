# 🧠 Customer Segmentation using Unsupervised Learning

This project involves analyzing marketing data to segment customers based on their demographic and behavioral characteristics. The aim is to identify distinct customer groups for better-targeted marketing strategies.

---

## 📂 Dataset
- `marketing_campaign.csv` — includes demographic and purchase information.
- Delimiter used: `;`

---

## 🛠️ Key Steps

1. **Data Loading & Cleaning**
   - Null value treatment
   - Feature engineering
   - Data type conversion

2. **Exploratory Data Analysis (EDA)**
   - Univariate & Multivariate analysis
   - Categorical & numerical feature exploration
   - Heatmaps, pairplots, and distributions

3. **Feature Scaling**
   - Used `StandardScaler` or `MinMaxScaler` for normalization

4. **Clustering Techniques**
   - ✅ K-Means Clustering with Elbow Method & Silhouette Score
   - ✅ PCA for dimensionality reduction (if applicable)
   - ✅ Hierarchical clustering and dendrograms (if included)

5. **Customer Profiling**
   - Interpretation of clusters
   - Insights for marketing actions

---

## 📈 Sample Visuals
*(Included screenshots of pairplots, heatmaps, elbow curves, or cluster visualizations)*

---

## 🔍 Insights & Observations
- Cluster 0: High income, high spenders
- Cluster 1: Young professionals with moderate spending
- Cluster 2: Low engagement, low spending

*(Adjust based on your actual cluster analysis)*

---

## 🚀 Future Improvements
- Deploy as an interactive dashboard using Streamlit or Flask
- Include demographic segmentation per region/country
- Use DBSCAN or Gaussian Mixture Models for comparison

---

## 📎 Requirements
```bash
pandas
numpy
seaborn
matplotlib
sklearn
scipy
