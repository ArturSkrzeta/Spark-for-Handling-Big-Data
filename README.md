<h2>Spark For Handling Big Data</h2>
<h3>Spark</h3>
<p>I found the information that Spark can perform up to 100x faster than Hadoop MapReduce. </p>
<ul>
  <li>Apache Spark is written in Scala programming language.</li>
  <li>Spark can be run both on local machine and within clusters environment in either a local infrastructur or it the cloud (f.e. Amazon EC2)</li>
<ul>
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

<h3>Demo</h3>
<p>...</p>
