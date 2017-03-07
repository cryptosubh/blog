---
layout: post
title: The Bias-Variance Tradeoff
---

The bias-variance tradeoff, like the curse of dimensionality, summarizes one of the central difficulties in modelling and statistical prediction. The more I read about statistics and machine learning, the more I understand the bias-variance tradeoff in new and different ways. 

You are probably familiar with various measures to assess the prediction accuracy of a particular model, such as R-squared or the residual sum of squares (RSS). 

Another measure that statisticians care about is the mean squared error (MSE), or the average squared residual, which is just the RSS divided by the sample size.  It turns out that the MSE can be decomposed into three components:
- irreducible error
- variance
- squared bias  

The irreducible error comes from noise that we are not modelling and is not of interest to us.  

It's easy to reduce either bias or variance separately by choosing a particular predictor function.  If I choose a predictor that passes through all the points in the data set, then I've created an estimator with a low but not zero bias (some bias is introduced depending upon how I connect up the data points).  So we see that reducing either variance or bias separately is trivial; the art lies in minimizing the sum.  
