This segmentation analysis aimed at identifying distinct customer groups based on their loan characteristics, repayment capacity, and financial profile, to better tailor loan products and marketing strategies. 
1. Three different datasets were downloaded from Kaggle. The datasets comprise loan facts table, loan 
dimension table and borrower dimension table. 
2. These datasets were loaded in google collab notebook, an integrative development of python, where the 
entire project was executed. 
3. Each dataset was thoroughly processed by converting columns to their appropriate data type, removing 
columns with missing values and dropping columns that were not relevant for the analysis. 
4. After pre-processing, the three datasets were joined together to form a one complete table. 
5. The merged data was further preprocessed for the clustering process. The preprocessing involved: 
a. Encoding categorical columns for easy analysis 
b. Scaling the data to reduce the effect of outliers on clustering outcome. 
c. Reducing the dimension of the data using PCA dimensionality reduction method to reduce the 
complexity of the data. 
6. An optimal cluster number of five was determined using the Elbow Method. 
7. The Agglomerative clustering method was then fit to the preprocessed data to predict five (5) customer 
segment/clusters. 
8. An exploratory analysis was performed on these clusters to gain insights into their distribution. 
9. Visualizations were then created to answer each research question.
A final documentation of this project is provided.
