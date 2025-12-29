# Customer-Segmentation-Using-Unsupervised-Learning

## Objective

Segment mall customers using K-Means Clustering and analyze spending behavior to support data-driven marketing decisions.

---

## Approach

### 1. Data Loading

* Imported libraries: pandas, numpy, matplotlib, seaborn, sklearn.
* Loaded the dataset (Mall_Customers.csv) into a DataFrame.
* Viewed dataset shape and first few rows to understand structure.

---

### 2. Data Exploration & Preprocessing

* Checked columns, data types, and missing values.

* Focused on key numerical features:

  * Age
  * Annual Income (k$)
  * Spending Score (1–100)

* Scaled numerical features to ensure fair comparison in clustering.

---

### 3. Clustering (K-Means)

* Applied **K-Means algorithm**.
* Selected **k = 4 clusters** based on typical segmentation behavior.
* Assigned each customer to a cluster (segment).

---

### 4. Dimensionality Reduction & Visualization

* Applied **PCA** to reduce features to 2 components.
* Visualized clusters on a scatter plot to see separation and patterns.

---

## Results & Insights

The clustering revealed four meaningful customer segments:

* **High income — high spending**
* **High income — low spending**
* **Low income — high spending**
* **Low income — low spending**

These insights help design targeted strategies such as loyalty programs, discounts, bundles, and awareness campaigns.

---

### Possible Improvements

Model and insights can be enhanced by:

* Adding more behavioral features (visits, product categories, purchase frequency)
* Trying different clustering algorithms (Hierarchical, DBSCAN)
* Using t-SNE for deeper visualization analysis

