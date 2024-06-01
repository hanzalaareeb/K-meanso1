# K-means Clustering Project

## Overview
This project demonstrates the application of K-means clustering algorithm on customer data to segment customers based on their annual income and spending score.

## Dataset
The dataset used in this project is `Mall_Customers.csv`, which contains the following columns:
- `CustomerID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Project Structure
- `Kmean.ipynb`: Jupyter Notebook containing the code for data preprocessing, K-means clustering, and visualization.
- `Mall_Customers.csv`: The dataset used for clustering.

## Libraries Used
- `numpy`
- `matplotlib`
- `seaborn`
- `pandas`
- `sklearn`

## Steps
1. **Data Loading and Exploration**:
    - Load the dataset using pandas.
    - Display the first few rows to understand the structure of the dataset.
    - Check for missing values and data types.

2. **Data Preprocessing**:
    - Extract relevant features (Annual Income and Spending Score) for clustering.
    
3. **K-means Clustering**:
    - Apply the K-means algorithm with different numbers of clusters (1 to 10).
    - Use the Elbow Method to determine the optimal number of clusters by plotting Within-Cluster Sum of Squares (WCSS).

4. **Visualization**:
    - Visualize the clusters and their centroids on a 2D plot.

## Results
The optimal number of clusters was determined using the Elbow Method. The final plot shows the segmentation of customers into different clusters based on their annual income and spending score.

## Usage
1. Ensure all the required libraries are installed:
    ```bash
    pip install numpy matplotlib seaborn pandas scikit-learn
    ```
2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Kmean.ipynb
    ```

## References
- [K-means Clustering Algorithm](https://en.wikipedia.org/wiki/K-means_clustering)
- [Elbow Method for Optimal Clusters](https://en.wikipedia.org/wiki/Determining_the_number_of_clusters_in_a_data_set#The_Elbow_Method)

