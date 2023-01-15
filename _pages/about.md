---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Currently graduate student of MS Computer Science program at York University, *Toronto, ON*.
Interested in Machine Learning, Deep Learning, Information Retrieval, Natural Language Processing, Information Visualization and Data Mining. You can find some related projects in [here](https://gitlab.com/users/parsareal/projects) and my Github. Here, I briefly explain some of my notable work and research experiences during my education.

***Data Science Internship at Manulife***

Being part of the **NLP team** in department of analytics to implement a **search engine** system for business documents.
Using **SQL Full-text index** feature of SQL on **Azure Machine Learning platform** to index documents and retrieve
ranked results based on input queries. Learning how to use different Azure features and services like **pipelines,
endpoints, data drift detector, datastores and etc** in order to create and manage a machine learning project
lifecycle.

***Natural Language Interactions with Visualization***

I'm currently working on **natural language** interactions with **visualization** under supervision of [Professor Hoque](https://www.yorku.ca/enamulh/#). Our work focuses specifically **chart data** and systems employing NLP
and computer vision techniques to handle charts and natural language both as input (question) and output (chart
summary). We have published a [survey paper](https://arxiv.org/abs/2205.03966) about **chart question answering** domain so far. Working on an end-toend solution by **chart pretraining** for **chart comprehension and reasoning**. Our ongoing project is about adapting **BLIP** vision-language
architecture in order to contain chart image encoder, text encoder, and chart-ground text decoder modules in a single
architecture. In a parallel project, we are utilizing the **YOLOS** object detection model on chart data in order to detect the bounding boxes,
relations of chart elements, and eventually **reconstructing the underlying data table of chart**, which is highly effective in chart downstream tasks like chart question answering, open chart question answering and chart summarization.

***Anomaly Detection in Networks***

I have done a paper about anomaly detection in **attributed graphs** under the supervision of [Professor AmirHaeri](https://people.utwente.nl/m.amirhaeri). The main idea is training **variational autoencoder (VAE)** with the concatenation of features extracted by **node2vec algorithm** and attributes of each node in the network. After the training procedure, we sorted the nodes based on their **reconstruction loss** and the ranking of each node indicated how much it could be a anomlay. The result of this project was a [paper](https://dl.acm.org/doi/fullHtml/10.1145/3459955.3460597) that was accepted by International Conference on Information Science and Systems (ICISS 2021) and published in the International Conference Proceedings Series by ACM. You can find the code of this project [here](https://github.com/vague-miner/Anomaly-Detection-in-Attributed-Graphs).


***Text Chunking***

I have done two projects ([paper](https://jad.shahroodut.ac.ir/article_2455_827ea2331be0e909e698d04fc145df6e.pdf)) about **phrase chunking** for Persian and English languages under the supervision of [Professor Momtazi](https://aut.ac.ir/cv/2345/Saeede%20Momtazi). The persian chunker entailed two major phases; the first phase was preparing a labeled dataset and finding phrase patterns in data with POS tags. The second phase was feeding the dataset into **transformer-based** pre-trained models, BERT and XLM-RoBERTa followed by **CRF** and BiLSTM_CRF in order to to learn how to predict noun phrases in unlabeled text. The English paper was a comparitive study on the performance of various contextualized models, Funnel Transformer, BERT, BART, GPT2, XLM, XLM-RoBERTa, in sequence chunking task on CoNLL2000 dataset.


***Adversarial Learning in Text***

Furthermore, in my BS thesis project, I worked on different defense approaches against **adversarial attacks on text data**, including character-level and word-level(typos and synonyms) attacks under the supervision of [Professor Mazlaghani](https://aut.ac.ir/cv/2296/Maryam-Amir-Mazlaghani?slc_lang=en&&cv=2296&mod=scv) by using machine learning algorithms. These approaches include methods like designing a defensive model to prevent adversarial examples from entering the classification module or making the classification algorithms more robust against these examples.

***Search Engine Project***

I was also involved in large-scale team project in *Information Retrieval* course during my BSc. We implemented an **online news search engine** from scratch. We pre-processed **(tokenization, stemming, stopwords)**, indexing and vectorizing documents with **tf-idf** measure.
Scoring the documents based on input query was calculated by **cosine similarity** metric between the query vector and all documents vectors.
At the final stage of the project, we imporved the retrieval process by document **classification** and **clustering**. You can find the code of this project [here](https://gitlab.com/parsareal/news_searchengine).

***LFP Signal Classification***

In my 2019's summer internship, I employed different clustering algorithms **(KMeans, DBSCAN, Hierarchical)** to cluster LFP signals captured from monkeys in Laboratory under the supervision of Professor Lashgari at [Brain Engineering Research Center](http://braineng.scs.ipm.ac.ir/) of the Institute for Research in Fundamental Sciences (IPM). [Code](https://github.com/parsareal/LFP_Clustering)
