# Amazon_Vine_Analysis

## _Overview of the project_ 

I have been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. In order to complete this analysis, I have picked a random subset of data of Amazon books reviews details then performed an ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next I used PySpark, Google Collaboratory, and Pandas to determine if there is any bias toward favorable reviews from Vine members in my selected dataset. _______ In this specific example there were no paid reviews on this dataset, and the process to be sure about that was as follows:


First we load our data and clean to get the useful reviews, we then try to split the data to either vine reviews or non-vine reviews. Hence, we filter our data to get the result demostrated below with a snippet of the code. 

![alt text](https://github.com/Yoditatr/Amazon_Vine_Analysis/blob/main/Resources/filtered%20df%20snippet.PNG?raw=true)

## _Results of the Analysis_

In the results sectionn I am trying to addres the following questions. 

- How many Vine reviews and non-Vine reviews were there?

  - The total number of reviews are 403807.
  - In this dataset there are no paid reviews. 
  - The number of 5 star votes is 242889.

![alt text](https://github.com/Yoditatr/Amazon_Vine_Analysis/blob/main/Resources/code%20snippet.PNG?raw=true)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  - Since the number of paid reviews are zero in this dataset, the number of vine review hence is zero. 
  
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

  - 60% of the reviews were 5 star. 
  
  ![alt text](https://github.com/Yoditatr/Amazon_Vine_Analysis/blob/main/Resources/code%20snippet%202.PNG?raw=true)
  
  
## _Summary of the analysis_ 

In our randomly selected dataset, there was no Positive bias, because the data is made entirely with bona fida reviews. Additional analysis, could be done at the verified purchaser reviewrs and perform an analysis to see what verified purchasers think of the books compared to other reviewers.
