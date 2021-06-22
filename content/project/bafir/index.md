---
date: 2021-06-18T00:00:00Z
external_link: ""
image:
  caption: Photo by me
  focal_point: Smart
tags:
- Current
title: Comparing methods for low-frequency connectivity
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Low-frequency connectivity allows researchers to measure interactions that are associated with different brain states while participants are performing a task. One challenge of this approach is that trial-related activations must be completely removed from the BOLD signals to ensure correlations are not driven by trial-based events, like stimulus presentation. There are two commonly used methods for removing trial-related activations in the BOLD signal- 1) applying a low-pass filter to the BOLD timeseries to remove frequencies at or above the task frequency (background connectivity), or 2) using the residuals from a finite impulse response (FIR) model that accounts for trial-by-trial activations. This project compares the efficacy of each approach, as well as how well they perform under different trial-timing conditions. 