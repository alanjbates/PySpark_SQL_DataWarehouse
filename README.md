# PySpark_SQL_DataWarehouse
Using PySpark, we can create a normalized database table structure that can be analyzed with SQL

In this exercise, I was able to create a small data warehouse using Spark to save data as if it were a table in a typical relational database. After the data has been loaded in this manner, we can query the tables using Structured Query Language (SQL).

I was able to execute Spark SQL within a Python program. Also know that if you are using a typical Hadoop distribution, there are many ways you can connect those tables to existing tools just as if it were a normal, relational database. Spark SQL natively supports reading and writing data managed by Apache Hive. Spark can act as a distributed SQL engine allowing you to connect to any tool with JDBC/ODBC support. You can also integrate Spark with big data tools like Apache Phoenix and normal relational databases.

#Example 1, tableize U.S. Gazetteer files provided by the United States Census Bureau. These files provide a listing of geographic areas for selected areas. You can find the Gazetteer files for 2017 and 2018 in the data directory under the gazetteer folder. These directories contain data for congressional districts, core statistical areas, counties, county subdivisions, schools, census tracts, urban areas, zip codes, and places of interest. You will combine the data from 2017 and 2018, and create tables with the filename of the source (e.g., places.csv is saved in the places table).

#Example 2, tableize Airport flight data.  Then we can write SQL to perform aggregations and summaries just as if the data were tableized in a traditiona RDBMS.
