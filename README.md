# Amazon_Vine_Analysis

A copy of the review ETL found [here](https://github.com/Mikeblanchard/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb) and the analysis [here](https://github.com/Mikeblanchard/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)

## Overview of Analysis 

The purpose of this project was to filter video game review ccontent and determine if Vine members were biased twoards 5 star reviews. We used pySpark to and AWS as well as Postgres to do this. 

## Results

- Initailly we sepaprated the dataframe into Vine and Non-Vine users:

![](https://github.com/Mikeblanchard/Amazon_Vine_Analysis/blob/main/Resources/Chal_16.png%20.png)

![](https://github.com/Mikeblanchard/Amazon_Vine_Analysis/blob/main/Resources/Chal_16-5.png%20.png)

- Then we looked at the total number of reviews and an edited "useful" number of reviews, as well as number of 5 star rating by group:

![](https://github.com/Mikeblanchard/Amazon_Vine_Analysis/blob/main/Resources/Chal_16-3.png%20.png)

- Finally we determined the number of 5 star reviews by group:

![](https://github.com/Mikeblanchard/Amazon_Vine_Analysis/blob/main/Resources/Chal_16-4.png%20.png)


## Summary

We found that 51% of reviews in the Vine program were 5 star, compared to 38.7%  for non-Vine users. This constitutes a bias in the Vine program. We would love to see rating system broken down by verified_purchase. Perhaps reviewers who actually bought the game have spent more time with it, and therefore had a more genuine opinion of the game, rather than someone who has only briefly played it. g
