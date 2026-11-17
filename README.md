# Will the Customer Accept the Coupon?

## Overview

This project explores a dataset from the UCI Machine Learning Repository, collected via Amazon Mechanical Turk surveys. The goal is to understand what factors influence whether a driver will accept a coupon delivered to their cell phone while driving.

## Dataset

The dataset contains 12,684 survey responses describing driving scenarios (destination, time, weather, passengers) and whether the driver accepted a coupon. Coupons fall into five categories: bars, coffee houses, carry out & takeaway, less expensive restaurants (under $20), and more expensive restaurants ($20-$50).

## Key Findings

### Overall Acceptance
- Approximately 57% of all coupons were accepted across all categories.

### Bar Coupons
- Drivers who visit bars more than 3 times per month accepted bar coupons at a significantly higher rate than those who visit 3 or fewer times.
- Drivers over 25 who go to bars more than once a month had higher acceptance rates than others.
- Drivers without kid passengers and not in farming/fishing/forestry occupations who visit bars regularly showed elevated acceptance.
- Younger drivers (under 30) who are regular bar-goers were especially likely to accept.

### Coffee House Coupons (Independent Investigation)
- Visit frequency is the strongest predictor of acceptance — regular coffee house visitors accept at much higher rates.
- Morning coupons (10AM) have higher acceptance than evening coupons.
- Drivers with friends as passengers accept more than those driving alone or with kids.
- Longer coupon expiration windows (1 day vs 2 hours) lead to higher acceptance.
- Drivers with no urgent destination are more receptive.

## Recommendations
- **Target frequent visitors** for each coupon type for the highest conversion rates.
- **Timing matters**: deliver coffee coupons in the morning, bar coupons in the evening.
- **Consider passenger context**: avoid bar coupons when kids are in the car.
- **Use longer expiration windows** to give drivers flexibility and increase acceptance.

## Files
- `prompt.ipynb` — Jupyter notebook with full analysis and visualizations
- `data/coupons.csv` — Dataset

## Link to Notebook
[View the Jupyter Notebook](prompt.ipynb)
