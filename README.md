# ETL-with-Pyspark

This is the final project of the data Analyst course. We had 3 specializations to choose. I chose the pre-engineering track, where the goal is to use pyspark and/or mongodb on a project of our choice. I decided to create a workflow from a mongodb database with an ETL script using jupyter notebook and pyspark API, loading the transformed data a Mysql database and further vizualition in PowerBI. 

These are the steps I did to complete the project:

[pre-requisites: have Java (on C:), Spark (on C:), Anaconda, Mysql and MongoDB Compass installed)

## 1) Datasets sources

1 - Projects funded in EU 2007-2013: https://data.europa.eu/data/datasets/cordisfp7projects?locale=pt

2 - Projects funded in EU in 2014-2020: https://data.europa.eu/data/datasets/cordish2020projects?locale=pt

3 - Projects funded in EU 2021-2027: https://data.europa.eu/data/datasets/cordis-eu-research-projects-under-horizon-europe-2021-2027?locale=en

    [explanation of projects database information on https://data.europa.eu/data/datasets/cordisref-data?locale=en]

4 - Industry production worldwide 2010-2019: https://stats.oecd.org/
    

## 2) Create pyspark and hadoop environment in desktop

1 - Dowload Apache Spark from https://spark.apache.org/downloads.html

2 - follow apache spark installation as in https://phoenixnap.com/kb/install-spark-on-windows-10 until end of step7

3 - Created the following environemntal variables:

        HADOOP in C:\Hadoop

        JAVA_HOME in C:\Java

        PYSPARK_DRIVER_PYTHON in jupyter

        PYSPARK_DRIVER_PYTHON_OPTS in notebook

        PYSPARK_SUBMIT_ARGS in --master local[3] pyspark-shell

        SPARK_HOME in C:\Spark\spark-3.3.1-bin-hadoop3

        in Path added: 

            %SPARK_HOME%\bin

            %HADOOP_HOME%\bin

            %JAVA_HOME%\bin]
           

## 3) Create database in MongoDB

1 - Install MongoDB Compass

2 - Create database and collections
    
    
 ## 4) Create ETL script in Jupyter Notebook
 
 
 ## 5) Save data in a MySQL database
 
1 -Dowload conector jar file from: https://dev.mysql.com/downloads/connector/j/

2 - Put jar file in jar directory of Spark (C:\\Spark\jars) in my case
    
 
 ## 6) Vizualize the data in PowerBI
  
1 - Dowload conector installation file from: https://dev.mysql.com/downloads/connector/j/

2 - Install the connector

3 - Open PowerBi/select datasource = Mysql/write your server name (localhos in my case), and select database on the left and write your Mysql credentials
    
    
  ## 7) Publish PowerBI report

1 - create professional e-mail and login in power bi desktop and power bi community

2 - connect to the Mysql server (server: localhost, database: write_database_name)

3 - publish the report and present it by expandind the window
    
    
    
    
    
    






