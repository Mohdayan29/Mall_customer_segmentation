# Customer Segmentation Using K-Means Clustering

📌 Objective
This project aims to develop a customer segmentation model that categorizes customers into distinct groups based on their behavior and preferences. By analyzing purchasing data, these clusters provide valuable insights for the marketing team to craft targeted strategies.

![Customer segmentation](https://github.com/user-attachments/assets/87c0fadd-5b89-4b79-95b6-dcb772cd5686)

### What is Customer Segmentation
Customer Segmentation is the process of division of customer base into several groups of individuals that share a similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.<br>

Companies that deploy customer segmentation are under the notion that every customer has different requirements and require a specific marketing effort to address them appropriately. Companies aim to gain a deeper approach of the customer they are targeting. Therefore, their aim has to be specific and should be tailored to address the requirements of each and every individual customer. Furthermore, through the data collected, companies can gain a deeper understanding of customer preferences as well as the requirements for discovering valuable segments that would reap them maximum profit. This way, they can strategize their marketing techniques more efficiently and minimize the possibility of risk to their investment.<br>

The technique of customer segmentation is dependent on several key differentiators that divide customers into groups to be targeted. Data related to demographics, geography, economic status as well as behavioral patterns play a crucial role in determining the company direction towards addressing the various segments<br>
### What is K-Means Algorithm
While using the k-means clustering algorithm, the first step is to indicate the number of clusters (k) that we wish to produce in the final output. The algorithm starts by selecting k objects from dataset randomly that will serve as the initial centers for our clusters. These selected objects are the cluster means, also known as centroids. Then, the remaining objects have an assignment of the closest centroid. This centroid is defined by the Euclidean Distance present between the object and the cluster mean. We refer to this step as “cluster assignment”. When the assignment is complete, the algorithm proceeds to calculate new mean value of each cluster present in the data. After the recalculation of the centers, the observations are checked if they are closer to a different cluster. Using the updated cluster mean, the objects undergo reassignment. This goes on repeatedly through several iterations until the cluster assignments stop altering. The clusters that are present in the current iteration are the same as the ones obtained in the previous iteration.<br>


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
