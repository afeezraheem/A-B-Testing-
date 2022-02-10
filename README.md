# A/B-Testing: Implemented in Python

A/B testing is arguably one of the most popular applications of machine learning and statistics in the real world. It is often used in comparison between two versions of the same marketing asset, such as a web page, promo ad or even new product features, that you expose to equal halves of your audience. Based on conversion rates or other metrics, you can decide which one performs best.

Retention analysis can help companies figure out why and how their customers are leaving while offering valuable insight into how to change it. This analysis will emable companies uncover insights such as:

-Why customers are churning.
-When customers are more likely to leave.
-How churning affects your bottom line.
-How to improve your retention strategies.

Overall, this analysis allows you to see how well your customer retention efforts are working. Without it, you may end up spending your marketing budget inefficiently.


In this project, I attempted to test the conversion rates of 2 groups (treatment and control groups) exposed to different landing pages. I collected publicly available data set, comprising 29,000 records, from Kaggle for this analysis. My goal was to evalaute and test the validity of the null hypothesis (i.e. the difference in probability of conversion between the 2 groups is negligible)

Interestingly, as I found out, it turns out that probability of conversion is higher among the control groups than the treatment group, but the difference is not significant enough to reject the null hypothesis

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Terms for viewers who might be viewing my work:

--Baseline rate — an estimate of the metric being analyzed before making any changes

--Practical significance level — the minimum change to the baseline rate that is useful to the business, for example an increase in the conversion rate of 0.001% may not be worth the effort required to make the change whereas a 2% change will be.

---While statistical significance shows that an effect exists in a study, practical significance shows that the effect is large enough to be meaningful in the real world. Statistical significance is denoted by p-values whereas practical significance is represented by effect sizes.

--Confidence level — also called significance level is the probability that the null hypothesis (experiment and control are the same) is rejected when it shouldn’t be

--Sensitivity is the probability that the null hypothesis is not rejected when it should be

--The standard normal distribution, also called the z-distribution, is a special normal distribution where the mean is 0 and the standard deviation is 1. Any normal distribution can be standardized by converting its values into z-scores. Z-scores tell you *how many standard deviations from the mean each value lies*.

--Not all distributions are normal and not all normal distributions are standard - standard has 1 standard deviation and mean of 0. The z score from your experiment is just a multiple of the standard which is taken to be 1 and mean of 0

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Data source : https://www.kaggle.com/zhangluyuan/ab-testing

Reference material :

leeds.ac.uk/educol/documents/00002182.htm

https://stackoverflow.com/questions/20864847/probability-to-z-score-and-vice-versa

https://stackoverflow.com/questions/20864847/probability-to-z-score-and-vice-versa?fbclid=IwAR2OhAyWytruv8fOhwEdZWppMJedXZNsSDOTxMxkmuAErakXSNz8xDtP-EE

https://www.statsmodels.org/stable/generated/statsmodels.stats.power.NormalIndPower.html


