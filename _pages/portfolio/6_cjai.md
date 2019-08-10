---
permalink: /portfolio/6
title: "Customer Journey AI"
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
* Cisco needs to understand the customer lifecycle in a multitude of ways. Cisco needs to understand the distinct kinds of behavior a customer exhibits after product purchase, when that behavior changes, and other information like if a customer is stuck, if there are challenges in the implementation of technology, and what Cisco can do to improve the customer’s journey. Traditionally, companies developing their customer experience use totally human driven methods, with no data and no visibility into the ways they can improve a customer’s journey.

## Solution: 
* Enter the Customer Journey AI project. This is a project where I started the data science initiative from scratch within my organization that focused on all aspects of how Cisco engages with their customers. The goal was to develop an automated suite of machine learning driven insights to predict metrics around the journey such as expected time to complete a set of engagements, the predicted ‘health’ of a customer, etc… The BRIAN system was also incorporated into this process to learn to prescribe actions to improve the metrics that the customer journey AI suite would identify.

## Methods:
* I developed an automated machine learning pipeline that will accept a wide variety of static and behavioral customer features and will automatically train models and generate reports about model training. I then deployed this pipeline alongside an automated prediction pipeline implemented using spark as the ETL pipeline, which automatically generated predicted metrics.

## Frameworks and Platforms:
* Python, spark ETL, spark ML, scikit-learn, keras+tensorflow, pymc3, auto-ml, etc…

## Outcomes:
* A continually running auto-ml pipeline that would automatically produce metric predictions about a customer’s engagements.































