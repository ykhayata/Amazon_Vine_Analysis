# Amazon Vine Analysis

## Overview

The purpose of this project is to perform an analysis on Amazon reviews that are written by members of the Amazon Vine program. To accomplish this, we used data that specifically pertained to the video game subcategory of Amazon, and performed an in-depth analysis on video game reviews. We performed an ETL on the video game data with the help of Amazon Web Services (AWS), Google Colabo, PySpark, and PostgreSQL. We then got into a little bit more of the specifics, mainly to determine whether or not there was any positibity bias for these Amazon reviews in the Vine Program.

## Our Results

To optimize our analysis we needed to answer a few key questions:

1: How many Vine reviews and non-Vine reviews were there?
2: How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
3: What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

Our Answers:

1: There is a total of 40,565 revies, 94 vine reviews and 40,471 non-vine reviews.

<img width="490" alt="total_reviews" src="https://user-images.githubusercontent.com/74481469/111941253-df852980-8a8d-11eb-9b98-de530af4bb4a.png">

2: In total, there were 15,711 5-star reviews (48 5-star vine reviews and 15663 5-star non-vine reviews). 

<img width="585" alt="5star_reviews" src="https://user-images.githubusercontent.com/74481469/111941324-0cd1d780-8a8e-11eb-9ad7-5bcd14b34fdf.png">

3: 51.06% of paid reviews are 5-stars where as only 38.7% of unpaid reveiws are 5-stars.

<img width="707" alt="5star_reviews_percentage" src="https://user-images.githubusercontent.com/74481469/111941403-37239500-8a8e-11eb-8915-47028ec19ce2.png">

## Summary 

After a deep analysis and examing the results, we can strongly conclude that there IS a positivity bias for video gamereviews in the Vine program. Though the non-vine sample size was very large, the vine sample size was only 94 entries. Because 94 entires is a rather low number to sample with, this could lead us to a less signifcant result. If we were to add to the current analysis, I'd love to go even further and find out whether or not the "verified_purchase" column had any effect on whether or not the customer made the purchase. After conducting this analysis we can get a better gauge on whether or not there is positivity bias for reviews. 



