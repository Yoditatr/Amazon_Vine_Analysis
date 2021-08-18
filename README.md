# Amazon_Vine_Analysis

## _Overview of the project_ 

I have been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. In order to complete this analysis, I have picked a random subset of data of Amazon books reviews details then performed an ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next I used PySpark, Google Collaboratory, and Pandas to determine if there is any bias toward favorable reviews from Vine members in my selected dataset. _______ In this specific example there were no paid reviews on this dataset, and the process to be sure about that was as follows:
