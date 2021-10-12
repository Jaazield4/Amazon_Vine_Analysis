# Amazon_Vine_Analysis

## Overview of Analysis
The purpose of this project is to perform the ETL process on an Amazon Review dataset and determine if there is any bias toward favorable reviews from Prime memebers. The dataset that is being analyzed is the Amazon DVD reviews. PySpark paired with pgAdmin and an AWS RDS was used to complete the analysis.

## Results

### How many Vine reviews and non-Vine reviews were there?
![image](https://user-images.githubusercontent.com/85451089/137016086-692afd0c-a53e-4c14-816d-21cb8eee3902.png)
![image](https://user-images.githubusercontent.com/85451089/137016398-16fe00fc-07f5-423b-a735-050513d1f9a4.png)

There were a total of 49 Vine reviews within the Amazon DVD Review Dataset, and 151400 of the reviews were non-vine reviews.

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/85451089/137016706-8d19d4e5-b0bb-4678-9d4b-7433d178a056.png)

From the 49 vine reviews only 9 of them rated the maximum of 5 stars

![image](https://user-images.githubusercontent.com/85451089/137016771-721a485a-822f-40de-9e55-673e132a7ebf.png)

The Amazon Review dataset provided that 78,061 of the non-vine reviews gave a 5 stars rating.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/85451089/137016992-deda5dba-9b0b-4a02-ba88-e9ab904df9db.png)

Only a little over 18% of the vine-reviews gave a 5 star rating.

![image](https://user-images.githubusercontent.com/85451089/137017085-4ae65d28-107b-4ecc-a16e-1d8e12163cdd.png)

While 51% of the non-vine reviews gave a 5 star rating.

## Summary
Given the analysis and the amount of 5 star reviews coming from both groups it is easy to see that there is no bias coming from vine-reviews as they preformed much more poorly than non vine reviews. Only 18% of paid reviews gave a 5 star rating while 51% of non paid reviews decided to give a 5 star rating. An additional analysis that can be performed to support the results would be to conduct a count of how many reviews each unique customer_id left. 
