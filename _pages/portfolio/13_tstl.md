---
permalink: /portfolio/13
title: "Time Series Transfer Learning"
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
* There exist many methods for performing transfer learning. Most of these methods enforce a statistical assumption about the link between the independent variables X-source and the dependent variables Y-source to the X-target and dependent Y-target domain. This assumption typically takes the form of an assumed equivalence of the class conditional distributions or some other form of linking assumption. This linking assumption is typically then used to re-weight the data from a source domain to match the target domain, which in turn improves the signal in the target domain. A major question is, how can we perform this transfer without assuming an equivalent distribution over the data sets?

## Solution: 
* For time series, we can create a generative Bayesian net based forecasting model over a data set, which tells us how likely a new time series was to be generated from the same distribution. Using this, we can link two time series in a way that can’t be done for non-temporal data sets, but eliminates the assumption of equivalent class conditional distributions. 

## Methods:
* Bayes nets, generative frequentists statistical models, transfer learning theory

## Frameworks and Platforms:
* Python, and a few python optimization packages, but most code was custom written.

## Outcomes:
* Wrote a paper (unpublished) outlining the technical approach and the model applied to an activity recognition data set for performing transfer from one set of activity recognition tasks to another for classification.






























