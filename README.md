

##  Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Mall Customers dataset** to understand customer behavior. The dataset contains customer demographic and spending information. By analyzing variables such as **Annual Income** and **Spending Score**, we aim to identify potential customer segments that can help in targeted marketing strategies.

---

##  Dataset

* **Source**: Public Kaggle dataset – *Mall Customers*
* **Columns**:

  * `CustomerID` → Unique ID for each customer
  * `Gender` → Male/Female
  * `Age` → Age of the customer
  * `Annual Income (k$)` → Annual income in thousand dollars
  * `Spending Score (1-100)` → Score assigned by the mall based on customer behavior & spending nature

---

##  Exploratory Data Analysis (EDA)

* Checked dataset info and null values
* Explored distributions of categorical & numerical features
* Visualized relationships between:

  * Gender distribution
  * Age vs Spending Score
  * Annual Income vs Spending Score
  * Correlation heatmap
* Identified **clusters of customers** based on spending and income

Example Visualization:

```python
sns.scatterplot(data=mall_df, x='Annual Income (k$)', y='Spending Score (1-100)', hue='Gender')
```

---

##  Key Insights

* Male and female customers are **almost equally represented**.
* Spending behavior shows **clear clusters**, especially when plotting **Annual Income vs Spending Score**.
* Age was not considered in this analysis, but it can provide additional segmentation opportunities.
* Customers with **moderate income and high spending scores** are likely the most valuable group for marketing.

---

##  Next Steps

* Apply **Clustering (KMeans)** to form customer segments.
* Explore **Age-based patterns** to refine segmentation.
* Build recommendations for **targeted marketing campaigns**.

---

##  Tech Stack

* Python 🐍
* Pandas, NumPy (data handling)
* Matplotlib, Seaborn (visualization)
* Jupyter Notebook

---

##  Project Structure

```
📦 mall-customers-analysis
 ┣ 📜 Mall_Customers.csv
 ┣ 📜 Mall_Customers_EDA.ipynb
 ┣ 📜 README.md
```




