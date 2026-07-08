# Customer Segmentation with K-Means Clustering & Pareto Analysis
This project demonstrates an **end-to-end customer segmentation workflow** using **K-Means clustering**, an unsupervised machine learning algorithm, to identify natural groups of customers based on purchasing behavior. By analyzing key metrics such as **Total Sales, Order Count, and Average Order Value**, the model uncovers meaningful customer segments that can support targeted marketing strategies and customer relationship management.

To complement the clustering analysis, the project applies **Pareto Analysis (80/20 Rule)** to determine which customer segments contribute the largest share of total revenue. Combining **machine learning with business analytics** transforms raw customer transaction data into actionable insights, enabling organizations to prioritize high-value customers, optimize marketing efforts, and make more informed, data-driven decisions.

# Project Workflow
## 1. Load the Data
The project begins by importing customer transaction data (http://archive.ics.uci.edu/ml/datasets/online+retail) into Python using Pandas.

## 2. Data Cleaning
Before building the machine learning model, the dataset is cleaned to ensure high-quality input.
Cleaning steps include:
- Filtering irrelevant and incomplete records
- Preparing customer-level features
- Aggregating transactional data
- Normalizing numerical variables
Proper preprocessing improves clustering performance and ensures that no single feature dominates the model due to scale differences.

## 3. K-Means Clustering Model
After data preprocessing, the customer data is grouped using the K-Means clustering algorithm. Multiple cluster configurations are evaluated to determine the **optimal number of clusters (K)**.
The best clustering structure is selected based on the **Silhouette Score**, which measures cluster separation and overall quality.

## 4. Pareto Analysis
Pareto Analysis is applied to customer segments by visualizing **Total Sales and Cumulative Percentage of Sales Contribution** across clusters to identify the segments with the greatest impact on overall sales.

## 5. Technologies Used
| Category                | Libraries        |
| ----------------------- | ---------------- |
| Programming Language    | Python           |
| Data Manipulation       | Pandas, NumPy    |
| Machine Learning        | Scikit-learn     |
| Data Visualization      | Matplotlib       |
| Statistical Evaluation  | Silhouette Score |
| Development Environment | Jupyter Notebook |

## 6. Results & Insights
The combination of K-Means clustering and Pareto Analysis provides actionable insights for customer targeting, retention strategies, and data-driven decision-making.
