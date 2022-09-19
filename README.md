# amazon_vine_analysis

## Overview

### Background

This analysis was requested by SellBy, a company that was considering participating in the paid Amazon Vine program. SellBy wanted to determine if Amazon Vine participants were more likely to leave favorable reviews than non-paid consumers. 

### Process

This analysis was completed using PySpark, Amazon Web Services, and PostgreSQL. The data was collected from reviews left on pet products on Amazon, sorted by whether the consumer had participated in the Vine program or not.

## Results

### Summary

The analysis showed that:
- There were significantly more non-Vine reviews than Vine reviews (37,840 vs 170)
- There were 20,612 non-Vine 5-star reviews, compared to only 65 Vine 5-star reviews
- The percent of 5-star reviews was higher for non-Vine reviews (55%) than for Vine reviews (38%)

### Full Results

![Full Results of Analysis](https://github.com/ehalprin/amazon_vine_analysis/blob/main/Summary_Table.png)

## Summary

### Positivity Bias in Paid Reviews?

Based on the results, there does not seem to be any positivity bias in the Vine program, as the percent of 5-star reviews in the Vine program were lower than 5-star reviews for non-Vine participants. Because there were so many unpaid reviewers compared to paid reviewers, even if Vine participants did have positivity bias, it might not have an effect on the overall rating of products, unless you were willing to pay for a lot of reviews.

### Further Analysis

Further analysis should look at the average overall rating of reviews that were paid for vs. unpaid, to determine if Vine participants enjoyed products less than non-Vine participants, or if they simply did not rate the products as 5-stars (perhaps to avoid the perception of bias!).
