---
title: "Music Information Retrieval For Genre Classification"
summary: We implement k-nearest neighbors (k-NN), Gaussian Mixture Model (GMM), Multi-class SVM, Convolutional Neural Network (CNN), and Convolutional Recurrent Neural Network (CRNN) to classify the following four genres: Dark-Forest, Hi-Tech, Full-On, and Goa. We further extract 30 temporal features using a Long Short Term Memory (LSTM) based Auto-encoder from individual frames, and augment them with the frame-level audio features, which is a novel contribution in this work. 
authors: [Soumya Ranjan Sahoo, Anindita Ghosh]
categories: []
date: 2020-07-03T12:10:13+01:00
tags: ["Deep Learning", "Machine Learning", "Information Retrieval", "Audio Signal Processing"]

image:
  caption: ""
  focal_point: ""
  preview_only: false

url_code: "https://github.com/soumya-ranjan-sahoo/Music-Information-Retrieval"
url_pdf: "https://github.com/soumya-ranjan-sahoo/Music-Information-Retrieval/blob/main/Report-AudioSignalProcessing.pdf"
---

Abstact - Music Genre Classification is one of the many branches of Music Information Retrieval (MIR). However, music genre classification has been a challenging task in the field of MIR. Music genres are hard to systematically and consistently describe due to their inherently subjective nature. In this report, we revisit the problem of Music Genre Classification by using both the more traditional frame-level audio features and exploiting the temporal structure in audio spectrograms using deep convolutional and recurrent models. To this end, we implement k-nearest neighbors (k-NN), Gaussian Mixture Model (GMM), Multi-class SVM, Convolutional Neural Network (CNN), and Convolutional Recurrent Neural Network (CRNN) to classify the following four genres: Dark-Forest, Hi-Tech, Full-On, and Goa. We further extract 30 temporal features using a Long Short Term Memory (LSTM) based Auto-encoder from individual frames, and augment them with the frame-level audio features, which is a novel contribution in this work. With a very limited number of supervision signals, our best performing model achieves an F1 score of 0.84. Additionally, we discuss and compare the effectiveness of machinelearning versus deep-learning models for the problem of music genre classification. 

Index Terms - Genre Classification, Information Retrieval, k-nearest Neighbors, Gaussian Mixture Model, Multi-class SVM, Convolutional Neural Network, Convolutional Recurrent Neural Network, Long Short Term Memory, Auto-encoder


**This project was completed as part of the Digital Signal Processing course of Saarland University, ad instructed by Prof.[Dietrich Klakow](https://scholar.google.com/citations?hl=en&user=_HtGYmoAAAAJ).**
