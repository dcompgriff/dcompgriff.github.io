---
permalink: /portfolio/15
title: "Blood glucose prediction model"
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
* People with diabetes and even pre-diabetes need to monitor their blood glucose levels to ensure they don’t get too high. Yet, almost all methods today require the use of blood, and are reactionary. They simply tell you that your blood glucose levels are high once they’ve already in the dangerous region. They provide no warning, and thus no proactive way to manage blood glucose levels. Thus, there exists a need to provide proactive forecasts around blood glucose levels, and the need to do it in a non-invasive way.

## Solution: 
* Enter ‘Smart Connected Health’. This is a project that I and two other individuals worked on, whose goal was to forecast blood glucose levels as ‘normal’, ‘high’, and ‘dangerous’ using only off the shelf wearable senor data (accelerometer, HR, etc…) and meal macro-nutrient information (grams of carbs, sugars, protein, fats, fiber). We developed a predictive service and hosted it on AWS, while also developing an interactive mobile application to allow a user to track their information and provide immediate forecasts about their blood glucose levels. 

## Methods:
* Deep convolutional neural networks, classical machine learning models

## Frameworks and Platforms:
* Python, Java, Android, keras (when it first came out) + Theano, python, scikit-learn

## Outcomes:
* Deployed a highly accurate model (90% accuracy) for predicting blood glucose levels, along with an interactive mobile phone app, and a cloud based service architecture for providing predictions and storing user application information.






























