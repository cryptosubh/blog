---
layout: post
title: The Curse of Dimesionality
---

Generalizing to higher dimensions is one area where mathematicians have usually excelled.  While others fear what they cannot visualize, 
mathematicians bravely add another coordinate or change a two to a three and BOOM! 

I've always been fascinated by proofs that *don't* generalize -- problems where we can perfectly characterize everything that is 
happening in two, three, or maybe even four dimensions, and after that [have no idea] (https://en.wikipedia.org/wiki/Kissing_number_problem).

In statistics, there are more methods than theorems, and sometimes methods that are powerful in low dimensions have much less predictive power in higher dimensional scenarios.  Statisticians call this phenomenon the curse of dimensionality, at least they understand precisely why additional dimensions can make problems nearly unsolveable:  

Consider the following set-up. We are given a data set of m observations (x, y), where each x has n coordinates, each y has one coordinate, and m > n.  For simplicity's sake, suppose each coordinate of x is between 0 and 1, so each x lies in the n-dimensional hypercube of side length one. 

For a given n-dim x*, we wish to predict the corresponding y*.  We do so by taking all the x's in our data set such that each coordinate value of x is within 0.1 of the corresponding coordinate value of x*.  Call this set X*.  Note that X* has a volume of at most (.2^n).  

So essentially the curse of dimensionality comes from the fact that the sequence of numbers {.2^n} converges to 0 - quickly. For more than four dimensions, we simply need too much data for this method to be feasible.  
