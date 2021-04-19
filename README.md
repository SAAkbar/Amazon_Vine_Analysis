# Amazon_Vine_Analysis

## Purpose
The purpose of this assignment was to analyze the reviews written by the paid Amazon Vine program and to see if there was any bias in them. To do this we needed to choose one of the 50 datasets and then using PySpark we had to preform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. After this we used PySpark to determine if there were any bias in them.

## Results
•	Total Vine Reviews = 94

•	Total Non-Vine Reviews = 40471

•	5-Star Vine Reviews = 48

•	5-Star Non-Vine Reviews = 15663

•	5-Star Vine Percentage = 51.06382978723404%

•	5-Star Non-Vine Percentage = 38.701786464381904%


![image](https://user-images.githubusercontent.com/76131315/115172283-eefa9100-a092-11eb-9026-e7877e15567d.png)


## Summary
Based of the two percentages, it looks like there is a positive bias as slightly more than half (51.06%) of the Vine voters gave 5 stars compared to the 38.7% of regular voters who gave 5 stars. Seeing as we have only looked at the two results it should be logical to do more or any analysis like getting the averages of the star rating for Vine and Non-Vine votes or even getting a histogram to check is the distribution of the star rating for Vine and Non-Vine votes to see if there is a positive distribution or a negative one or neutral.
