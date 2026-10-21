Customer Segmentation Using K-Means Clustering 

🛍️An unsupervised machine learning project that segments retail/mall customers into distinct behavioral groups based on their annual income and spending score, enabling targeted marketing and business strategy development.

📌 Project Overview
In retail analytics, understanding customer behavior is crucial for targeted marketing. 
Since customer datasets often lack predefined target labels, this project applies Unsupervised Learning (K-Means Clustering) to automatically discover hidden patterns and natural customer segments.

🚀 Key Features & WorkflowFeature Selection: 
Extracted core behavioral features—Annual Income and Spending Score (1-100).

Optimal Cluster Determination (Elbow Method):
Evaluated Within-Cluster Sum of Squares (WCSS) across multiple cluster counts to determine the optimal number of clusters ($K = 5$).

Model Training: 
Implemented the K-Means Clustering algorithm to categorize customers into actionable segments.

Data Visualization: Plotted cluster distributions, boundaries, and respective Centroids using Matplotlib and Seaborn.

📊 Business Insights & Customer Profiles
The K-Means model successfully categorized customers into 5 distinct behavioral segments:

Cluster 1 (Careful Customers): 
Moderate annual income with moderate spending habits. 
Ideal targets for standard loyalty programs.

Cluster 2 (Standard Customers): 
Balanced income and spending levels; forms the reliable core base for everyday retail offerings.

Cluster 3 (Target / High-Value Customers): High annual income and high spending score.

(Most Lucrative Group): Perfect candidates for exclusive VIP memberships, premium services, and high-end promotions.

Cluster 4 (Careless Customers): Low annual income paired with high spending behavior. Requires careful credit risk management or specialized promotional campaigns.

Cluster 5 (Sensible / Prudent Customers): High annual income but low spending score. 
Potential to increase conversions through targeted utility or luxury investment offerings.

🛠️ Tech StackLanguage: Python 3.
xLibraries:Pandas & NumPy (Data manipulation & handling)
Scikit-Learn (K-Means algorithm implementation)
Matplotlib & Seaborn (Data visualization & plotting)
Environment: Google Colab

💻 How to Run the Code
Clone the repository or open the .ipynb notebook in Google Colab.
Download the Mall_Customers.csv dataset from Kaggle.
Run the cells step-by-step to generate the Elbow graph, clustered scatter plots, and final insights.

Created as part of my Data Science Portfolio.
