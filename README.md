# ETL-with-Pyspark

This is the final project of the course. The goal isto use pyspark on a project of our choice. These are the steps I did to complete the project:
[pre-requisites: have Java (on C:), Anaconda, Mysql and MongoDB Compass installed)

1) Grab the data

    1 - Projects funded in EU 2007-2013: https://data.europa.eu/data/datasets/cordisfp7projects?locale=pt
    
    3 - Projects funded in EU in 2014-2020: https://data.europa.eu/data/datasets/cordish2020projects?locale=pt
    
    2 - Projects funded in EU 2021-2027: https://data.europa.eu/data/datasets/cordis-eu-research-projects-under-horizon-europe-2021-2027?locale=en
    

1) Create pyspark and hadoop environment in desktop

    1 - Dowload Apache Spark from https://spark.apache.org/downloads.html
    
    2 - follow apache spark installation as in https://phoenixnap.com/kb/install-spark-on-windows-10 until end of step7
    
    [environment variables created:
    
    HADOOP in C:\Hadoop
    
    JAVA_HOME in C:\Java
    
    PYSPARK_DRIVER_PYTHON in jupyter
    
    PYSPARK_DRIVER_PYTHON_OPTS in notebook
    
    PYSPARK_SUBMIT_ARGS in --master local[3] pyspark-shell
    
    SPARK_HOME in C:\Spark\spark-3.3.1-bin-hadoop3
    
    in Path added: 
    
        %SPARK_HOME%\bin
        
        %HADOOP_HOME%\bin
        
        %JAVA_HOME%\bin
           

2) Create database in MongoDB

    1 - Install MongoDB Compass
    
    2 - Create database and collections
    
 3) Create ETL script in Jupyter Notebook
 
 4) Save data in a MySQL database
 
    1 -Dowload conector jar file from: https://dev.mysql.com/downloads/connector/j/
    
    2 - Put jar file in jar directory of Spark (C:\\Spark\jars) in my case
 
 5) Vizualize the data in PowerBI
  
    1 - Dowload conector installation file from: https://dev.mysql.com/downloads/connector/j/
    
    2 - Install the connector
    
    3 - Open PowerBi/select datasource = Mysql/write your server name (localhos in my case), and select database on the left and write your Mysql credentials
    
  6) Publish PowerBI report

    1 - create professional e-mail and login in power bi desktop and power bi community
    
    2- publish the report and present it by expandind the window
    
    
    
    
    
    






