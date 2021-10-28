# Amazon Vine Analysis

## Overview
Amazon's Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

### Purpose
The purpose of this analysis is to determine whether or not there is any bias for reviews in Amazon's Vine program. Specifically, this analysis looks into a dataset of video game reviews.

## Results

### Total Reviews
There are 572,411 non-vine reviews.
![image name](https://github.com/PirateSuit/Amazon_Vine_Analysis/blob/main/images/unpaid_dataframe.png)

Comparatively, there are 1,757 vine reviews.
![image name](https://github.com/PirateSuit/Amazon_Vine_Analysis/blob/main/images/paid_dataframe.png)

Put another way, vine reviews make up only .003% of total reviews.  

### 5-Star Reviews
There are 291,135 5-star ratings for non-vine reviews, and 700 5-star ratings for vine reviews.
![image name](https://github.com/PirateSuit/Amazon_Vine_Analysis/blob/main/images/5star_count.png)

### 5-Star Percent
Percentages of total reviews that were rated 5-stars for non-vine and vine were 51% and 40%, respectively.
![image name](https://github.com/PirateSuit/Amazon_Vine_Analysis/blob/main/images/5star_percent.png)

## Summary
People who were in the vine program were 11% less likely to give a game a 5-star rating. An initial assumption might be that people who were receiving items for free would be more likely to rate them higher. But in this case, as the company providing the free items is not the company the reviews are being delivered to, that is less likely. To take that further, we could surmise that the vine reviewers could potentially be more in-depth in their evaluations and more likely to be critical, thus returning fewer 5-star reviews.

### Additional Analysis
The dataset included plenty of additional information that wasn't delved into here. One particular factor that would be useful to include in a future analysis would be 'verified purchase.' It would be interesting to see how the ratings compared, as it seems that people that had put down their own hard-earned money for an item would be more likely to give it a more thoughtful and informed review. Likewise, it's hard to place as much value on someone's review for an item that they do not themselves own and have perhaps never even used.
