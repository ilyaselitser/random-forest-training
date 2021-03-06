
# Random Forests Training

***Random forest*** are a very popular “out-of-the-box” learning
algorithm that enjoys good predictive performance. This
[tutorial](http://bit.ly/random-forests-training) covers the underlying
concepts of random forests, what to consider when tuning them, and an
illustrative example of implementing them with the R package **ranger**.

## Learning Objectives

After completing this workshop, learners will understand…

1.  how single decision trees work
2.  why bagging improves upon single trees
3.  why random forests improve upon bagging
4.  how to tune a random forest model
5.  how to implement random forests with R

## Prerequisites

Most of this training emphasizes the concepts behind random forests.
Very little programming or mathematical prereqs are required. The last
section demonstrates an implementation with the R programming language
and assumes fundamental knowledge of using R; however, you should be
able to interpret the results regardless of understanding the code. If
you are unsure whether you meet these prerequisites, feel free to reach
out and ask [Brad Boehmke](mailto:bradleyboehmke@gmail.com).

## Overview

The following is an outline of the material covered in this training:

  - Intro
  - Decision trees
      - Idea of a single decision tree
      - How a decision tree is grown
      - Understanding decision boundaries
      - How to minimize overfitting
      - Strengths & weaknesses
  - Bagging
      - Idea of of bootstrap aggragating
      - Limitations of bagging
  - Random Forests
      - Adding split-variable randomization
      - Out-of-bag
      - What and how to tune
      - How variable importance is computed
  - Implementation (in R)
      - Basic implementation
      - Tuning
      - Feature importance
      - Feature effects
      - Where to learn more
