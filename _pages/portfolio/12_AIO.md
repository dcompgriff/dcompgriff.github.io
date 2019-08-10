---
permalink: /portfolio/12
title: "AI Orchestration Engine"
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
* Some systems consist of an input and an output, which have multiple paths from input to output with varying costs and benefits. An example is some physical dynamical model simulations. Sometimes, it can be extremely time consuming to retrieve a single data point from a highly complicated model. Many times, approximations to such a model are made in a tradeoff between accuracy and speed. Suppose you have a set of these models, each with a varied degree of accuracy and expected speed. A challenging question to answer is which system should be used to achieve a set level of accuracy, while returning results the quickest? The problem becomes even more challenging when the models or services must be called in a chain. Another example of this domain is customer onboarding to a financial service. There exist multiple services for the customer to have their credit score checked, their bank accounts to be verified, etc… What is the best chain of services to call that minimizes cost while still meeting a certain level of accuracy? 

## Solution: 
* Develop a system that accepts a definition of the possible paths of calling models and services, which learns to model the system’s accuracy and cost over time, and how those errors propagate through time, and can tradeoff between new models being added and old models being retired.
* Allow a user to choose a satisficing metric, and an optimizing metric, where the system will find the optimal predicted path of service calls to meet the base threshold and optimize for the optimizing metric. 

## Methods:
* Reinforcement learning, graph algorithms, statistical prediction methods.

## Frameworks and Platforms:
* Java, industry available conductor systems such as Netflix conductor, other technologies…

## Outcomes:
* Developed a basic intelligent system that attempted to use AI algorithms to optimize the service call chain paths for an optimal service chain.






























