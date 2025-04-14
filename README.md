[Customer Segmentation Project](https://github.com/KoreJosh/Customer-Segmentation-Cluster):


# 🛍️ Customer Segmentation Using Clustering

Welcome to the **Customer Segmentation** project! This repository contains a machine learning project that applies **unsupervised learning** to group mall customers into distinct clusters based on their **Spending Score**, **Annual Income**, and **Age**. The goal is to help mall management and marketers better understand their customer base and tailor strategies to different customer segments.

## 🚀 Project Overview

### 🎯 Objective

The primary goal of this project is to:
- Identify patterns in customer behavior using key features.
- Segment customers into distinct groups using clustering algorithms.
- Support **personalized marketing**, **improved customer engagement**, and **efficient resource allocation** for mall management.

### 🧩 Problem Statement (Pain Point)

Retail malls often struggle with generic marketing and poorly targeted promotional strategies due to limited insights into customer diversity. Without segmentation, malls:
- Waste resources marketing to disinterested customers.
- Fail to identify and retain valuable shoppers.
- Miss chances to optimize customer experience based on age, income, and spending habits.

This project solves that by applying **K-Means Clustering** to group customers into meaningful segments using spending score, income, and age.

---

## 📊 Features Used

| Feature         | Description                              |
|----------------|------------------------------------------|
| **Age**         | Age of the customer                      |
| **Annual Income** | Income of the customer (in thousands)   |
| **Spending Score** | Score assigned by the mall based on spending behavior (1-100) |

---

## 🧠 Machine Learning Techniques

- **Unsupervised Learning**
  - K-Means Clustering
- **Preprocessing**
  - Feature Scaling
- **Evaluation**
  - Elbow Method for optimal cluster selection
- **Visualization**
  - 2D and 3D Cluster Plots
  - Pairplots and Heatmaps for feature relationships

---

## 🧪 Project Workflow

1. **Data Exploration**
   - Loaded and cleaned the dataset.
   - Visualized distributions and feature relationships.

2. **Preprocessing**
   - Feature selection and standardization.

3. **Modeling**
   - Applied K-Means clustering.
   - Used Elbow Method to determine optimal number of clusters.

4. **Visualization**
   - Plotted clusters in 2D and 3D for interpretation.

5. **Insights**
   - Segmented customers into groups such as:
     - **High income, high spenders**
     - **Young, low income, moderate spenders**
     - **Older, budget-conscious shoppers**
     - And more...

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- Libraries:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`, `plotly`
  - `sklearn`

---

## 📁 Repository Structure

```
Customer-Segmentation-Cluster/
│
├── Customer_Segmentation_Clustering.ipynb  # Main Jupyter notebook
├── mall_customers.csv                      # Dataset used
├── README.md                               # Project overview
└── assets/                                 # Optional folder for visual outputs
```

---

## 📌 Key Insights

- Customers are not homogenous: Age, income, and spending behaviors vary greatly.
- Clustering helps identify high-value and low-engagement customer groups.
- These insights support **data-driven decisions** in marketing, product placement, and customer service personalization.

---

## 📈 Potential Business Applications

- Targeted email and SMS campaigns for each cluster.
- Personalized discounting and loyalty programs.
- Inventory and layout optimization based on customer behavior.

---

## 🔮 Future Improvements

- Incorporate more features like gender, purchase frequency, product preferences.
- Apply hierarchical clustering or DBSCAN for comparison.
- Integrate with a dashboard using Streamlit or Dash.

---

## 📎 Dataset

The dataset is publicly available and included in this repo: `mall_customers.csv`

---

## 🤝 Contributions

Feel free to fork this repo, improve the analysis, or add new clustering approaches!

---

## 📬 Contact

Made with ❤️ by [@KoreJosh](https://github.com/KoreJosh)  
For inquiries or collaborations, reach out via GitHub or drop a message!

