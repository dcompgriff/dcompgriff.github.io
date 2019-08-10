---
permalink: /portfolio/8
title: "Sales Analysis and Forecasting"
excerpt: ""
layout: single
layouts_gallery:
  - url: /assets/images/mm-layout-splash.png
    image_path: /assets/images/mm-layout-splash.png
    alt: "splash layout example"
  - url: /assets/images/mm-layout-single-meta.png
    image_path: /assets/images/mm-layout-single-meta.png
    alt: "single layout with comments and related posts"
  - url: /assets/images/mm-layout-archive.png
    image_path: /assets/images/mm-layout-archive.png
    alt: "archive layout example"
header:
  overlay_image: /assets/images/unsplash-image-1.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background

last_modified_at: 2018-06-04T12:04:24-04:00
toc: true
author_profile: true

---

## Problem: 
* Cisco needs to be able to effectively forecast it’s sales every quarter on a product by product basis, and needs to understand the highest and lowest bounds it can expect in terms of revenue to make strategic decisions about the companies investment and planning.

## Solution: 
* Develop an aggregated sales forecasting model that uses the aggregated time series sales over each week of a quarter to forecast the sales for each week in the next quarter. Traditional time series regression methods were initially applied such as ARIMA methods and variations of these traditional simple stochastic process methods of forecasting. However, these methods failed to perform well, and were ultimately unable to fit our data set given the small number of points, high complexity of the seasonal trend. So instead, the fundamental approach of modeling trend, and seasonality separately was used. The trend was modeled using a robust linear regression method (Using Huber Loss) as sales motions had high variance outliers near the end of quarters that biased the trend of traditional regression methods. The seasonal component of the series was modeled using gaussian process regression method, which provided upper and lower High Density Intervals (HDI) quantifying the 95% credible interval for sales each week to lie in.


## Methods:
* Huber linear regression, Gaussian Process Regression, ARIMA models, various forms of EDA

## Frameworks and Platforms:
* Python, scikit-learn, pymc3, statsmodels

## Outcomes:
* Developed a set of reliable sales forecasting models, and a strategic forecasting report about the forecast with upper and lower forecast bounds.






























