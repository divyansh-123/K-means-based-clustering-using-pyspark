IT-494 (Group-7)

Parallelizing K-Means Based Clustering using PySpark

Objective:

The major goal of the project is to develop a K-means-based clustering algorithm in parallel at each step in order to reduce run time and achieve maximum accuracy in assigning cluster labels to data points (i.e. grouping/clustering similar data points and separating dis-similar data points).

The major goal of the project was to develop a K-means-based clustering algorithm in parallel at each step in order to reduce run time and achieve maximum accuracy in assigning cluster labels to data points (i.e. grouping/clustering similar data points and separating dis-similar data points).

Work Done:

1. We have implemented the k-means clustering in two ways : sequentially using dataframes and parallely using PySpark RDD.
1. For both the methods, compared the clustering techniques using Silhouette Score and also compared the run time for both the methods by varying the number of maximum iterations and keeping clusters constant.
1. Used a country dataset which contains: country, child\_mort, health, imports, income, inflation, life\_epec, total\_fer, gdpp from kaggle.
1. We have used our algorithm in all the above given columns.

Link to dataset: <https://drive.google.com/file/d/1LFyecfE_5w_fFVlABe8nEEGxcxtmKWJK/view?usp=sharing>

Evaluation:

This is based on the clustering quality that our algorithm returns and this is evaluated from the Silhouette Score and for the sequential algorithm the score we got is .6003 and for parallel algorithm we got .7256.

Final Outcomes:

Clustering results(Sequentia(left)l and parallel(right))

![](Result1.png) ![](Result2.png)

Link to git repository:[https://github.com/divyansh-123/K-means-based-clustering-using-pyspark/blob/main/README. md](https://github.com/divyansh-123/K-means-based-clustering-using-pyspark/blob/main/README.md)


