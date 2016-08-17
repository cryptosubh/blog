---
layout: post
title: The Curse of Dimesionality
---

Generalizing to higher dimensions is one area where mathematicians have usually excelled.  While others fear what they cannot visualize, 
mathematicians bravely add another coordinate or change a two to a three and BOOM! 

I've always been fascinated by proofs that *don't* generalize -- problems where we can perfectly characterize everything that is 
happening in two, three, or maybe even four dimensions, and after that [have no idea] (https://en.wikipedia.org/wiki/Kissing_number_problem).

In statistics, there are more methods than theorems, and sometimes methods that are powerful in low dimensions have much less predictive power in higher dimensional scenarios.  Statisticians call this phenomenon the curse of dimensionality, at least they understand precisely why additional dimensions can make problems nearly unsolveable:  

Consider the following set-up.  We have an n-dimensional independent variable x and will use it to predict a one-dimensional variable y.  For simplicity's sake, suppose each coordinate of x is between 0 and 1.  We are given a data set of m > n observations (x, y). 
