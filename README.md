# Module 17 Challenge: Amazon Vine Analysis - Big Data
## by Crystina Dang using Google Colaboratory, pgAdmin 4 v6.14, Pyspark


### Overview of the analysis:

The purpose of this analysis is to summarize the findings from Amazon_Vine_Analysis.ipynb



### Results:

- Total reviews: 31,830
- Total Vine (paid) reviews: 285 (0.90%)
- Total non-Vine (unpaid) reviews: 31,545 (99.10%)

- Total 5-star reviews: 14,777
- Total Vine (paid) 5-star reviews: 163 (1.10%)
- Total non-Vine (unpaid) 5-star reviews: 14,614 (98.90%)


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

*Below is an image of the DataFrame created of the total 5-star reviews paid and unpaid and the percentage of the two types (paid vs unpaid):*
![This is an image](https://github.com/crystdang/Amazon-Vine-Analysis/blob/main/Images/summary.png)



### Summary: 

In summary, the difference in percentage of 5-star versus lower reviews (0.20%) are not substantial enough to be providing a positivity bias due to the Vine program, which proves its validity. 

An additional assessment that could be done with this dataset would be to further clean the dataset and ensure Natural Language is considered when reviews are considered helpful. Due to language barriers or quick keys, the helpful votes could be considered just positive reinforcement to negative reviews.