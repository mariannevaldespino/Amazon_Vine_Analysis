# Amazon_Vine_Analysis

## Overview of the analysis
The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program, use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the dataset. 

## Results
### 1. How many Vine reviews and non-Vine reviews were there? 
- 33 Vine reviews
- 45,388 Non-Vine reviews

## 2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Vine reviews: 15
- Non-Vine reviews: 23,733

## 3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Vine reviews: 45.5%
- Non-Vine reviews: 52.3%

## Summary
I don't believe there is a positivity bias for leaving good reviews in the paid program since there are not that many and they are not rating very well since 45.5% are rating 5 stars. 
An additional analysis could be to calculate the mean star ratings on the reviews of each program.
