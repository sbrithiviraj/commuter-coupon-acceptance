# Project Title: 
Restaurant Coupon Acceptance Analysis for Commuters
# Description:
An exploratory data analysis on a UCI Machine Learning dataset and was collected via a survey on Amazon Mechanical Turk. Evaluating consumer responses to real-time, location based driving coupons depending on the time of dat, current weather, passanger types and coupon categoeris (less expensive restaurants (under \$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\$20 - $50)). Highlight the differences between customers who did and did not accept the coupons.
# Getting Started
## Code
[Click here for Jupyter Notebook Source Code](https://github.com/sbrithiviraj/commuter-coupon-acceptance/blob/main/prompt.ipynb "Git")
## Installing
To execute the code below libraries need to be installed
1. matplotlib
2. seaborn 
3. pandas
4. numpy
## Summary of Findings
### Overall Coupon acceptance ratio is 56%
![Overall coupon acceptance](/images/Coupon_acceptance_rate.png)
### Carryout coupon is the  most accepted coupon followed by cheap restaurant. Bar coupon is the least accepted coupon.
![Coupon Acceptance by Category](/images/Coupon_acceptance_rate_by_category.png)
### Most coupons were delivered and accepted when the weather was nice.
![Coupon Acceptance by temperature](/images/Coupon_acceptance_rate_by_temp.png)
### Deep Dive into Bar Coupons
***
### Acceptance ratio for frequent bar goers is more than 70% where as in frequent bar goers coupon acceptance ratio is less than 40%.
![Bar coupons acceptance by visiting frequency](/images/Bar_coupon_acceptance_rate_by_vist_freq.png)
### Frequest bar goers above 25 years old acceptance ration is almost 70% where as infrequent bar goers accept only little above 30%.
![Frequent bar goes above 25 YO](/images/Bar_coupon_acceptance_rate_by_vist_freq_age_GE25.png)
### Coupon acceptance ratio across 3 different categories below, we can clearly see the trend of frequent bar goers acceptance ratio is higher than any other group.
    Cat-1: go to bars more than once a month, had passengers that were not a kid, and were not widowed OR
    Cat-2: go to bars more than once a month and are under the age of 30 OR
    Cat-3: go to cheap restaurants more than 4 times a month and income is less than 50K.
![Three different categories](/images/Bar_coupon_acceptance_rate_by_3_cohorts.png)
### Deep Dive into Coffee House Coupons
***
### Acceptance ratio for coffee coupons are higher during rain and also around 10 Am and 2PM compared to any other times.
![Coffee acceptance weather and temp](/images/coffee_coupon_acceptance_rate_by_weather_time.png)
### Drivers travelling with friends are the most accepted group for coffee coupons followed by people travelling with partners.
![Coupons accepted by passenger type](/images/coffee_coupon_acceptance_rate_by_pass_type.png)
### Max acceptance ratio of coffee coupons  was around 50% but when we checked for coffee lovers the acceptance was gone up close to 80%
![Coffee lovers coupon acceptance by passenger type](/images/coffee_coupon_acceptance_rate_by_vist_freq_pass_type.png)
# Authors
Brithiviraj Shanmugam
# Version History
* **1.0** (2026-06-04)
    * Initial Version
* **1.0.1** (2026-06-04)
    * Added summary of findings to readme
# Acknowledgements
1. Requirement / idea is for practical application 1 in "Professional Certificate in Machine Learning and Artificial Intelligence" course by UC Berkely
2. [Simple readme template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc "Github")
3. [Markdown syntax](https://medium.com/analytics-vidhya/how-to-create-a-readme-md-file-8fb2e8ce24e3 "Medium") 
