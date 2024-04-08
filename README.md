# Home_Sales
![tips-for-selling-your-home](https://github.com/IsmaelG8/Home_Sales_Analysis/assets/128990362/a76d1844-5753-47e6-be67-18473ea2ecb5)

Project Overview:

This project involved an in-depth analysis of home sales data using SparkSQL, showcasing my adeptness in leveraging Apache Spark for data processing and analysis. The challenge was designed to harness Spark's powerful in-memory computation capabilities to efficiently query large datasets, emphasizing data manipulation, analysis, and optimization techniques.

Objective:

The primary goal was to extract meaningful insights from a comprehensive home sales dataset by performing various SQL queries to understand market trends based on property characteristics and sales records. This included analyzing the average sale prices of homes with different features across various years and evaluating the impact of data caching on query performance in Spark.

Technical Summary:

Data Preparation:

Initialized a Spark session and imported necessary PySpark SQL functions.
Loaded the home_sales_revised.csv dataset into a Spark DataFrame, establishing a foundational structure for the analysis.
Analysis Execution:

Created a temporary table, home_sales, to facilitate SQL queries against the dataset.
Conducted a series of queries to determine:
The average sale price of four-bedroom homes by year.
The average sale price of homes with three bedrooms and three bathrooms by construction year.
The average sale price of homes meeting specific criteria (three bedrooms, three bathrooms, two floors, and a minimum size of 2,000 square feet) by construction year.
The average sale price of homes per "view" rating for those with an average price of at least $350,000, including performance timing analysis.
Data Optimization and Performance Measurement:

Implemented caching for the home_sales table to enhance query performance.
Verified the caching status through PySpark commands.
Compared the performance of the aforementioned "view" rating query before and after caching and upon partitioning the data by "date_built".
Partitioning and Further Optimization:

Partitioned the dataset based on the "date_built" field and created a temporary table for partitioned data to observe performance improvements.
Uncached the home_sales table and verified uncaching, ensuring efficient resource utilization.
Outcomes:

The project successfully demonstrated the efficiency of using SparkSQL for complex data analysis tasks. Key outcomes included:

Identification of trends in home sale prices based on various property features and years of sale.
Evidence of significant query performance improvement through data caching and partitioning strategies.
Skills and Tools Used:

Apache Spark: For in-memory data processing and analysis.
SparkSQL: For executing SQL queries on Spark DataFrames.
PySpark: For integrating Python with Spark, facilitating data manipulation and analysis.
Jupyter Notebook: As an interactive computational environment for code development and testing.
Conclusion:

This SparkSQL challenge project not only highlighted my technical proficiency in using Apache Spark for advanced data analysis but also demonstrated my capability to optimize data processing tasks for improved performance. The insights derived from the home sales dataset are indicative of my analytical skills, showcasing my ability to translate complex datasets into actionable business insights.
