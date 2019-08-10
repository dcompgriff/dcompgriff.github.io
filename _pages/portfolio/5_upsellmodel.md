---
permalink: /portfolio/5
title: "Product Upsell Model"
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
* Cisco needs to know what customers are interested in specific products. Traditionally, recommendation system methods are used to perform this kind of upselling motion. However, it is sometimes desired to have more accurate results, especially for new products where the cold start problem causes recommendation systems to give spurious results.

## Solution: 
* Develop a customer predictive model that uses views of customers activity before and after purchasing a product or service to predict new customers that will be interested in purchasing the products.

## Methods:
* Classical machine learning models along with Spark/Hive tabular data.

## Frameworks and Platforms:
* Python, spark ETL, scikit-learn, etc…

## Outcomes:
* A model that could predict the interest of customers in a product, as well as a report of all customers that haven’t purchased the product ranked by their predicted interest in purchasing the product, along with insights into the reasons for their interest (which is important for sellers to tailor their selling motions)































