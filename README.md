# Big-Data-Fundamentals-with-PySpark
## Discription
Advance your data skills by mastering Apache Spark. Using the Spark Python API, PySpark, you will leverage parallel computation with large datasets, and get ready for high-performance machine learning. From cleaning data to creating features and implementing machine learning models, you'll execute end-to-end workflows with Spark. The track ends with building a recommendation engine using the popular MovieLens dataset and the Million Songs dataset.
### 1. Introduction to Big Data analysis with Spark [Notebook](https://github.com/cc59chong/Big-Data-Fundamentals-with-PySpark/blob/main/Introduction%20to%20Big%20Data%20analysis%20with%20Spark.ipynb)
Fundamentals of BigData and introduction to Spark as distributed computing framework
* Main components: Spark Core and Spark built-in libraries - Spark SQL, Spark MLlib, Graphx, and Spark Streaming
* PySpark: Apache Spark's Python API to execute Spark jobs
* PySpark shell: For developing the interactive applications in python
* Spark modes: Local and clister mode
### 2. Programming in PySpark RDD’s [Notebook](https://github.com/cc59chong/Big-Data-Fundamentals-with-PySpark/blob/main/Programming%20in%20PySpark%20RDD%E2%80%99s.ipynb)
Introduction to RDDs, different features of RDDs, methods of creating RDDs and RDD operations (Transformation and Actions)
* Transsformations: ```map()```, `flatMap()`, `filter()`,` union()`
* Actions: `collect()`, `take()`, `first()`, `count()`
* Paired RDD Transformations: `reduceByKey()`, `groupByKey()`, `sortByKey()`, `join()`, `countByKey()`, `collectAsMap()`
* Advanced RDD Actions: `reduce()`, `saveAsTextFile()`
* **Project**: Write code that calculates the most common words
### 3. PySpark SQL & DataFrames [Notebook](https://github.com/cc59chong/Big-Data-Fundamentals-with-PySpark/blob/main/PySpark%20SQL%20%26%20DataFrames.ipynb)
Introduction to Spark SQL, DataFrame abstraction, creating DataFrames, DataFrame operations and visualizing Big Data through DataFrames
* DataFrame Transformations: `select()`, `filter()`, `groupby()`, `orderby()`, `dropDuplicates()` and `withColumnRenamed()`
* DataFrame Actions: `head()`, `show()`, `count()`, `clomuns` and `describe()`
* Data Visualization: `hist()`, `displot()`, `pandas_histogram()`, `toPandas()`, `HandySpark`
* **Project**: Exploratory data analysis (EDA) on the "FIFA 2018 World Cup Player" 
### 4. Machine Learning with PySpark MLlib [Notebook](https://github.com/cc59chong/Big-Data-Fundamentals-with-PySpark/blob/main/Machine%20Learning%20with%20PySpark%20MLlib.ipynb)
Introduction to Spark MLlib, the three C's of Machine Learning (Collaborative filtering, Classification and Clustering) 
