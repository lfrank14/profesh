---
date: 2022-06-22T00:00:00Z
external_link: ""
image:
  caption: Photo by me
  focal_point: Smart
tags:
- Past
- Machine Learning
title: Class Imbalance in Multivoxel Pattern Analysis
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

In functional MRI multivoxel pattern analysis (MVPA), we are sometimes faced with classification problems where the training set contains unequal class sizes. For example, if we are trying to predict activity for remembered v. forgotten pictures, we may find that there are more remembered than forgotten trials. Unequal observations between the classes may bias the classifier to predict the more frequently observed class. In other words, if trained on more “remembered” trials, the classifier may be more likely to predict trials in the untrained set as “remembered.” While downsampling is a common solution to unequal class sizes, it’s not always an ideal approach when working with fMRI data. The available training data in MVPA is often small and downsampling can exacerbate this problem. This dashboard is intended to showcase the influence of unbalanced or unequal class sizes on MVPA performance and show how downsampling is not always the solution. In this dashboard highlight two classification problems, one with manually produced imbalance and another with inherent imbalance.

Check out my completed dashboard {{< staticref "uploads/mvpa_dash.html" "newtab" >}}here{{< /staticref >}}. 