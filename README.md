# Amazon Vine Analysis

## Overview of the Analysis
The purpose of our analysis is to look at video game reviews on Amazon to determine if they are biased by the Amazon Vine reviewer program. We will use database tools and pyspark to accomplish this analysis.

## Results
We find that out of 40,565 helpful video game reviews on Amazon, only .2% are from Vine program reviewers. Those Vine reviewers give a 5 star rating 51% of the time. Meanwhile, non-Vine reviewers only give 5 star ratings 38.7% of the time. 

## Summary
It is clear from our sample that Vine reviewers are as much as 13% likely to rate a video game with 5 stars. Further analysis is recommended. One thing of interest would be to use both helpful and non-helpful reviews. Or perhaps determine if Vine reviewers are less likely to create helpful reviews. Also we could use a different metric instead of 5 star reviews. Maybe average review would be more enlightening. An exploration of the distribution of reviews for vine and non-vine reviewers would also be very interesting. Do they both follow a sort of normal distribution? Or do either of them experience sudden jumps between 4 and 5 stars for example.
