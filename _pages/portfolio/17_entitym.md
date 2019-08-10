---
permalink: /portfolio/17
title: "Entity Matching"
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
* Entity matching is an extremely prevalent problem at large companies. Entity matching is the problem of determining if two records from different data sources refer to the same real world entity. For example, many times different databases at the same company use different id’s to identify customers. Sometimes a customer is only put in with partial information, and sometimes their information is duplicated. Many times a company wants to match together customers in two different databases and identify them as being the same customer. Matching data like this, as well as de-duplication of databases that have multiple rows that refer to the same entity happens extremely often. In this problem, we have two different movie data base sets, and we have to determine what movies exist in both databases, to create a single database with all, unique movies.    

## Solution: 
* Develop a supervised entity matching system that uses the approach of multiple layers of blocking, string expanded and categorical features, and a bagged set of classifiers to perform supervised entity matching.

## Methods:
* Supervised learning methods, a variety of string similarity methods as features such as levenstein distince, jaro-winkler, n-gram overlap, etc…

## Frameworks and Platforms:
* Python, scikit-learn, Magellan, etc…

## Outcomes:
* Developed an entity matching system that could match movies together with a 99.99% accuracy. 






























