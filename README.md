# Amazon_Vine_Analysis

#Resources
This analysis used Amazon Web Services(AWS) Relational Database Service (RDS), Googel Colab, PGAdmin Version 6.4, PostgreSQL 11.13, Spark 3.2.0, Java, PySpark, And Amazon S3 https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Outdoors_v1_00.tsv.gz

# Deliverable 1 Results

Review ID Table from PGAdmin

![Review_ID_Table_Snip](https://user-images.githubusercontent.com/90878901/149685903-51679154-8b4b-41de-94a1-8d492fd425d4.jpg)

Products table from PGAdmin

![Products_Table_Snip](https://user-images.githubusercontent.com/90878901/149685898-ef7375e1-c5ed-4b05-92c7-df0015f6e13b.jpg)

Customers Table from PGAdmin

![Customers_Table_Snip](https://user-images.githubusercontent.com/90878901/149685931-e10adee6-e496-4a4a-af81-69d4130bed38.jpg)

Vine Table from PGAdmin

![Vine_Table_Snip](https://user-images.githubusercontent.com/90878901/149685914-b63e7f44-c816-4aeb-ad12-2411be7605c7.jpg)

# Deliverable 2 Results

![Vine_summary_table](https://user-images.githubusercontent.com/90878901/149690106-a507ad8d-6a32-418e-9047-33229d63647f.jpg)

# Deliverable 3

## Overview of the Analysis
The objective of the analysis was to determine if there was any positivity bias for reviews in the Vine program. This analysis was on the "outdoors" reviews

## Results
The results of the analysis of outdoors reviews were as follows:
  * There were 107 vine reviews and 39,869 non vine reviews.
  * There were 56 5 star vine reviews and there were 21,005 5 star non vine reviews.
  * The percentage of 5star vine reviews was 52.34% while non vine 5 star reviews were 52.69%
  
## Summary
There was not a positivity bias in reviewing the vine program for outdoors. Additional analysis is needed. A review of verfied -purchases (also in the data) could be helpful in reviewing the number of 5 star reviews. Another analysis could look at the category. Was this an anomoly to the outdoors category? More data could be used to help determine if this is unique to outdoors or symbolic of larger results. 
