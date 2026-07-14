# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project performs customer segmentation using the K-Means Clustering algorithm on the Mall Customers dataset. The objective is to group customers with similar purchasing behavior so that businesses can better understand their customers and create targeted marketing strategies.

## 📂 Dataset
The project uses the **Mall Customers Dataset**, which contains the following features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

For clustering, the following features were used:

- Annual Income (k$)
- Spending Score (1-100)

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Project Workflow

1. Import required libraries.
2. Load and explore the dataset.
3. Check for missing values.
4. Select relevant features for clustering.
5. Apply feature scaling using StandardScaler.
6. Use the Elbow Method to determine the optimal number of clusters.
7. Train the K-Means clustering model.
8. Assign cluster labels to customers.
9. Visualize customer segments and centroids.

## 📈 Customer Segments

The customers were divided into five segments:

- **Cluster 0:** Moderate Income, Moderate Spending → Regular Customers
- **Cluster 1:** High Income, High Spending → Premium Customers
- **Cluster 2:** Low Income, High Spending → Promotional Shoppers
- **Cluster 3:** High Income, Low Spending → Careful Customers
- **Cluster 4:** Low Income, Low Spending → Budget Customers

## 🎯 Results

The K-Means algorithm successfully grouped customers into distinct segments based on their annual income and spending score. These insights can help businesses improve customer targeting, personalized marketing, and business decision-making.

