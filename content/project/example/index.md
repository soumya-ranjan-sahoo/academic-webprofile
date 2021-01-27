---
title: "Score Me if You Can"
summary: Study on Robustness of Automated Essay Scoring Systems to Out-of-domain and Adversarial Inputs summary
authors: [Soumya Ranjan Sahoo, Vladislav Skripniuk, Vinit Hegiste]
categories: []
date: 2020-07-03T12:10:13+01:00
tags: ["Deep Learning", "Robustness", "Vision"]


image:
  caption: ""
  focal_point: ""
  preview_only: false






url_code: "https://github.com/soumya-ranjan-sahoo/UdSProjects/tree/master/MLCySec/project3"
url_pdf: "https://github.com/soumya-ranjan-sahoo/UdSProjects/blob/master/MLCySec/project3/Report-AdversarialML.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Abstact - Successes in natural language processing gave rise to numerous automated essay scoring systems, some of which are now used in high-stakes tests. In this project we take one of the recent models [20] into consideration and through several sanity checks reveal some of its intriguing properties.

<figure>
   <img src="featured_2.png" width="75%"></img> 
    <figcaption><b>Original label (Y-axis) to Predicted label (X-axis)</b></figcaption>
</figure>

Next, we explore a defence mechanism known as adversarial training, where we train the model with batches of such attacked images.
We train the model with samples of FGSM attacked images. 
We show that this drastically improves the robustness of the model for both attacks, for FGSM it goes to 93.4% whereas it improves to 77.6% for MIM.

<figure>
   <img src="featured_3.png" width="100%"></img> 
    <figcaption><b>Prediction probabilities for original model and defended model to attacked images</b></figcaption>
</figure>

**This project was completed as part of the Machine Learning in Cybersecurity course of Saarland University.**
