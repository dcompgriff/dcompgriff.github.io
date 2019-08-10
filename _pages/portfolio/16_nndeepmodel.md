---
permalink: /portfolio/16
title: "‘Normal Noise Sensitivity’ Deep Model Benchmark"
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
* Deep neural networks for object recognition are a high performing method in the object detection and recognition problem domains. However, these systems have been shown to be brittle to slight variations in their input domains. Lots of research using things like generative adversarial networks has been developed for reducing the sensitivity of neural networks to attackers. However, many times there are variations in images that are not due to attackers, but instead due to things like image blue, image saturation and lighting effects, etc… We appoint these kinds of image variation as ‘natural noise’. Previously, there had been no work or exploration done to determine the sensitivity of various deep neural network components to these kinds of natural image variation.  

## Solution: 
* I developed a benchmark suite that injected a variety of natural noise into images, and then performed a systematic analysis of the effects of these noise on image object recognition tasks using the COCO-MS object detection data set across all object kinds, and variations in deep neural network architectures for this task.

## Methods:
* Deep residual and convolutional neural networks

## Frameworks and Platforms:
* Python, pytorch, scikit-learn, facebook detectron, etc…

## Outcomes:
* Develop a Benchmark for Evaluating Natural Variation In Images, and Their Effects on Deep Neural Network Object Detection Algorithms.
* Developed a report on the sensitivity to natural image variation for a set of 10+ state of the art object recognition models.
* Developed a set of 8+ guidelines for developing neural network based object detection methods robust to natural image variation.






























