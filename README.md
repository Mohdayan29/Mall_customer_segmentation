# Customer Segmentation Using K-Means Clustering

📌 Objective
This project aims to develop a customer segmentation model that categorizes customers into distinct groups based on their behavior and preferences. By analyzing purchasing data, these clusters provide valuable insights for the marketing team to craft targeted strategies.

![Customer segmentation](https://github.com/user-attachments/assets/87c0fadd-5b89-4b79-95b6-dcb772cd5686)


## Process:
1. **Loading and Exploring Data:**
   - The dataset is loaded into a Pandas DataFrame.
   - Basic exploratory data analysis is performed, including examining the first five rows, checking the data shape, and reviewing data information for insights.

2. **Data Preprocessing:**
   - Missing values are checked and found to be absent.
   - The relevant columns for clustering (Annual Income and Spending Score) are selected.

3. **Determining Optimal Clusters:**
   - The "Elbow Method" is employed to determine the optimal number of clusters.
   - The Within-Cluster-Sum-of-Squares (WCSS) is plotted against the number of clusters.

4. **Training K-Means Model:**
   - The K-means clustering model is trained with the optimal number of clusters determined from the elbow method.
   - Labels are assigned to each data point based on their respective clusters.

5. **Visualization:**
   - The clustered data points are visualized in a scatter plot.
   - Each cluster is represented by a distinct color, making it easy to discern different customer groups.
   - The plot illustrates the relationship between Annual Income and Spending Score for each customer segment.
     
     ![image](https://github.com/pantakanch/Customer-Segmentation-using-K-Means-Clustering/assets/113978334/2a9ecf1c-d43f-4d13-b133-14d53f896e6c)
