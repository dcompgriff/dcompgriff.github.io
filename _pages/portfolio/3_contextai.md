---
permalink: /portfolio/3
title: "conTEXT AI Project"
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
* Companies need to understand the complex and varied aspects of all of the ways they interact with customers. One of these ways is through the variety of text base communication channels. These include channels like emails, text support cases, click2chat boxes, surveys, FAQ forums, social media posts, and many others. While these text sources often contain varied structures of text and kinds of discussions, the kinds of questions we have about them remain roughly the same. Companies want to answer questions such as: ‘what are the most common questions’, ‘what are the most common problems’, ‘what are the most common discussions occurring’, ‘how do we stack up against our competitors’. Companies also want to solve problems such as: ‘how do we reduce our operational support costs while improving response quality and speed?’.

## Solution: 
* Enter the context AI project. I started this project from scratch as one of my ‘blue sky’ initiatives at Cisco. I went on to fully develop and deploy the v1 system, and then continued afterwards leading a team of data scientists to continue work on the project. The system won multiple global technical data science awards at Cisco. It is currently being used on technical support cases for an opportunity of a cost reduction of $300 Million per year, while simultaneously automating responses and providing faster time to resolution of cases through recommended resolutions and recommended supporting content resources. It is also being applied in Cisco’s global virtual seller case deflection opportunity and reduce man hour costs. It is also being applied in Cisco’s social media channel and email channel opportunity to reduce man hour cost and reduce time to respond. The data science methods I used include a method of Semantic Clustering of text that I invented that can cluster text based on Topic, Problem, Semantics, Cisco Semantics, and outperforms traditional data representation methods (such as tf-idf, fuzzywuzzy, deep embeddings), as well as traditional clustering methods (such as k-means, hierarchical clustering, spectral clustering, etc…). The system also uses various forms of topic classification of text,  machine learning based “Information Extraction” methods to extract common Questions asked by customers and common Questions asked by support engineers in the support case dialogue, and uses machine learning based text models to map incoming text to a multitude of Cisco knowledge bases and cisco search engines for resolving support cases automatically.

## Methods:
* Custom invented semantic clustering method that far exceeded the capabilities of traditional methods, deep neural networks, deep unsupervised methods, advanced semi-supervised topic labeling

## Frameworks and Platforms:
* Google Cloud Platform for model development and deployment, python, spacy, scikit-learn, keras + tensorflow, genism, Guided LDA package, scrapy web scraper library

## Outcomes:
* An award winning system that can group together related technical support cases by the most commonly occurring problems, visualize this information, and allow support case managers to take strategic action to reduce the volume of cases and time to respond to a case.































