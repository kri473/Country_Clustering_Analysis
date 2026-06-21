
# 🌍 Country Development Clustering Analysis

## 📌 Project Overview

This project applies **Unsupervised Machine Learning** techniques to group countries based on their socio-economic and health indicators. The objective is to identify countries with similar development characteristics and help understand which nations may require greater economic or humanitarian support.

The analysis includes:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Scaling
* K-Means Clustering
* PCA + K-Means Clustering
* Hierarchical Clustering
* Model Evaluation & Comparison
* Cluster Interpretation

---

## 🎯 Objective

The dataset contains various indicators such as:

* Child Mortality
* Exports
* Health Spending
* Imports
* Income
* Inflation
* Life Expectancy
* Fertility Rate
* GDP per Capita

Using these features, countries are grouped into clusters representing different levels of development.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn
* SciPy

---

## 📂 Project Workflow

### 1️⃣ Data Loading

* Imported the country dataset.
* Examined shape, data types, and summary statistics.

### 2️⃣ Data Cleaning

* Checked for missing values.
* Removed duplicate records.
* Applied IQR-based outlier treatment on:

  * Health
  * Life Expectancy
  * Total Fertility

### 3️⃣ Exploratory Data Analysis

Performed:

* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis

Key observations:

* Higher income is generally associated with higher GDP per capita.
* Countries with high child mortality tend to have lower life expectancy.
* Significant variation exists between developed and developing countries.

### 4️⃣ Feature Engineering & Scaling

* Encoded country names for reference.
* Selected numerical features for clustering.
* Applied **StandardScaler** to normalize feature ranges.

### 5️⃣ K-Means Clustering

* Used the Elbow Method.
* Evaluated different values of K.
* Selected the optimal number of clusters.
* Visualized clusters using economic and health indicators.

### 6️⃣ PCA + K-Means

* Reduced dimensionality using Principal Component Analysis (PCA).
* Visualized clusters in 2D space.
* Compared performance against standard K-Means.

### 7️⃣ Hierarchical Clustering

* Built a dendrogram using Ward linkage.
* Created clusters based on hierarchical relationships.

---

## 📊 Model Evaluation

The clustering models were compared using:

| Metric                  | Goal             |
| ----------------------- | ---------------- |
| Silhouette Score        | Higher is Better |
| Davies-Bouldin Index    | Lower is Better  |
| Calinski-Harabasz Score | Higher is Better |

Models compared:

* K-Means
* K-Means + PCA
* Hierarchical Clustering

The best model was selected based on the average ranking across all evaluation metrics.

---

## 🌎 Cluster Interpretation

Clusters were analyzed using average feature values and GDP per capita.

Countries were categorized into development tiers such as:

* Underdeveloped (Needs Most Aid)
* Developing
* Emerging
* Developed

This provides a practical interpretation of the clustering results beyond numerical labels.

---

## 📈 Key Insights

✅ Countries naturally form distinct development groups based on economic and health indicators.

✅ Income and GDP per capita are among the strongest differentiators between clusters.

✅ Child mortality and life expectancy show strong inverse relationships.

✅ Clustering can help organizations identify regions requiring additional support and investment.

---

## 🚀 Future Improvements

* Experiment with DBSCAN and Gaussian Mixture Models.
* Perform feature selection using correlation analysis.
* Build an interactive dashboard using Streamlit or Power BI.
* Incorporate additional socio-economic indicators.

---

## 👨‍💻 Author

**Krishna Kumar**

📧 [krishnakumar.tech7889i@gmail.com](mailto:krishnakumar.tech7889i@gmail.com)

🔗 LinkedIn: [https://www.linkedin.com/in/krishna-sharma-130527321](https://www.linkedin.com/in/krishna-sharma-130527321)

🔗 GitHub: [https://github.com/kri473](https://github.com/kri473)

---

⭐ If you found this project useful, consider giving it a star on GitHub.
