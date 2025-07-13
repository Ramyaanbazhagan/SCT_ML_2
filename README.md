# 🛍️ Task 2 – Customer Segmentation using K-Means Clustering

As part of my internship at **SkillCraft Technology**, I completed a machine learning task on **unsupervised clustering** using the **Mall Customers** dataset.

## 🎯 Objective
To segment mall customers into distinct groups based on their:
- 🧮 Annual Income
- 💳 Spending Score

This helps businesses better understand customer behavior and target marketing strategies effectively.

---

## 🗂 Dataset
- 📁 `Mall_Customers.csv`
- 📊 200 records | 5 features: CustomerID, Gender, Age, Annual Income, Spending Score

---

## 🔧 Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

---

## 📈 Steps Performed

1. **Unzipped and loaded** the dataset
2. **Cleaned** column names and checked for missing values
3. **Selected features**: `Annual Income`, `Spending Score`
4. **Standardized** data using `StandardScaler`
5. **Used Elbow Method** to determine optimal number of clusters (K=5)
6. **Trained KMeans model**
7. **Assigned clusters** to each customer
8. **Visualized** clusters using scatter plots
9. **Analyzed** average `Age`, `Income`, and `Spending Score` in each cluster

---

## 📊 Output Summary

| Cluster | Avg Age | Avg Income (k$) | Avg Spending Score |
|---------|---------|-----------------|---------------------|
| 0       | 42.7    | 55.3            | 49.5                |
| 1       | 32.7    | 86.5            | 82.1                |
| 2       | 25.3    | 25.7            | 79.4                |
| 3       | 41.1    | 88.2            | 17.1                |
| 4       | 45.2    | 26.3            | 20.9                |

---

## 🧠 Insights Gained

- ✅ How unsupervised learning groups customers based on patterns
- ✅ Used Elbow Method to determine optimal K
- ✅ Learned to scale features for better distance calculation
- ✅ Interpreted cluster behavior and visualized segments
- ✅ Practical application of ML in retail and marketing

---

## 📎 Folder Contents

- `Task2_KMeans_MallCustomers.ipynb` – Full notebook
- `archive.zip` – Contains Mall_Customers.csv
- `README.md` – You're reading it!

---

## ✅ Output Visualizations

- 📈 **Elbow Curve**: Showed K=5 as optimal
- 🎯 **Scatterplot of Segments**:
  - Clear segmentation of high-income, high-spending vs low-spending groups
  - Clusters visually interpretable and business-meaningful

---



