---
title: "Enhancing clinical information retrieval on health forums using neural ranking models"
summary: Since health forums become a rich source of information to people with medical conditions discussing treatments, doctor's opinions, side-effects to complex-drugs, while also sharing personal background medical information in a community question-answering framework, we develop a neural search engine on top of such health forums by exploring the state-of-the-art neural ranking models. We first write a set of optimal heuristic functions that maximizes the relevancy scores for a labelled dataset by training a snorkel classifier that classifies a given query-document pair as relevant or irrelevant. Later, these functions are extended to classify the unlabelled set of query-document pairs, followed by re-ranking using neural re-rankers.  
authors: [Soumya Ranjan Sahoo]
date: 2020-07-03T12:10:13+01:00
tags: ["Deep Learning", "Machine Learning", "Information Retrieval", "NLP", "Information extraction"]

image:
  caption: ""
  focal_point: ""
  preview_only: false

url_code: "https://github.com/soumya-ranjan-sahoo/Music-Information-Retrieval"
url_pdf: "https://docs.google.com/document/d/1NjFs9YLUwO0PghcBV8w1-UTfimGiRg0YDQkAnTph7uc/edit"
---

Abstact - Online health forums offer a wealth of information for people with medical conditions. Users share experiences with treatments, talk about side-effects they experience with complex drug regimens and also give detailed background information about their conditions, such as demographic, lifestyle, or familial information. Other users including doctors reply in a community question- answering (CQA) manner. Prominent examples of online health forums are ehealthforum.com and healthboards.com. To the best of our knowledge there isn’t any substantial prior work on exploring neural ranking models for searching health forums and thus there is a big opportunity of having a meaningful impact by tackling this problem. Beyond the question and answering community, all health forums support searching functionality. However, in practice the retrieved results are not satisfactory because they tend to be very broad and unrelated to the user's specific medical needs. To the best of our knowledge there isn’t any substantial prior work on exploring neural ranking models for searching forums, health or non-health, and thus there is a big opportunity of having a meaningful impact by tackling this problem.

Index Terms - Health forums, community question-answering, neural ranking models

**This project was completed as part of Research Immersion Lab at Max Planck Institute for Informatics, supervised by Dr.[Erisa Terolli](https://faculty.stevens.edu/eterolli).**
