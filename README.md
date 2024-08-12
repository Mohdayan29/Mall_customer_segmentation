# Customer Segmentation Using K-Means Clustering

📌 Objective
This project aims to develop a customer segmentation model that categorizes customers into distinct groups based on their behavior and preferences. By analyzing purchasing data, these clusters provide valuable insights for the marketing team to craft targeted strategies.

![Customer segmentation](https://github.com/user-attachments/assets/87c0fadd-5b89-4b79-95b6-dcb772cd5686)


What is Customer Segmentation?

Customer segmentation is dividing a customer base into distinct groups based on shared characteristics relevant to marketing, such as gender, age, interests, and spending habits. This approach allows companies to tailor their marketing strategies to meet the specific needs of each group.
By implementing customer segmentation, companies recognize that each customer has unique requirements and that targeted marketing efforts are necessary to address these effectively. This tailored approach helps companies better understand their customers, enabling them to identify valuable segments that can drive profitability.
Segmentation relies on analyzing key differentiators, including demographic, geographic, economic, and behavioral data. This analysis helps companies strategize their marketing techniques more efficiently, reducing investment risks and enhancing overall business performance.

K-means Algorithm
We specify the number of clusters that we need to create.
The algorithm selects k objects at random from the dataset. This object is the initial cluster or mean.
The closest centroid obtains the assignment of a new observation. We base this assignment on the Euclidean Distance between object and the centroid.
k clusters in the data points update the centroid through calculation of the new mean values present in all the data points of the cluster. The kth cluster’s centroid has a - - Length of p that contains means of all variables for observations in the k-th cluster. We denote the number of variables with p.
Iterative minimization of the total within the sum of squares. Then through the iterative minimization of the total sum of the square, the assignment stop wavering when we - - Achieve maximum iteration. The default value is 10 that the R software uses for the maximum iterations.
