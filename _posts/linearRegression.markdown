---
layout: post
title: Linear Regression
date: 2020-10-20
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: i-rest.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [MachineLearning, LinearRegression]
---


y = B0 + B1 × x
Pros: Easy to interpret results, computationally inexpensive
Cons: Poorly models nonlinear data
Works with: Numeric values, nominal values


General approach to regression
1.	Collect: Any method.
2.	Prepare: We’ll need numeric values for regression. Nominal values should be mapped to binary values.
3.	Analyze: It’s helpful to visualized 2D plots. Also, we can visualize the regression weights if we apply shrinkage methods.
4.	Train: Find the regression weights.
5.	Test: We can measure the R2, or correlation of the predicted value and data, to measure the success of our models.
6.	Use: With regression, we can forecast a numeric value for a number of inputs. This is an improvement over classification because we’re predicting a continuous value rather than a discrete category.
