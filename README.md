# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project performs customer segmentation using the K-Means Clustering algorithm on the Mall Customers dataset. The goal is to group customers based on their annual income and spending behavior, helping businesses understand different customer categories for targeted marketing strategies.

## 🎯 Objectives

* Analyze customer purchasing behavior.
* Apply K-Means clustering for customer segmentation.
* Determine the optimal number of clusters using the Elbow Method.
* Visualize customer groups for better business insights.

## 📂 Dataset

Dataset Used: **Mall_Customers.csv**

Features used for clustering:

* Annual Income (k$)
* Spending Score (1-100)

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

## 📋 Project Workflow

### 1. Data Loading

The dataset is loaded using Pandas.

### 2. Feature Selection

The following features are selected:

* Annual Income (k$)
* Spending Score (1-100)

### 3. Data Scaling

StandardScaler is used to normalize the data before clustering.

### 4. Finding Optimal Clusters

The Elbow Method is applied to identify the best value of K.

### 5. K-Means Clustering

K-Means algorithm is applied with 5 clusters.

### 6. Visualization

Customer segments are visualized using a scatter plot.

## 📊 Output

* Elbow Method Graph
* Customer Segmentation Scatter Plot
* Cluster labels added to the dataset

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/customer-segmentation.git
```

2. Install required libraries:

```bash
pip install pandas matplotlib scikit-learn
```

3. Run the Python file:

```bash
python main.py
```

## 📈 Business Benefits

* Identifies high-value customers.
* Helps create personalized marketing campaigns.
* Improves customer retention strategies.
* Supports data-driven business decisions.

## 👨‍💻 Author

Mohd Aftab Khan

## 📜 License

This project is created for learning and educational purposes.
