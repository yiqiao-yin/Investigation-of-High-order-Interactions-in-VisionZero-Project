# Investigation of High-order Interactions in VisionZero Project

<p align="center">
  <img width="1000" src="https://github.com/yiqiao-yin/Investigation-of-High-order-Interactions-in-VisionZero-Project/blob/master/figs/background.gif">
</p>

This project investigates the higher-order interactions in VisionZero Traffic Dataset

# Introduction

This project explores VisionZero Traffic Dataset, a joint project with Department of Transportation (DOT) in New York City. We are particularly motivated to investigate what may be the potential explanation for fatalities or injuries. In doing so, we deliver executable solutions for the policy makers at DOT to make better judgments for traffice in New York City.

In the context of big data such as VisionZedro project, good prediction is essential. Conventional approaches to prediction problems rely on trial and error search to evaluate models and machine learning algorithms through cross-validation may face challenges when data sets do not have sufficient sample size. The above direction may guide analysis to less-predictive variable sets due to overfitting in training set. 

# Data

We are looking at a variety of treatments executed by DOT in the past since 2002. The treatments are exposed in tree-based structures. For example, in streetscape elements, we may have Slow Turn Wedge interacting with Slow Turn Box as well as Right Turn Signal. We have also have Bike Lane and Raised Crosswalk together imposing an impact to the ongoing traffic. 

We collect and clean up a list of these treatments and simply mark them treatment 1, 2, ..., and so on. Each treatment in binary form so they are coded as 1 if there exists one and 0 otherwise.

# Lab Procedure

The following section we search for an algorithm to further explore our target, Attrition, which is measured by 0 if the employee stays and 1 if the employee leaves. The task is to deliver a solution, a trainable machine, such that we can predict a new candidate's probability of Attrition with high accuracy rate.

We test screened and engineered data set using common machine learning algorithms such as Bagging or Bootstrap Aggregation, Gradient Boosting Machine, Naive Bayes, Linear Model or Least Squares, Tree-based Algorithms (RF, iterative RF, Bayesian Additive Regression Tree or BART).

# Conclusion

After careful investigation of VisionZero Dataset, we proposed a generalized search algorithm to detect high-order interactions in this dataset as a screening technique to target correct model specification. This allows to achieve high performance for common machine learning algorithms.
