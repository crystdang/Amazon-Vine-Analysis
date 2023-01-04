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

DATA COLUMNS:
marketplace       - 2 letter country code of the marketplace where the review was written.
customer_id       - Random identifier that can be used to aggregate reviews written by a single author.
review_id         - The unique ID of the review.
product_id        - The unique Product ID the review pertains to. In the multilingual dataset the reviews
                    for the same product in different countries can be grouped by the same product_id.
product_parent    - Random identifier that can be used to aggregate reviews for the same product.
product_title     - Title of the product.
product_category  - Broad product category that can be used to group reviews 
                    (also used to group the dataset into coherent parts).
star_rating       - The 1-5 star rating of the review.
helpful_votes     - Number of helpful votes.
total_votes       - Number of total votes the review received.
vine              - Review was written as part of the Vine program.
verified_purchase - The review is on a verified purchase.
review_headline   - The title of the review.
review_body       - The review text.
review_date       - The date the review was written.
x
