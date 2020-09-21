<h2>Spark For Handling Big Data</h2>
<h3>Spark</h3>
<p>I found the information that Spark can perform up to 100x faster than Hadoop MapReduce. </p>
<ul>
  <li>Data processing part of Big Data Engineering.</li>
  <li>Apache Spark is written in Scala programming language.</li>
  <li>Spark is a memory based solution keeping as much as it can in a Cache RAM - that contriutes to the speed of it.</li>
  <li>Spark can be run both on local machine and within clusters environment in either a local infrastructure or it the cloud (f.e. Amazon EC2)</li>
  <li>The core idea behind Spark is MapReduce which is mapping your data set into a collection of (key, value) pairs, and then reducing over all pairs with the same key.</li>
</ul>
  
<h3>PySpark</h3>
<p>PySpark as Python library enables using Spark with Python instead of Scala.</p>
<img src="images/pyspark.jpg">
<ul>
  <li>With Python, the readability of code, maintenance, and refactoring is far easier than in Scala.</li>
  <li>I apply functional programming for buildnig data model - f.e. passing functions both lambda and defined ones as parameters of another function.</li>
  <li>Pyspark operations work like Python genearators, it's being delayed until the result is called.</li>
  <li>This way, avoiding pulling the full data frame into memory and enabling an efficient processing across a cluster of machines (I use single local machine).</li>
  <li>This is in opposition to Pandas dataframes, where everything is pulled into memory at once.</li>
  <li>The main data type in PySpark is the Spark dataframe - equivalent to dataframes in R and Pandas.</li>
  <li>Wanting to apply distributed computation using PySpark, you need to be performing operations on Spark dataframes.</li>
</ul>

<h3>Installation</h3>
<ol>
  <li>Install Java version 8</li>
  <li>Java jdk Folder will be created inside C:\Program Files\Java</li>
  <li>Add the Environment variable (JAVA_HOME) as shown in the video: JAVA_HOME = C:\Program Files\Java\jdk1.8.0_201</li>
  <li>Add the Path variable(till bin folder in System Variable Section if in case User variable section is not recognizing it): PATH = C:\Program Files\Java\jdk1.8.0_201\bin</li>
  <li>Create a subfolder named "spark" in the C: drive For e.g. C:\spark </li>
  <li>Keep your Spark installation folder inside C:\spark For e.g. C:\spark\spark-2.3.1-bin-hadoop2.7</li>
  <li>Setup Environment variables for (SPARK_HOME): SPARK_HOME = C:\spark\spark-2.3.1-bin-hadoop2.7</li>
  <li>Setup Environment variables for (HADOOP_HOME): HADOOP_HOME = C:\spark\spark-2.3.1-bin-hadoop2.7</li>
  <li>Add the Path variable(till bin folder in System Variable Section if in case User variable section is not recognizing it): PATH = C:\spark\spark-2.3.1-bin-hadoop2.7\bin</li>
  <li>Copy and Paste the winutils file in C:\spark\spark-2.3.1-bin-hadoop2.7\bin</li>
</ol>

<h3>Project Demo</h3>
<ol>
  <li>Importing all necessary libraries and sprak features initialization.</li>
  <li>Setting up variable and functions for further passing as parameters.</li>
  <li>Exporting data set.</li>
  <li>Building so-called RDD Data Model that data will be pushed through.</li>
  <li>Converting RDD into Spark Data Frame.</li>
  <li>Converting RDD into Python list of tuples.</li>
  <li>Converting Spark Data Frame into Pandas Data Frame - converting RDD into Pandas DF not possible.</li>
  <li>Exporting Pandas DF into csv flat-file.</li>
</ol>
  
<h3>Notes</h3>
<p>I take advantage of Jupyter Notebook and put all the notes in there that help me to understand PySpark syntax</p>

