The understanding of the ETL process and the ability to perform an ETL task is an important skill for every data engineer. In this field, and for a particular ETL task, there are multiple tools that can be used.

For the sake of this project, I have chosen to perform a simple ETL task using Python. With this project, I was able to deepen my knowledge of Python coding and also undergo an actual data engineering task.

I started this project by first installing the PyODBC and Psycopg2 softwares using the pip install command. After that, I imported the needed libraries/modules which are;

sqlalchemy : This library acts as a bridge between Python and SQL. It facilitates smooth communication betweeen Python programs and SQL databases.

create_engine: This creates an engine object based on a URL that must be provided. This URL typically contains hostname, databasename, username and password. It was the create_engine() function that facilitated the data load into Postgresql.

pyodbc: This module makes it easy to access any database by connecting to the driver of the database.

pandas: Of course, do you do any data related activity without using pandas? This library helped in the reading of the data and transforming the data into a dataframe.

After all necessary libraries/modules/functions had been imported, I moved on to putting my postgres database credentials into variables that I can pass into the load function later. Then I used the pyodbc.drivers() function to know the different types of ODBC drivers present on my local disk. I then went on to define my data extraction and data load functions, and running the code showed the data extraction and loading was successful.
