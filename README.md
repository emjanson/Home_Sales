# Home_Sales
 MSU Data Analytics BootCamp Module 22 Challenge

Code file name: 'Home_Sales.ipynb' located in the root repository directory

The Jupyter Notebook file in this repository demonstrates the use of Spark, Spark SQL, data partitioning, and the Parquet data file format to create a temporary SparkSQL table from a CVS file, perform various SparkSQL queries on the table, demonstrate the performance impact of Spark caching/uncaching on SparkSQL queries, and demonstrate the performance impact of data partitioning and the Parquet file format on SparkSQL queries. Simply: a remote CSV is read into a Spark DataFrame, placed into a temporary SparkSQL table, and then several SparkSQL queries are performed, one of which is timed in order to obtain a baseline (uncached DataFrame) SparkSQL performance metric. The Spark DafaFrame is then cached and the timed SparkSQL query is repeated and timed for cached vs. uncached SparkSQL performance comparisons. Finally, the Spark Dataframe is partitioned by one of the columns within the DataFrame and read into the Parquet file format. The previous timed SparkSQL query is repeated and timed once more for comparisons of cached Spark Dataframe vs. partitioned Parquet dataset SparkSQL query performance. The DataFrame is then uncached.

Generally, (as expected), cached SparkSQL query performance was slightly better than uncached, and partitioned Parquet SQL query performance was slightly better than cached SparkSQL.


*Code sourcing statement*
-----------------------

I used a natural language description of some desired code functions entered into ChatGPT 3.5 to help build the code structure. I copied pieces of that generated code to be more efficient, but I tailored it to fit all the desired functions of this particular project. I did not directly copy and paste any of this code from the internet otherwise (e.g., from StackExchange or any other webpage). I did not seek any assistance or use code written by my peers or instructors for this challenge.

End of code sourcing statement.

 ----------------------
