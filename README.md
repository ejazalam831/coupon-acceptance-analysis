# Coupon Acceptance Analysis

## Project Overview

This project analyzes factors influencing coupon acceptance rates for different types of coupons, with a focus on bar and coffee house coupons. The goal is to distinguish between customers who accepted driving coupons versus those who did not.

## Data Source

The data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. It describes different driving scenarios and asks whether the driver would accept a coupon.

## Key Findings

### Overall Coupon Acceptance

- The overall coupon acceptance rate is 56.76%.

- Restaurant(<20) coupons are the most common, followed by Coffee House coupons.

- Carry out & Take away coupons have the highest acceptance rate.

### Bar Coupon Analysis

- Bar coupon acceptance rate: 41.00%

- Frequent bar-goers (>3 times a month) are much more likely to accept bar coupons (73.2% vs 37.0%).

- Drivers over 25 who frequently go to bars have a significantly higher acceptance rate (67.6% vs 33.3%).

### Coffee House Coupon Analysis

- Coffee House coupon acceptance rate: 49.86%

- Frequent coffee drinkers (≥4 times a month) are more likely to accept coupons (67.5% vs 44.9%).

- Acceptance rates are highest in the morning (64.0% at 10AM) and lowest in the evening (41.1% at 6PM).

- Younger drivers, specially those below 21, have the highest acceptance rate (69.7%).

## Recommendations

1. Implement targeted marketing strategies based on customer segments.

2. Develop time-based promotional strategies.

3. Create loyalty programs to encourage more frequent visits.

## Notebook

For a detailed analysis, please refer to the Jupyter Notebook: https://github.com/ejazalam831/coupon_acceptance_analysis/blob/main/coupon_acceptance_analysis.ipynb

## Tools Used

- Python

- Pandas

- Matplotlib

- Seaborn

## Future Work

- Incorporate machine learning models for predictive analysis.

## Acknowledgments

- UCI Machine Learning Repository for providing the dataset.
