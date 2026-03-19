# coupon_acceptance

A data science project analyzing factors that influence whether a driver accepts a coupon delivered to their phone while driving. Using survey data from the UCI Machine Learning Repository (collected via Amazon Mechanical Turk), the project explores how user attributes (age, income, habits), contextual attributes (weather, time of day, passengers), and coupon attributes (type, expiration) affect acceptance rates across five coupon categories: bars, coffee houses, carry out, and restaurants at two price tiers. The analysis involves data cleaning, handling missing values, statistical summaries, and visualizations using pandas, matplotlib, and seaborn.

[project notebook](prompt.ipynb)

## Bar Coupon Investigation

Investigating the acceptance rate of coupons for bars found that these coupons are some of the least popular, only 41.5% of people offered these coupons accepted them.

The investigation did, however, reveal which groups would be more likely to accept bar coupons, namely those who are at lease 25 years old, have no children and who already visit bars frequently.

## Coffee House Coupon Investigation

Coffee house coupons have a near-average acceptance rate of 49.63%, compared to 56.93% across all coupon types. frequent visitors who visit more than 3 times a month are more likely to accept.

The most surprising finding was that the "morning commuter coffee run" hypothesis was incorrect. Drivers heading to work accepted coffee house coupons at only 44.00%, lower than those heading to other destinations (51.31%). The highest acceptance rates were found at 10AM and 10PM when drivers had no urgent destination, suggesting that leisure time and schedule flexibility are stronger drivers of acceptance than the habitual need for morning coffee.

Based on these findings, coffee house coupon campaigns should focus on targeting customers during mid morning and late evening hours when they are not on a time sensitive commute.
