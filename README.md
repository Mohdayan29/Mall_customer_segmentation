# Customer Segmentation Using K-Means Clustering

📌 Objective
This project aims to develop a customer segmentation model that categorizes customers into distinct groups based on their behavior and preferences. By analyzing purchasing data, these clusters provide valuable insights for the marketing team to craft targeted strategies.

![Customer segmentation](https://github.com/user-attachments/assets/87c0fadd-5b89-4b79-95b6-dcb772cd5686)


What is Customer Segmentation?

Customer segmentation is dividing a customer base into distinct groups based on shared characteristics relevant to marketing, such as gender, age, interests, and spending habits. This approach allows companies to tailor their marketing strategies to meet the specific needs of each group.

By implementing customer segmentation, companies recognize that each customer has unique requirements and that targeted marketing efforts are necessary to address these effectively. This tailored approach helps companies better understand their customers, enabling them to identify valuable segments that can drive profitability.

Segmentation relies on analyzing key differentiators, including demographic, geographic, economic, and behavioral data. This analysis helps companies strategize their marketing techniques more efficiently, reducing investment risks and enhancing overall business performance.

What is K-Means Algorithm
While using the k-means clustering algorithm, the first step is to indicate the number of clusters (k) that we wish to produce in the final output. The algorithm starts by selecting k objects from dataset randomly that will serve as the initial centers for our clusters. These selected objects are the cluster means, also known as centroids. Then, the remaining objects have an assignment of the closest centroid. This centroid is defined by the Euclidean Distance present between the object and the cluster mean. We refer to this step as “cluster assignment”. When the assignment is complete, the algorithm proceeds to calculate new mean value of each cluster present in the data. After the recalculation of the centers, the observations are checked if they are closer to a different cluster. Using the updated cluster mean, the objects undergo reassignment. This goes on repeatedly through several iterations until the cluster assignments stop altering. The clusters that are present in the current iteration are the same as the ones obtained in the previous iteration.

