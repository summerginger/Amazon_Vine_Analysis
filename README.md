# Amazon_Vine_Analysis
## Overview of the analysis
The project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.


### The purpose 
The purpose of this analysis is to allow manufacturers and publishers to receive reviews for their products. The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics. The review product focused on homes.
## Results

•	Total number of reviews of vine were 1,395, non-vine reviews were 84,949.

•	624 Vine reviews were 5 stars and 41,265 non-Vine reviews were 5 stars.

•	Approximately 45% Vine reviews were 5 stars  and 49% of non-Vine reviews were 5 stars.
## Summary
According to the results, There is a slightly high number of negtive bias for reviews in the vine program. Where 49% of the reviews in the non-vine program were 5 stars reviews whereas the percentage in the vine reviews is about 45%. Additionally, we could further analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

![image](https://user-images.githubusercontent.com/82733723/138495395-3ceb03b0-4a1a-4c34-a60a-189c1752a00e.png)

![image](https://user-images.githubusercontent.com/82733723/138495301-15c9dbe9-6989-41c1-b9dc-4bec19edfc9b.png)




### Technologies
Google Colab Notebook, PostgreSQL 13.4, pgAdmin 4, AWS
![Store environmental variable](https://user-images.githubusercontent.com/82733723/138494753-9fa43853-ae8c-43cb-b3b4-233713aa6cf4.png)

