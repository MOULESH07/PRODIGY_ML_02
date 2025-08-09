# PRODIGY_ML_02 - Customer Segmentation using K-Means

## 📌 Overview
This project uses **K-Means clustering** to segment customers based on their **Annual Income** and **Spending Score**.  
It helps businesses understand customer groups for targeted marketing.

## 📂 Dataset
- Dataset: [Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- Columns used:  
  - Annual Income (k$)  
  - Spending Score (1-100)  

 Steps
1. Load and explore dataset.
2. Select relevant features.
3. Scale the features for better clustering.
4. Find the optimal number of clusters using the **Elbow Method**.
5. Apply K-Means clustering.
6. Visualize the customer segments.

 Output
- **Elbow Method Graph** to find optimal clusters.
- **Scatter Plot** showing the different customer segments.
- **Customer_Segments.csv** with cluster labels.

## 📦 Dependencies

pip install pandas numpy matplotlib seaborn scikit-learn
▶ How to Run

python kmeans_customer_segmentation.py
