# Amazon_Vine_Analysis

## Purpose

The purpose of this project is to determine if there is any bias toward favorable reviews from Vine members who test mobile apps. In order to achieve this we must complete the ETL process on the large dataset (there are over 5 million reviews for these mobile apps). Then we want to filter the data to understand if there is any bias with these reviews.

## Results

After filtering the data we can see that Amazon may not utilize the Vine program for its mobile app reviews. Of the 129,516 reviews that were left when filtered, 0 were members of the vine program. After further investigation of the 5 million reviews, 0 were members of the vine program.

![image](https://user-images.githubusercontent.com/102189324/182045419-3507dbea-73e0-4d2f-bba1-5967836dac9c.png)


![image](https://user-images.githubusercontent.com/102189324/182045367-d4114f8a-98eb-49e9-9702-6fb00bcb8641.png)


However, we can further analyze the non-vine reviews affectivley.

![image](https://user-images.githubusercontent.com/102189324/182045436-192ffff6-9fc9-480e-9f87-edfa78b24a97.png)


![image](https://user-images.githubusercontent.com/102189324/182045369-5f4517ed-0e06-4038-9bea-43c3a4d53851.png)


* We can see there were a total of 129,516 helpful non-vine reviews
* Of those 129,516 reviews, 59,278 reviews had 5-stars
* A little over 45% of the reviews had 5-stars

## Summary

Although our vine program data may be inconclusive, we can see that there may not be a huge bias with those who are not in the vine program. 45% of helpful reviews were from non-vine members. Almost half of these helpful reviews were from non-vine members, showing an almost even split.

Perhaps a better analysis for Mobile Apps would be to understand if a verified purchase has any effect on ratings and the percentage of 5-star ratings. People who have not downloaded the app may be paid promoters for the app, thus skewing the data and making these apps look better than they really are.
