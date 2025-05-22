##Project Overview: Disney Movie PySpark Analysis
This notebook project involves analyzing a dataset of Disney+ shows using PySpark, a distributed computing framework. The focus is on extracting insights from the dataset using various data transformation and analysis techniques available in PySpark.
Key Analyses Performed
Basic Exploration:

Displaying schema.

Counting number of rows and columns.

Identifying missing values in columns.

Showing basic statistics and column names.

Rating-Based Analysis:

Created a subset dataframe with relevant columns for analysis.

Filtered movies with IMDb ratings of 8 and 9.

Sorted movies by title and average rating.

Top/Bottom Rated Content:

Top 10 highest-rated Disney movies (by average IMDb votes).

Lowest-rated movies excluding null values.

Genre and Keyword-Based Insights:

Calculated average rating per genre.

Found plots containing keywords like “ghost” and “evil”.

Grouping and Aggregation:

Average IMDb rating per director.

Count of movies grouped by rated category.

Technologies Used:
PySpark for distributed data processing

SparkSession to initiate Spark environment

SQL Functions like groupBy, agg, filter, desc, avg, etc.
