#  Credit Card Customer Segmentation using Machine Learning

## 📌 Project Overview

This project applies **unsupervised machine learning** techniques to segment credit card customers based on their demographics and spending behavior. The objective is to identify distinct customer groups that enable financial institutions to deliver personalized marketing campaigns, improve customer retention, optimize credit offerings, and maximize profitability.

---

## 🎯 Objective

The primary goals of this project are to:

* Analyze customer demographic and spending patterns.
* Compare multiple clustering algorithms to identify the most effective segmentation technique.
* Discover meaningful customer segments based on behavioral characteristics.
* Provide actionable business recommendations for each customer segment.
* Support data-driven marketing and customer relationship strategies.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **K-Means Clustering**
* **DBSCAN**
* **Hierarchical Clustering**
* **Principal Component Analysis (PCA)**

---

## 📊 Methodology

### 1. Data Preprocessing

* Cleaned missing and inconsistent values.
* Scaled numerical features using StandardScaler.
* Performed exploratory data analysis (EDA) to understand customer behavior.
* Reduced dimensionality using PCA for visualization.

### 2. Model Comparison

Three clustering algorithms were evaluated:

* **K-Means**
* **DBSCAN**
* **Hierarchical Clustering (Agglomerative)**

The models were compared using the **Silhouette Score**, which measures how well-separated and cohesive the clusters are.

**Result:**

* **K-Means achieved the highest Silhouette Score**, indicating the most distinct and well-defined customer segments.
* Therefore, **K-Means was selected as the final clustering model** for customer segmentation.

---

## 👥 Customer Segments Identified

### 1. High-Value Customers

**Characteristics**

* High spending
* High credit limit
* Frequent card usage

**Business Recommendations**

* Offer premium credit cards.
* Increase credit limits based on spending behavior.
* Introduce exclusive rewards and loyalty programs.
* Provide investment and wealth management services.

---

### 2. Moderate-Value Customers

**Characteristics**

* Stable income
* Moderate spending habits
* Consistent card usage

**Business Recommendations**

* Introduce cashback and milestone-based rewards.
* Promote EMI and installment plans.
* Cross-sell loans and insurance products.
* Encourage higher spending through personalized campaigns.

---

### 3. Low-Engagement Customers

**Characteristics**

* Low spending
* Infrequent transactions
* Limited card utilization

**Business Recommendations**

* Launch personalized promotional campaigns.
* Provide financial education and spending insights.
* Introduce entry-level rewards to increase engagement.
* Encourage regular card usage through targeted incentives.

---

### 4. High Credit Utilization Customers

**Characteristics**

* High credit utilization
* Increased repayment risk

**Business Recommendations**

* Monitor repayment behavior proactively.
* Offer balance transfer and repayment assistance programs.
* Send personalized budgeting alerts and spending recommendations.
* Implement early risk management strategies.

---

##  Business Impact

This project helps financial institutions:

* Segment customers using machine learning.
* Compare clustering models using quantitative evaluation metrics.
* Improve customer targeting through personalized marketing.
* Increase customer retention and engagement.
* Optimize credit card offerings based on customer behavior.
* Support strategic business decisions with data-driven insights.

---

##  Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Feature Scaling
        │
        ▼
PCA for Visualization
        │
        ▼
Model Training
(K-Means | DBSCAN | Hierarchical)
        │
        ▼
Silhouette Score Comparison
        │
        ▼
Best Model Selection (K-Means)
        │
        ▼
Customer Segmentation
        │
        ▼
Business Recommendations
```

---

##  Key Takeaways

* Compared **three clustering algorithms** for customer segmentation.
* Used the **Silhouette Score** to objectively evaluate clustering performance.
* Identified **four actionable customer segments**.
* Developed business strategies tailored to each customer group.
* Demonstrated how machine learning can support marketing, customer retention, and revenue optimization in the banking and financial services sector.

---

##  Future Improvements

* Deploy the segmentation model as an interactive web application using Streamlit.
* Incorporate transaction history and temporal spending patterns.
* Automate customer segmentation for real-time analysis.
* Experiment with advanced clustering techniques such as Gaussian Mixture Models and HDBSCAN.
* Build personalized recommendation systems based on customer segments.
