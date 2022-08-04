---
date: 2021-06-18T00:00:00Z
external_link: ""
image:
  caption: Photo by me
  focal_point: Smart
tags: 
  - Research
title: Evaluating methods for background connectivity
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Functional connectivity is used in MRI to understand the functional relevance of coherent brain activity between brain regions. Importantly, functional connections contains idiosyncratic features that can be leveraged to identify individuals and predict individual behavior. The most common approach to measuring functional connectivity is during a period rest, referred to as resting-state functional connectivity. Background connectivity, or those connections that occur in the background of task-evoked activity, can be similarly leveraged to identify individuals and their behavior. Successfully removing task-evoked activity is crucial for isolating background connections, and there is little consensus on the best approach. There are two methods for removing trial-evoked activity - 1) applying a low-pass filter to remove frequencies at or above the task frequency, or 2) using the residuals from a finite impulse response (FIR) model that accounts for trial-by-trial activations. This project evaluates the efficacy of each approach, as well as how well they compare to functional connections obtained at rest.

Check out the project code on [Github](https://github.com/lfrank14/co_methods)!