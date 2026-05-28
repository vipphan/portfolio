## Notebook
https://github.com/vipphan/portfolio/blob/main/prompt.ipynb

## Tools & Libraries used
Python
Pandas
NumPy
Matplotlib
Seaborn

## Analysis
### Part 1: Bar Coupons
We filtered the dataset to only bar coupons and explored the following:

Frequency of bar visits — Drivers who visited bars more than 3 times a month accepted at ~76%, compared to ~37% for those who visited 3 or fewer times — a ~39% gap.
Age + frequency — Drivers over 25 who go to bars more than once a month accepted at ~69%, compared to ~34% for all others.
Passenger type — Drivers without kid passengers who go to bars more than once a month accepted at ~70%.
Combined factors — Grouping by frequency, passenger, marital status, and age showed acceptance rates consistently in the 69–72% range for frequent bar-goers.

Hypothesis: Drivers who accept bar coupons tend to be frequent bar-goers over the age of 25 who do not have kids in the car. The strongest predictor of bar coupon acceptance is how often the driver already visits bars.

### Part 2: Carry Out & Take Away Coupons
Carry out coupons had the highest overall acceptance rate in the dataset at ~74%. We explored the following factors:

Frequency of carry out orders — Frequent vs infrequent carry out customers showed only a ~3% gap in acceptance rates, suggesting frequency is not a strong predictor for this coupon type.
Time of day + destination — Drivers heading home at 6PM accepted at ~82%, compared to ~66% for those heading to work at 7AM.
Passenger type — Drivers heading home at 6PM alone accepted at ~82%, compared to ~78% with a partner — a small difference suggesting passenger type is not a major factor.
Weather — Sunny weather had the highest acceptance rate at ~76%, while rainy weather dropped to ~61%, which is counterintuitive given that bad weather might be expected to increase takeout demand.

Most likely to accept: Driver heading home alone on a sunny evening at 6PM → ~82% acceptance rate
Least likely to accept: Driver heading to work on a rainy morning at 7AM with kids in the car → ~50% acceptance rate


## Key Findings
For bar coupons, frequency of bar visits and age are the strongest predictors of acceptance.
For carry out coupons, time of day and destination are the strongest predictors, while frequency of orders matters very little.
Carry out coupons are broadly popular — even the least favorable profile still has a ~50% acceptance rate.
Weather plays a surprising role in carry out coupon acceptance, with rainy weather reducing acceptance despite intuitive expectations.


## Recommendations
Deliver carry out coupons in the early evening (~6PM) when drivers are heading home from work.
Prioritize coupon delivery on sunny days, as acceptance rates are notably higher.
For bar coupons, target frequent bar-goers over the age of 25 for the highest acceptance rates.
