# Amazon_Vine_Analysis
Module 16 - big data

## Overview
This project analyzises the amazon vine program reviews for US health products to determine if there is a positivity bias among the vine members.

Resources: AWS, postgres, google colab, pyspark, pgadmin, amazon review datasets provided


## Results

### Reviews in the Numbers

#### - How many vine reviews and non-Vine reviews were there?

Out of 121,360 helpful total reviews, 497 of them are paid and 120,863 are unpaid.

![image](https://user-images.githubusercontent.com/94019661/162814107-f1040dcf-79cd-4990-a55d-b7667f6d023f.png)


### - How many vine reivews were 5 stars? How many non-Vine reviews were 5 Stars?

Out of 74,690 total 5 star reviews, 220 of them are paid and 74,470 are unpaid.

![image](https://user-images.githubusercontent.com/94019661/162814128-7669d18d-4f2d-4dac-ac5f-f75e8a3d1c3a.png)


### - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

44.3 % of the paid vine reviews are 5 stars.
61.6 % of the unpaid amazon reviews reviews are 5 stars.

![image](https://user-images.githubusercontent.com/94019661/162814136-c4065dee-2a6a-4be0-9e50-9210e0a52111.png)


## Summary
### - Note on any positivity bias for reviews in the Vine program?  

Because the vine program had considerably less reviews than non paid reviews, less that 0.05% of unpaid reviews and 44.3% were 5 stars vs 61.6% of the unpaid 5 star reviews there is little evidence to suggest that there is not positivity bias at play with this dataset.

### - One additional analysis that you could do with the dataset to support your statement.

One additional analysis to include is to group the products into price cohorts and see if the relationship % of 5 star votes remain constant or if price affects the review process of health products on amazon and what role price plays into the reviews.
