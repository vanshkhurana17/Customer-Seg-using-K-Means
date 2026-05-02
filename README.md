# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project focuses on customer segmentation for a mall using the **K-Means Clustering algorithm**.  
The main objective is to group customers based on their **Annual Income** and **Spending Score** to help businesses 
understand customer behavior and improve targeted marketing strategies.

---

## 📊 Dataset Information
- Dataset contains customer details from a mall
- Key features used:
  - Annual Income (k$)
  - Spending Score (1-100)

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (KMeans)

---

## 🔄 Workflow

### 1. Data Exploration
- Loaded dataset and performed basic checks using `head()`, `info()`, `shape`
- Checked for missing values

### 2. Feature Selection
- Selected only:
  - Annual Income
  - Spending Score  
- These features best represent customer purchasing behavior

### 3. Finding Optimal Clusters
- Used **WCSS (Within Cluster Sum of Squares)**
- Applied **Elbow Method**
- Optimal number of clusters = **5**

### 4. Model Building
- Applied **K-Means Clustering**
- Assigned each customer to a cluster group

### 5. Visualization
- Plotted clusters using scatter plot
- Visualized centroids for each group

---

## 📈 Customer Segments Identified

- **Cluster 1:** Medium income, medium spending customers  
- **Cluster 2:** Low income, high spending customers (impulsive buyers)  
- **Cluster 3:** High income, high spending customers (premium customers)  
- **Cluster 4:** Low income, low spending customers (budget customers)  
- **Cluster 5:** High income, low spending customers (careful spenders)  

---

## 📌 Key Insights
- Customers can be clearly divided into 5 behavioral groups
- High-income high-spending customers are the most valuable segment
- Low-income high-spending customers show impulsive buying behavior
- Low-income low-spending customers contribute least to revenue
- Targeted marketing strategies can be designed for each group

---

## 🚀 Conclusion
This project demonstrates how **unsupervised learning (K-Means clustering)** can be used to understand customer behavior.  
These insights can help businesses design better marketing strategies, improve customer targeting, and increase revenue.

## 💡 Business Recommendations

- Focus marketing on **High Income – High Spending** customers as they are the most valuable segment.
- Offer loyalty programs for **Low Income – High Spending** customers to improve retention.
- Provide discounts and promotions for **Low Income – Low Spending** customers to increase engagement.
- Target **High Income – Low Spending** customers with premium campaigns to increase spending behavior.

---

## 📎 Skills Demonstrated
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- K-Means Clustering  
- Data Visualization  
- Business Insight Generation  
