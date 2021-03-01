# A/B-Testing: Implemented in Python

A/B testing is arguably one of the most popular applications of machine learning and statistics in the real world. It is often used in comparison between two versions of the same marketing asset, such as a web page, promo ad or even new product features, that you expose to equal halves of your audience. Based on conversion rates or other metrics, you can decide which one performs best.


In this project, I attempted to test the conversion rates of 2 groups (treatment and control groups) exposed to different landing pages. I collected publicly available data set, comprising 29,000 records, from Kaggle for this analysis. My goal was to evalaute and test the validity of the null hypothesis (i.e. the difference in probability of conversion between the 2 groups is negligible)

Interestingly, as I found out, it turns out that probability of conversion is higher among the control groups than the treatment group, but the difference is not significant enough to reject the null hypothesis).

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Terms for viewers who might be viewing my work:

--Baseline rate — an estimate of the metric being analyzed before making any changes

--Practical significance level — the minimum change to the baseline rate that is useful to the business, for example an increase in the conversion rate of 0.001% may not be worth the effort required to make the change whereas a 2% change wilfl be

--Confidence level — also called significance level is the probability that the null hypothesis (experiment and control are the same) is rejected when it shouldn’t be

--Sensitivity is the probability that the null hypothesis is not rejected when it should be

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Data source : https://www.kaggle.com/zhangluyuan/ab-testing

Reference material :

leeds.ac.uk/educol/documents/00002182.htm

https://stackoverflow.com/questions/20864847/probability-to-z-score-and-vice-versa

https://stackoverflow.com/questions/20864847/probability-to-z-score-and-vice-versa?fbclid=IwAR2OhAyWytruv8fOhwEdZWppMJedXZNsSDOTxMxkmuAErakXSNz8xDtP-EE

https://www.statsmodels.org/stable/generated/statsmodels.stats.power.NormalIndPower.html


