Mall Customers Clustering (K-Means)
📌 Project Overview

This project applies K-Means clustering to the Mall Customers dataset (from Kaggle) to segment customers based on their income and spending behavior.
The goal is to help businesses identify distinct customer groups for targeted marketing strategies.

📂 Dataset

Source: Mall Customers Dataset - Kaggle

Features Used:

CustomerID – Unique identifier for customers

Gender – Male / Female

Age – Customer age (not used in final clustering here)

Annual Income (k$) – Customer’s yearly income

Spending Score (1-100) – Score assigned by the mall based on spending habits

⚙️ Steps in the Project

Exploratory Data Analysis (EDA)

Distribution of Gender, Age, Income, and Spending Score

Scatter plots (e.g., Annual Income vs Spending Score)

Heatmaps / correlation check

Feature Selection

Focused on Annual Income (k$) and Spending Score (1-100)

(Optional: Could extend with Age or other features)

Clustering with K-Means

Used Elbow Method to determine the optimal number of clusters

Applied K-Means clustering

Visualized customer segments with scatterplots

Cluster Insights

Group 1: High Income – High Spending (Premium Customers)

Group 2: Low Income – High Spending (Value Seekers)

Group 3: High Income – Low Spending (Conservative Customers)

Group 4: Low Income – Low Spending (Minimal Shoppers)

Group 5: Medium Income – Medium Spending (Average Customers)

📊 Visualizations

Gender distribution bar chart

Age, Income, Spending histograms

Scatterplot: Annual Income vs Spending Score (with clusters highlighted)

Elbow curve for choosing optimal k

🚀 How to Run

Clone this repo

git clone <your-repo-link>
cd mall-customers-clustering


Install dependencies

pip install -r requirements.txt


Run the notebook

jupyter notebook Mall_Customers_Clustering.ipynb

📌 Requirements

Python 3.x

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, jupyter

📈 Future Work

Include Age for 3D clustering

Try other algorithms (DBSCAN, Hierarchical Clustering)

Build an interactive dashboard with Streamlit / Flask

✨ Acknowledgments

Dataset: Kaggle – Mall Customers Dataset

👉 This makes your README clear, professional, and resume/portfolio-friendly.

Would you like me to also generate the README.md file directly with proper markdown so you can just copy-paste into your repo?
