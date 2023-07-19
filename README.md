Parallelizing K-Means Based Clustering using PySpark

Objective:

The primary objective of this project is to design a parallel K-means clustering algorithm. By implementing parallel processing at each step, the aim is to minimize runtime while maximizing accuracy in assigning cluster labels to data points. This involves effectively grouping similar data points and separating dissimilar ones for efficient clustering.

Work Done:

1. Implemented the k-means clustering in two ways : sequentially using dataframes and parallely using PySpark RDD.
2. For both the methods, compared the clustering techniques using Silhouette Score and also compared the run time for both the methods by varying the number of maximum iterations and keeping clusters constant.
3. Used a country dataset which contains: country, child_mort, health, imports, income, inflation, life_epec, total_fer, gdpp from kaggle.
4. We have used our algorithm in all the above given columns.

Link to dataset: <https://drive.google.com/file/d/1LFyecfE_5w_fFVlABe8nEEGxcxtmKWJK/view?usp=sharing>

Evaluation:

This is based on the clustering quality that our algorithm returns and this is evaluated from the Silhouette Score and for the sequential algorithm the score we got is .6003 and for parallel algorithm we got .7256.

Final Outcomes:

Clustering results(Sequentia(left)l and parallel(right))

![](Result1.png) ![](Result2.png)

To see results clearly open Results.pdf 

Link to git repository:[https://github.com/divyansh-123/K-means-based-clustering-using-pyspark/blob/main/README. md](https://github.com/divyansh-123/K-means-based-clustering-using-pyspark/blob/main/README.md)

