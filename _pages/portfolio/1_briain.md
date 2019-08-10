---
permalink: /portfolio/1
title: "Prescriptive Actions Engine (BRIAIN)"
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
* Let’s say that you have a predictive model that tells you a customer is 30% likely to purchase a problem. This is clearly a problem. The next question you have is ‘how do I improve the likelihood to purchase’. In other words, what actions can you take to solve a problem once it’s been identified? This is the question the Prescriptive Actions Engine named ‘BRIAIN’ solves. Classic machine learning is extremely useful, but only answers one half of the problem. Classic machine learning identifies that there is a problem but tells you nothing about how to solve the problem. Classic machine learning provides numbers to humans, and leaves determining corrective action to vague human intuition. BRIAIN, instead, provides human readable actions that should be taken to correct the problems identified. Cisco (and every company) has a need to know what actions they can perform to improve the metrics they care about. This could be what actions to take to improve the number of sales, actions to reduce the number of support cases, actions to improve a manufacturing process, actions to improve an investing portfolio, etc… 

## Solution: 
* I developed BRIAIN as a general AI learning agent service to prescribe actions in any environment. This service simply needs a client to define the ‘learning problem’ in the form of actions, states, rewards, and context, and they system will continually learn overtime which actions the client should take to solve the problems they care about. The system uses advanced statistical decision theory, utility theory, agent based AI, and advanced reinforcement learning (classical tabular, MAB’s, ML approximate, deep learning based, and invented extensions to the classical reinforcement learning framework). I developed the BRIAIN python package, the Django-rest based service, all unit/integration tests, the custom gym-cx simulated environment packages for algorithm evaluation, and deployed the entire service on the Google Cloud Platform using a combination of AppEngine, Pub/Sub, BigQuery, CloudSQL. The solution was deployed at Cisco to improve the following:
    1. Cisco Email Campaign Engagements
        * What content to send, when to send it, what order, when to involve a human, when to send upsells
        * All to optimize open rate, click through rate, traversal rate through the engagement
    2. Renewals
        * When to send renewal notifications, what content to send, what order to send it in
        * All to optimize likelihood to renew rates

## Methods:
* Advanced statistical decision theory, utility theory, agent based AI, and advanced reinforcement learning (classical tabular, MAB’s, ML approximate, deep learning based, and invented extensions to the classical reinforcement learning framework).

## Frameworks and Platforms:
* Google Cloud Platform for Development and Deployment of the Service
* Python, almost all code was custom written. All algorithms were developed and written from scratch.
* OpenAI Gym for a Base Structure to Implement Custom Simulations 

## Outcomes:
* A GCP deployed service for any stakeholder to use to prescribe actions in the client’s domain.
* BRIAIN python package for prescribing actions with a large suite of algorithms implemented.
* Gym-cx python package with custom simulated customer experience environments for email engagements.
* Deployment to prescribe actions for the renewals business, and to prescribe actions for all email engagements.
































