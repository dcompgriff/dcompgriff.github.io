---
permalink: /portfolio/11
title: "NBA Basketball Health Prediction Using Advanced Wearable Sensors"
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
* Athletics teams need to understand the capabilities of their players, and how their players bodies are being affected by their activity routines. A novel way of measuring overall load on the body of an athlete is to measure the para-sympathetic nervous system response. Given this signal, many questions arise such as ‘what affects this’, ‘how are my athletes doing’, ‘who is improving and who isn’t’, and ‘what can I do to make sure they are ready to go?’.

## Solution: 
* Develop an analysis suite to understand, quantify, and predict the health sensor metrics of a team of players. This requires a multi-variate analysis of various health sensor variables including breath-rate, heart rate, pule ox, ECG, accelerometer, and more static variables like player position, weight, etc… This also requires the proper fusion of time series data with static data, with a small amount of data points and a high amount of variation, as well as distinct confounding factors. 

## Methods:
* Classical machine learning modeling methods (Classification and statistical such as bayes nets), as well as classical Frequentist (ANOVA, non-parametric tests, etc…) and more modern Bayesian statistical methods (Credible intervals, hierarchical modeling, etc…) were used to determine the relationships between variables, as well as to predict and forecast health sensor metrics.

## Frameworks and Platforms:
* Python, scikit-learn, pymc3, statsmodels

## Outcomes:
* Developed many statistical inference models and generated statistical insights reports detailing the associations between sensors, the predictions for sensors, and strategies for optimally affecting the value of those sensors.






























