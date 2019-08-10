---
permalink: /portfolio/2
title: "Social AI Project"
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
* Social media communication channels are becoming increasingly important in the digital age for companies to communicate with their customers. Businesses need to understand the discussions that are occurring on social media platforms, and to quickly identify engageable conversations and discussions. However, trillions of pieces of text content are generated on social media platforms every day. How can a company like Cisco quickly and effectively identify the engageable posts, gather related resources for engaging, and generate a response? The problem is even more challenging because some discussions the company cares about use only vague technology terms (like ‘firewalls’) or different names for the same entity (NGFW vs Next Generation Firewall vs NextGen FW etc…). There’s also different kinds of posts to engage with (Sales related, ask for support, general discussion, questions, product evaluations, etc…). How can we identify these opportunities quickly, in a cost effective way, given huge volumes of data?

## Solution: 
* I initially developed, and then lead a team of data scientists to continue developing and enhancing a 3 stage automated Machine Learning (ML) system that 1) provides post context, 2) routes and gathers related information, 3) generates responses automatically. I developed and deployed the system on the Google Cloud Platform (GCP) using auto-scaling services for robust prediction serving including AppEngine, Pub/Sub, Datalab, Dataproc, ML Engine. I also wrote a service API to automatically integrate into the business process and main tool used for social care. The methods used included cutting edge deep neural network text processing based methods for processing data (Custom & Cutting edge deep embedding models, custom deep RNN/Attention networks, etc…) as well as various forms of transfer learning (beyond simple model parameter sharing), and combinations of supervised and unsupervised machine learning for providing context, extracting useful information, and creating automated responses. After deployment, the system had performed ~70 Million predictions, with ~1 Million per week, and resulted in an ~8,200% raw efficiency improvement over the previous business process.

## Methods:
* Classical machine learning models like SVMs, logistic regression, adaptive basis functions, bayes nets built on top of traditional feature representation methods like n-grams, skip-grams, and PCA reduced tf-idf features.
* Advanced classification deep neural network models with both custom and pre-trained glove embeddings, bagged with classical methods.
* Advanced sequence generation methods using RNNs for generative and selective response construction.

## Frameworks and Platforms:
* Google Cloud Platform for Development and Deployment of the Models and Service, Python, keras + tensorflow, spacy, scikit-learn, NLTK, numpy, scipy, Auto-sklearn

## Outcomes:
* ~70 Million predictions, with ~1 Million per week, and resulted in an ~8,200% raw efficiency improvement over the previous business process.
* A continually running and consumable service that provided multiple kinds of context (intent of post, sales/support/feedback, sentiment, product, etc…)
* Multiple supervised and unsupervised model artifacts.































