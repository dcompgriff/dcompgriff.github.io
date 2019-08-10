---
permalink: /portfolio/24
title: "Hillary Clinton Email Sentiment Analysis Project"
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
* In 2015, Hillary Clinton was embroiled in an email scandal that possibly significantly affected her bid for a presidential election. In 2015 the US state department released a set of 7000 redacted emails from her private email accounts through the freedom of information act. From a data science perspective, there is an opportunity to try to understand the discussions that were being had in these emails and their context. How can we do this in an automated fashion using machine learning methods?

## Solution: 
* I along with two other people developed an automated pipeline for processing emails, cleansing them, featurizing them, and supervised machine learning methods to understand the topics of these emails, as well as the general sentiment towards the topics in these emails.

## Methods:
* Classical supervised machine learning models, along with classical dimensionality reduction methods, and NLP methods.

## Frameworks and Platforms:
* Python, scikit-learn, NLKT, n-grams/tf-idf, etc… (Before deep embeddings were popular)

## Outcomes:
* Developed an automated classification system for determining sentiment from emails.
* Applied the system to both the enron data set and the Hillary Clinton data set, and generated reports on the topics discussed in both email sets, and the general sentiment towards those topics.































