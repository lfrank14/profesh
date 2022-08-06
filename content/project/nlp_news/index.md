---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Predicting real v. fake news using natural language processing
summary: ""
authors: []
tags:
  - Data science
categories: []
date: 2022-08-05T20:56:54-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

For this project, I wanted to see if I could use machine learning to reliably predict whether a news article was real of fake. I used a collection of real and fake news articles, which can be found [here](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset?datasetId=572515). I compared two models- Naive bayes with word bags and Artificial Neural Networks (ANN) with word embeddings. The ANN outperformed Naive bayes, with an accuracy of 94% on the final test set. For a bit of fun, I then evaluated how well these models could generalize to a random sample of POTUS tweets from 2019-2020 (found [here](https://www.kaggle.com/datasets/austinreese/trump-tweets)). 

The code to this project and an outline of my findings can be found [here](https://colab.research.google.com/drive/1Zy4xXXFg2bMEIlUUhLOXJ0sdESZNqTYj?usp=sharing). 