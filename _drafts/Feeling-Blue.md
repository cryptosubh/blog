---
layout: post
title: Feeling Blue
---

In statistics, the acronym BLUE stands for Best Linear Unbiased Estimator.  For a while I didn't know this and wondered why the stats paper I was reading kept using capitalized colors to describe a regression.  

What exactly is meant by 'unbiased'?  The bias (or bias function) of an estimator is the difference between this estimator's expected value and the true value of the parameter being estimated.  An estimator or decision rule with zero bias is called unbiased.  An unbiased estimator may wildly overshoot or undershoot on any particular sample, but over many samples, large positive errors will cancel out with large negative errors and the average error will tend towards zero.

So which unbiased estimator is the best? The one which varies the least from zero on any given sample is the best -- that is, the one with the lowest MSE is best.

The **Gauss-Markov Theorem** states that under certain conditions, the ordinary least squares regression is BLUE. 

The text that inspired this post is an 80-page paper called *Understanding Regression Assumptions* by William D. Berry.  If you care about understanding every single detail of regressions, I can't recommend it strongly enough.  He uses a lot of equations, but also somehow explains everything in an extremely intuitive manner.   
