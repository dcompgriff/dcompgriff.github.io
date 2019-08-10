---
permalink: /portfolio/7
title: "Causality Pipeline"
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
* Most questions that businesses want to know about are actually causal in nature. How is business activity X causing metric Y? If I increased the amount of activity X, how much will this increase or decrease metric Y? These are causal questions because the question implies a cause and effect relationship between an activity and a metric. However, most data scientists incorrectly apply classical machine learning methods to answer these questions (Judea pearl, a totally awesome dude pioneering the field of causal analysis has many talks on this), using things like feature importance as a surrogate for causing predicted metrics. This is a classic example of the phrase everyone knows ‘correlation is not causation’, and yet PhD’s in statistics still easily get their analysis conclusions wrong. The problem is, how can a company understand the cause and effect aspects of their activities, to derive statistically valid strategies and decision making? 

## Solution: 
* I helped forward the idea of applying causality to the business, and operated as a technical consultant on the capabilities and methods for performing causal inference. These methods are often used on the medical world for things like adverse drug effect discovery, as well as in marketing to optimize targeting to customers where the action of sending an email is likely to cause someone to purchase a product.

## Methods:
* Difference-in-Differences, Causal Graphical Models, Counter Factual Analysis, Uplift modeling, etc…

## Frameworks and Platforms:
* Python, and a few pre-built packages like one for causal graphical models. Not many pre-built packages exist, so a lot of the code is custom.

## Outcomes:
* Causal inference applied to multiple business areas to determine how the business activities are causing revenue among other metrics.






























