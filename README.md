# Amazon_Vine_Analysis


# Overview of the analysis: 
## Background 
Product review play a significant part in the eye of a consuemr when purchasing consumer products and service online. Many companies pay fees to obtain reviews to membership website. The Amazon Vine program  allows manufacturers and publishers to receive products reviews from members, who publish a review.



## Purpose  
In this project, we worked with an Amazon datasets specific to furniture. We used Pyspark to transform the dataset, connect to a AWS RDS Instance and load the transformed dataset into PGAdmin. The final results helped in determininng if having a paid Vine review impacts the percentage of favorable 5-star reviews for Amazon DataSet.
 
 
 ##  Deliverable 1: Perform ETL on Amazon Product Reviews
#### Workflow:
1. Extracted DataFrame of Amazon Review dataset
2. Extracted  Amazon Review dataset transformed into four DataFrames
  -  Customers_table DataFrame
  -  Products_table DataFrame
  -  Review_id_table DataFrame
  -  Vine_table DataFrame
3. All four DataFrames loaded into pgAdmin tables
  -  Customers_table 
  -  Products_table 
  -  Review_id_table 
  -  Vine_table 

# Results: Deliverable 1 
Using bulleted lists and images of DataFrames as support, address the following questions:



<hr> </hr> 

## Deliverable 2: Determine Bias of Vine Reviews
#### Workflow:
1. DataFrame created using Pyspark methods 
2. New DataFrame created that filters votes greater than 20 
3. New DataFrame created that filters the percentage of helpful_votes/totalvotes equal to or greater than 50% 
4. New DataFrame created that filters Vine review only 
5. New DataFrame created that filters Non- Vine review only
6. Calculations for the following: 
    -  The total number of reviews
    -  The number of 5-star reviews
    -  The percentage 5-star reviews for all Vine 
    -  The percentage 5-star reviews for all non-Vine reviews (15 pt)

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

Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.




### Submission
- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis (README.md)

### Uploads made to Amazon_Vine_Analysis GitHub repository:
Your Amazon_Reviews_ETL.ipynb file.
Your Vine_Review_Analysis.ipynb or Vine_Review_Analysis.sql file.
An updated README.md that has your written analysis.
