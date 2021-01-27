---
title: "Data Augmentation using Feature Generation for Volumetric Medical Images"
summary: In this work, we propose using U-net and ACGAN as a learning framework for feature generation of medical images followed by classification to validate the quality of
generated features.
authors: [Soumya Ranjan Sahoo, Khushboo Mehra]
categories: []
date: 2020-07-03T12:10:13+01:00
tags: ["Deep Learning", "Generative Models", "Vision"]

image:
  caption: ""
  focal_point: ""
  preview_only: false

url_code: "https://github.com/soumya-ranjan-sahoo/GANs---PyTorch/tree/master"
url_pdf: "https://github.com/soumya-ranjan-sahoo/GANs---PyTorch/blob/master/Report-ComputerVision.pdf"
url_slides: ""
url_video: ""

---
Abstact - Medical image classification is one of the most critical problems in the image recognition area. One of the major challenges in this field is the scarcity of labelled training data. Additionally, there is often class imbalance in datasets as some cases are very rare to happen. As a result, accuracy in classification task is normally low. Deep Learning models, in particular, show promising results on image segmentation and classification problems, but they require very large datasets for training. Therefore, there is a need to generate more of synthetic samples from the same distribution. Previous work has shown that feature generation is more efficient and leads to better performance than corresponding image generation [12]. We apply this idea in the Medical Imaging domain. We use transfer learning to train a segmentation model for the small dataset for which goldstandard class annotations are available. We extracted the learnt features and use them to generate synthetic features conditioned on class labels, using Auxiliary Classifier - ACGAN). We test the quality of the generated features in a downstream classification task for brain tumors according to their severity level. Experimental results show a promising result regarding the validity of these generated features and their overall contribution to balancing the data and improving the classification class-wise accuracy.


**This project was completed as part of the High Level Computer Vision course offered by MPI-Inf. Course Instructor:**
