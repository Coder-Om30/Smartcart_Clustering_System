# 🛒 Smart Cart Customer Clustering System

> Machine Learning project that analyzes shopping behavior and groups customers into meaningful segments using unsupervised learning.

---

## 📌 Overview

Retail stores collect huge amounts of purchase data but rarely use it effectively.
This project builds a **Customer Segmentation Engine** that helps businesses:

* Understand different types of customers
* Improve product recommendations
* Optimize marketing campaigns
* Increase revenue using data‑driven decisions

The system uses **clustering algorithms** to automatically group customers based on their shopping patterns.

---

## 🚀 Features

* Data Cleaning & Pre‑processing
* Feature Engineering
* Outlier Detection & Handling
* PCA Dimensionality Reduction
* Optimal K detection (Elbow + Silhouette)
* Multiple Clustering Algorithms

  * K‑Means
  * Agglomerative Clustering
* Visualization of Customer Segments
* Interpretable Business Insights

---

## 🧠 ML Workflow

```
Raw Dataset → Cleaning → Encoding → Scaling → PCA → Clustering → Customer Segments → Insights
```

---

## 🛠️ Tech Stack

| Category      | Tools                           |
| ------------- | ------------------------------- |
| Language      | Python                          |
| Libraries     | Pandas, NumPy                   |
| Visualization | Matplotlib, Seaborn             |
| ML            | Scikit‑Learn                    |
| Algorithms    | KMeans, Hierarchical Clustering |
| Evaluation    | Silhouette Score, Elbow Method  |

---

## 📊 How It Works

### 1️⃣ Data Preprocessing

* Handle missing values
* Remove irrelevant columns
* Encode categorical features
* Scale numerical features

### 2️⃣ Dimensionality Reduction

PCA reduces high dimensional data to 2D space for visualization and faster clustering.

### 3️⃣ Finding Optimal Clusters

* **Elbow Method** → Detect inertia change
* **Silhouette Score** → Measure cluster separation

### 4️⃣ Customer Segmentation

Customers are grouped into clusters such as:

* High Spenders
* Budget Buyers
* Frequent Visitors
* Occasional Customers

---

## 📈 Output Example

Each customer gets a cluster label:

```
Customer_ID  →  Cluster 2 (Premium Customer)
Customer_ID  →  Cluster 0 (Discount Seeker)
```

Businesses can use this for personalized offers & targeted marketing.

---

## ▶️ Run Locally

```bash
# Clone repo
git clone https://github.com/your-username/smart-cart-clustering.git
cd smart-cart-clustering

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
```

---

## 📷 Visualizations Included

* Correlation Heatmap
* PCA Projection Plot
* Elbow Curve
* Silhouette Score Graph
* Cluster Scatter Plot

---

## 💡 Business Applications

* Personalized Discounts
* Product Recommendation Systems
* Customer Retention Strategy
* Store Layout Optimization
* Inventory Planning

---

## 👨‍💻 Author

**Om Sahu**
Computer Science Engineering Student
Machine Learning Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
