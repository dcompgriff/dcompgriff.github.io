---
permalink: /portfolio/4
title: "Sales Opportunity Scoring Model"
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
* The Cisco seller process works with digital seller information reports called ‘opportunities’. When a seller has contacted a customer and determined they are potentially interested in purchasing products or services, a seller creates an ‘opportunity’. An opportunity has a 5 stage lifecycle. A question sellers typically have is, ‘which opportunities are the most likely to go through the entire set of 5 stages to booked’. Given this information, a seller would be able to prioritize their focus on the opportunities that need their focus, allowing them to book more opportunities.

## Solution: 
* I developed an end-to-end, automated spark pipeline for gathering multiple pieces of data from salesforce, and other Cisco business information, and developed a highly accurate predictive machine learning model to predict the likelihood of a customer seller leaving. This model was integrated into the seller process, and changed the way Cisco sellers approached opportunities to improve the data.

## Methods:
* Using large historical salesforce data, and adaptive basis function classification models, along with probability calibration methods.

## Frameworks and Platforms:
* Company spark job scheduler system, python, spark ETL, spark ml, Hadoop+hive, scikit-learn, jupyter notebooks

## Outcomes:
* Development and deployment pipelines, with an automated ETL & prediction pipeline built on top of spark.































