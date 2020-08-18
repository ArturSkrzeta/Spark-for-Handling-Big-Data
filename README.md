<h2>Spark For Handling Big Data</h2>
<h3>Spark</h3>
<p>I found the information that Spark can perform up to 100x faster than Hadoop MapReduce. </p>
<ul>
  <li>Apache Spark is written in Scala programming language.</li>
  <li>Spark can be run both on local machine and within clusters environment in either a local infrastructur or it the cloud (f.e. Amazon EC2)</li>
</ul>
  
<h3>PySpark</h3>
<ul>
  <li>PySpark as Python library enables using Spark with Python instead of Scala.</li>
  <li>With Python, the readability of code, maintenance, and familiarity is far better in comparsion to Scala</li>
  <li>Pyspark operations work like Python genearators, it's being delayed until the result is called.</li>
  <li>This way, avoiding pulling the full data frame into memory and enabling an efficient processing across a cluster of machines.</li>
  <li>This in opposition to Pandas dataframes, where everything is pulled into memory at once.</li>
  <li>The main data type in PySpark is the Spark dataframe - equivalent to dataframes in R and Pandas.</li>
  <li>Wanting to apply distributed computation using PySpark, you need to be performing operations on Spark dataframes.</li>
</ul>

<h3>Installation</h3>
1.Install Java version 8
2.Java jdk Folder will be created inside C:\Program Files\Java
3.Add the Environment variable (JAVA_HOME) as shown in the video: JAVA_HOME = C:\Program Files\Java\jdk1.8.0_201
4.Add the Path variable(till bin folder in System Variable Section if in case User variable section is not recognizing it): PATH = C:\Program Files\Java\jdk1.8.0_201\bin
5.Create a subfolder named "spark" in the C: drive For e.g. C:\spark 
6.Keep your Spark installation folder inside C:\spark For e.g. C:\spark\spark-2.3.1-bin-hadoop2.7
7.Setup Environment variables for (SPARK_HOME): SPARK_HOME = C:\spark\spark-2.3.1-bin-hadoop2.7
8.Setup Environment variables for (HADOOP_HOME): HADOOP_HOME = C:\spark\spark-2.3.1-bin-hadoop2.7
9.Add the Path variable(till bin folder in System Variable Section if in case User variable section is not recognizing it): PATH = C:\spark\spark-2.3.1-bin-hadoop2.7\bin
10.Copy and Paste the winutils file in C:\spark\spark-2.3.1-bin-hadoop2.7\bin
