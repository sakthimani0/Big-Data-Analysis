# Big-Data-Analysis

COMPANY: CODTECH IT SOLUTIONS

NAME: SAKTHI MANI M

INTERN ID: CT06DH2657

DOMAIN: DATA ANALYTICS

DURATION: 6 WEEEKS

MENTOR: NEELA SANTOSH

This project demonstrates scalable data analysis using PySpark on the Netflix Titles dataset. PySpark is a powerful tool for handling and analyzing large datasets using distributed computing.

We began by initializing a SparkSession and loading the CSV dataset into a DataFrame. The first step was analyzing the distribution of content types (Movies vs TV Shows) using simple groupBy and count operations. Next. we explored the top countries contributing to Netflix's content by grouping data by the 'country' field.

To analyze genres, we split and exploded the listed_in column (which contains comma-separated genres), then counted the frequency of each genre. We also identified the most frequent directors using similar grouping methods.

A year-wise trend analysis showed how many titles were released each year. We then extracted durations using regular expressions and calculated the average duration for movies and TV shows separately.

We performed filtered analysis by searching for titles containing the word "Love" released after 2015. demonstrating PySpark's filtering capabilities. A join operation was also carried out by duplicating and joining the dataset on show_id to simulate relational queries.

Finally, we split the cast column to identify the most frequently appearing actors.

Overall, the project showcased PySpark's ability to handle real-world data tasks like filtering. grouping. joining. and aggregation efficiently. proving its scalability for big data analytics.
