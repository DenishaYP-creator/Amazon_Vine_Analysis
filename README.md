# Amazon_Vine_Analysis


# Overview of the analysis: 
## Background 
For consumers who purchase products and services, online Product reviews impact the purchase decision process. Many companies pay small fees to obtain product reviews on membership-based websites such as the Amazon Vine Program. The Amazon Vine membership-based website allows manufacturers and publishers to receive product reviews for their products. 

## Purpose  
In this project, we utilized an Amazon Vine program dataset specific to furniture product reviews to determine if having a paid Vine review impacts the percentage of favorable 5-star reviews for Amazon DataSet. The tools used in this project include Pyspark, AWS RDS Instance, AWS S3, and PGAdmin. We used Pysprak to transform the dataset;PGAdmin to load the transformed dataset and connect the data to an AWS RDS Instance. 
 
 ##  Deliverable 1: Perform ETL on Amazon Product Reviews
Create an AWS RDS database with tables in pgAdmin,and transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. The four DataFrames/Tables include the folllowing:  1.)Customers_table DataFrame 2.)Products_table DataFrame 3.) Review_id_table DataFrame and 4.) Vine_table DataFrame 


# Results: Deliverable 1 

PgAdmin Table that matched the 4 DataFrames in PySprak notebook. 
**(Please review Amazon_Reviews_ETL.ipyp file in this repo)
[![All-Tables.png](https://i.postimg.cc/52s6nNVp/All-Tables.png)](https://postimg.cc/DSbvzhmb)



<hr> </hr> 

## Deliverable 2: Determine Bias of Vine Reviews
DataFrame created using Pyspark methods for the following: 

1. New DataFrame created that filters votes greater than 20 
2. New DataFrame created that filters the percentage of helpful_votes/totalvotes equal to or greater than 50%
3. New DataFrame created that filters Vine review only 
4. New DataFrame created that filters Non- Vine review only
6. Calculations for the following: 1.) The total number of reviews 2.)The number of 5-star reviews 3.) The percentage 5-star reviews for all Vine 4.)The percentage 5-star reviews for all non-Vine reviews 

# Results: Deliverable 2 
Using bulleted lists and images of DataFrames as support, address the following questions:

### How many Vine reviews and non-Vine reviews were there?
Vine Reviews | Non-Vine Reviews
------------ | -------------
Content cell 1 | Content cell 2

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
Five Star Vine Reviews | Five star Non-Vine Reviews
------------ | -------------
Content cell 1 | Content cell 2

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Five Star Vine Reviews % | Five star Non-Vine Reviews %
------------ | -------------
Content cell 1 | Content cell 2

# Summary: 
There is a 7% difference between the percentage of 5 star Vine review versus non-Vine reviews, and As a result, we can conclude that there is a positivity bias for reviews in the Vine program. When we compare the "total Vine review" versus "non-Vine Review," we can visually see that there a to a notable difference in the population count. 
Never the less the percentage of 5-star reviews is more significant than that of non-Vine Reviews.
 




# Submission
### Uploads made to GitHub repository:
- Deliverable 1: Perform ETL on Amazon Product Reviews (Amazon_Reviews_ETL.ipynb file.)
- Deliverable 2: Determine Bias of Vine Reviews (Vine_Review_Analysis.ipynb file)
- Deliverable 3: A Written Report on the Analysis (README.md)


