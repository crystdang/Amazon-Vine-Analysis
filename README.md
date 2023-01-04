# Module 17 Challenge: Amazon Vine Analysis - Big Data
## by Crystina Dang using Google Colaboratory, pgAdmin 4 v6.14, Pyspark


### Overview of the analysis:
The purpose of this analysis is to summarize the findings from Amazon_Vine_Analysis.ipynb


### Results: 
Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


### Summary: 
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

*Below is an image of the DataFrame created where there are 20 or more total votes:*
![This is an image](https://github.com/crystdang/Amazon-Vine-Analysis/blob/main/Images/votes.png)

*Below is an image of the DataFrame created where the percentage of helpful_votes is equal to or greater than 50%:*
![This is an image](https://github.com/crystdang/Amazon-Vine-Analysis/blob/main/Images/top_votes.png)

*Below is an image of the DataFrame created where there is a Vine review:*
![This is an image](https://github.com/crystdang/Amazon-Vine-Analysis/blob/main/Images/paid.png)

*Below is an image of the DataFrame created where there is not a Vine review:*
![This is an image](https://github.com/crystdang/Amazon-Vine-Analysis/blob/main/Images/unpaid.png)

*Below is an image of the DataFrame created of 5-star reviews with a Vine reviews and to the total count:*
![This is an image](https://github.com/crystdang/Amazon-Vine-Analysis/blob/main/Images/top_paid.png)

*Below is an image of the DataFrame created of 5-star reviews without a Vine reviews and to the total count:*
![This is an image](https://github.com/crystdang/Amazon-Vine-Analysis/blob/main/Images/top_unpaid.png)

MISSING: The total number of reviews, the number of 5-star reviews, and the percentage 5-star reviews