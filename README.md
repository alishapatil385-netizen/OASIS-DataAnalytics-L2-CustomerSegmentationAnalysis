# OIBSIP-DataAnalytics-L2-CustomerSegmentationAnalysis
# Customer Segmentation Analysis using K-Means Clustering

## 📌 Project Overview

This project focuses on customer segmentation for an e-commerce business using **RFM (Recency, Frequency, Monetary) Analysis** and **K-Means Clustering**. The objective is to group customers based on their purchasing behavior, helping businesses create personalized marketing strategies and improve customer retention.


## 🎯 Objective

* Analyze customer purchasing behavior.
* Perform RFM analysis.
* Apply K-Means clustering to identify customer segments.
* Visualize customer groups.
* Recommend marketing strategies for each customer segment.

---

## 📂 Dataset

* **Dataset:** Online Retail Dataset
* **Domain:** E-Commerce
* **Records:** Customer transaction data
* **Features Used:**

  * CustomerID
  * InvoiceDate
  * InvoiceNo
  * Quantity
  * UnitPrice

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Project Workflow

1. Load and inspect the dataset.
2. Perform data cleaning and handle missing values.
3. Create the RFM (Recency, Frequency, Monetary) features.
4. Perform exploratory data analysis (EDA).
5. Standardize the selected features using StandardScaler.
6. Determine the optimal number of clusters using the Elbow Method.
7. Apply K-Means Clustering.
8. Visualize customer segments.
9. Profile each cluster.
10. Recommend marketing strategies.

---

## 📈 Exploratory Data Analysis (EDA)

The dataset was analyzed to understand customer purchasing patterns by:

* Checking missing values
* Removing invalid records
* Calculating descriptive statistics
* Creating RFM features
* Visualizing customer behavior

---

## 🤖 Machine Learning Technique

**Algorithm Used:** K-Means Clustering

The Elbow Method was used to determine the optimal number of clusters before training the K-Means model.


## 📊 Visualizations

* Elbow Method
* Frequency vs Monetary Scatter Plot
* Recency vs Monetary Scatter Plot
* Customers per Cluster Bar Chart


## 👥 Customer Segments

Example customer groups identified:

| Cluster | Customer Type        | Marketing Strategy                       |
| ------- | -------------------- | ---------------------------------------- |
| 0       | Loyal Customers      | Loyalty Rewards & Membership             |
| 1       | High-Value Customers | Premium Offers & VIP Benefits            |
| 2       | At-Risk Customers    | Win-Back Campaigns & Discount Coupons    |
| 3       | New Customers        | Welcome Offers & Product Recommendations |

---

## 📌 Key Insights

* High-value customers contribute significantly to overall revenue.
* Loyal customers should be retained through exclusive rewards.
* At-risk customers require re-engagement campaigns.
* New customers can be converted into loyal customers using personalized offers.


## 🚀 Future Improvements

* Use DBSCAN or Hierarchical Clustering for comparison.
* Build an interactive dashboard using Power BI or Tableau.
* Deploy the model as a web application.
* Perform real-time customer segmentation.


## 📚 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* RFM Analysis
* Data Standardization
* K-Means Clustering
* Data Visualization
* Customer Profiling
* Marketing Insights



## ⭐ Conclusion

This project demonstrates how customer segmentation can help businesses understand customer behavior and create targeted marketing strategies. Using RFM analysis and K-Means clustering, meaningful customer groups were identified to support better business decision-making.
