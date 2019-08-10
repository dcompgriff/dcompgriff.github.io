---
permalink: /portfolio/14
title: "Time series feature database for ML applications"
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
* How to effectively store time series is a popular and challenging problem today. More and more data is being produced every day, and most of this data has some sort of temporal component to it. Furthermore, the advent of the idea of IoT (Internet of Things) means more and more sensor data is going to be produces. These time series streams can contain huge amounts of information, and don’t have much insights to any individual data point. In fact most insights we care about exist as complex relationships between trends in time series and aggregations of data points. Yet, almost all time series databases focus on being able to compress the data that takes up less space with an emphasis on accuracy for recently generated data points. 

## Solution: 
* I proposed and developed a prototype database that stored time series not as individual data points or approximate representations (like using an fft or exponentially degraded signal), but instead stored windowed feature representations that are more conducive to machine learning based analysis methods. Time series classifiers typically re-use features that can be computationally complex to produce. This system uses ‘feature functions’ to condense time series into re-useable feature representations for existing data science models to use. This solves the issue of having to store large amounts of data, while still preserving the ability to derive the insights we care about, which come from complex aggregations and feature representations of the time series anyways.

## Methods:
* Time series based feature representations of data sets gathered from multiple surveys on the topic (shaplet, wavelet, sax, local regression methods, windowed generative model parameters, LSTM windowed embeddings built on forecasting data)

## Frameworks and Platforms:
* Python spark

## Outcomes:
* Developed a novel POC of the system for automatically storing time series data as feature representations for machine learning driven applications.






























