---
permalink: /portfolio/9
title: "Colorimetric Assay Quantification"
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
* A colorimetric assay is a substance that has been chemically designed to change color in the presence of a detected chemical. An easy example of a colorimetric assay is a Ph strip. A Ph strip has been chemically designed to change color when dipped into a solution to indicate the Ph of the solution. These assays are hugely beneficial in that they are highly portable, and typically require no added technology or lab to be run. Examples of how this is useful are for AIDS medical tests performed in remote African villages, and for drug substance testing at country border crossings. The common issue with these assays is that the color evaluation is typically performed by a human holding the assay up against some paper color chart. This can lead to high variance measurements. How can we quantify these assays in a general way, given that we can’t add custom technology to perform the visual measurements, and given the colors of assays are unique to their design, as well as the predicted response functions (aka Ph assays are from 1 to 14, but glucose measures are from 0 to 1)? 

## Solution: 
* I developed a novel mobile phone application that allowed a user to take a calibration picture to build a predictive model that would map any user defined color/value pairs to a predictive surface. This surface could then be used to perform numeric predictions on new data. The app allowed a user to create and store multiple sets of predictive functions for a multitude of assays. By utilizing the ubiquity of mobile phones and their attached cameras, we can improve the prediction of assay values without adding extra custom hardware.

## Methods:
* The predictive method used a novel color space transformation to reduce image saturation issues, and allowed on-phone model building to resolve the issues of phone-to-phone camera response variations. The predictive method used various forms of non-grid based, multi-variate interpolation methods for building predictive surfaces.

## Frameworks and Platforms:
* Java, Android platform, java math libraries, MySQL & SQLite databases, OpenCV for automatically finding expected assay shapes to help automate the calibration process.

## Outcomes:
* Multiple published papers on novel assays, and the novel methods for general mobile quantification. 
* I was the sole developer of the entire mobile app, prediction method, and everything not related to the assay creation itself.
* Demonstrated capability for cocaine detection, Ph prediction, glucose prediction.






























