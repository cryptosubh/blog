---
layout: post
title: The Bias-Variance Tradeoff
---

The bias-variance tradeoff, like the curse of dimensionality, summarizes one of the central difficulties in modelling and statistical prediction. The more statistics and machine learning I learn, the more I understand the bias-variance tradeoff in new and different ways. 

You are probably familiar with various measures to assess the prediction accuracy of a particular model, such as R-squared or the residual sum of squares (RSS). 

Another measure that statisticians care about is the mean squared error (MSE), or the average squared residual, which is just the RSS divided by the sample size.  It turns out that the MSE can be decomposed into three components:  
- irreducible error
- variance
- squared bias
