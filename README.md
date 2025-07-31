This project is part of Berkeley Haas program. The relevant datset is coupons,csv and the program to analyze the data is in prompt.ipyynb.

Some of the findings from the work include:

Data cleansing before analysis
------------------------------
1. Car column had only '108' non-nulls. Updated dataset to have 'do not drive' instead of nan. This will reduce number of drops for nan.
2. Data was clean other than few columns with null values. The rows with null values are dropped.
3. There was overall 4.77% data reduction post data cleansing stage.

Analysis outcomes
-----------------
1. Data suggests 56.9% users accepeted coupon.
2. Most coupons are from 'Coffee House' and there are around 1913 bar coupons which have clean data.
3. 41% bar coupons are accepted by users.
4. Users who went to bar less than 3 times in a month are 7 times more likely to accept 'bar' coupon than users who went more than 3 times.
5. Users who go to bar more than 3 times has a pattern. If their age is > 25, they will likely buy coupon compared to age <25.
6. Number of users #%% md
5. Use the same process to compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry.
6. More than 3 times visitor to bar accepted coupon and with no kids count:  833
7. More than 3 times visitor to bar accepted coupon and with not having occupation Farming et al:  858