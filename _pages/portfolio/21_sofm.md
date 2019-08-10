---
permalink: /portfolio/21
title: "Self Organizing Feature Maps for Explainable Clustering"
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
* Many times we want to understand how to model the complex relationships between data points. Typically, the more features and data we have, the more complex relationships we can model. However, one of the issues is that high dimensional data prevents us from directly visualizing the relationships. We may be able to tell that a group of 10 dimensional data points belong to the same cluster, but we can’t determine how one cluster may be related to others. There are many methods for trying to visualize high dimensional data sets including violin plots, parallel coordinate plots, t-sne embeddings, locally linear manifold methods, and many others… One special method includes ‘self organizing feature maps’. This method takes high dimensional data, along with a set of randomly scaled cluster vectors laid out in a grid, and then performs an iterative clustering method. The result is a 2D grid representing the cluster vectors, along with a label per cluster vector. This visualization provides a representation of how complex, high dimensional data clusters are related to each other.

## Solution: 
* I developed a general purpose python library for automatically creating self-organizing feature maps that can be used in a variety of other projects.

## Methods:
* Self-organizing feature maps

## Frameworks and Platforms:
* Python

## Outcomes:
* Developed a general self-organizing feature map python library.
* Demonstrated the effectiveness of this library by applying it to a dataset of animal features and providing a 2D projected representation of the animals clustered on the surface.































