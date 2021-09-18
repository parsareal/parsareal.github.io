---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Currently graduate student of Computer Science program at York University, *Toronto, ON*.
Interested in Machine Learning, Deep Learning, Information Retrieval, Natural Language Processing, Information Visualization, Data Mining and Social Nework Analysis. You can find some related projects in [here](https://gitlab.com/users/parsareal/projects) and my Github. Here, I briefly explain some of my notable research experiences during BSc.

***Anomaly Detection in Networks***

I have done a paper about anomaly detection in attributed graphs under the supervision of [Professor AmirHaeri](https://people.utwente.nl/m.amirhaeri). The main idea is training variational autoencoder (VAE) with the concatenation of features extracted by node2vec algorithm and attributes of each node in the network. After the training procedure, we sorted the nodes based on their reconstruction loss and the ranking of each node indicated how much it could be a anomlay. The result of this project was a [paper](https://dl.acm.org/doi/fullHtml/10.1145/3459955.3460597) that was accepted by International Conference on Information Science and Systems (ICISS 2021) and published in the International Conference Proceedings Series by ACM. [Code](https://github.com/vague-miner/Anomaly-Detection-in-Attributed-Graphs)


***Text Chunking***

Moreover, I have done two papers (abstracts [here](https://drive.google.com/file/d/1E2GzNGsa2DofIeziKv2nscYDas8_luUI/view?usp=sharing) and [here](https://drive.google.com/file/d/1gg2NuAfrhuYw2Gnc_yisFEDYEL-PA5vD/view?usp=sharing)) about phrase chunking for Persian and English languages under the supervision of [Professor Momtazi](https://aut.ac.ir/cv/2345/Saeede%20Momtazi). The persian chunker entailed two major phases; the first phase was preparing a labeled dataset and finding phrase patterns in data with POS tags. The second phase was feeding the dataset into transformer-based pre-trained models, BERT and XLM-RoBERTa followed by CRF and BiLSTM_CRF in order to to learn how to predict noun phrases in unlabeled text. The English paper was a comparitive study on the performance of various contextualized models, Funnel Transformer, BERT, BART, GPT2, XLM, XLM-RoBERTa, in sequence chunking task on CoNLL2000 dataset.


***Adversarial Learning in Text***

Furthermore, I am working on different defense approaches against adversarial attacks on text data, including character-level and word-level(typos and synonyms) attacks under the supervision of [Professor Mazlaghani](https://aut.ac.ir/cv/2296/Maryam-Amir-Mazlaghani?slc_lang=en&&cv=2296&mod=scv) by using machine learning algorithms. These approaches include methods like designing a defensive model to prevent adversarial examples from entering the classification module or making the classification algorithms more robust against these examples.

***LFP Signal Classification***

In my 2019's summer internship, I employed different clustering algorithms (KMeans, DBSCAN, Hierarchical) to cluster LFP signals captured from monkeys in Laboratory under the supervision of Professor Lashgari at [Brain Engineering Research Center](http://braineng.scs.ipm.ac.ir/) of the Institute for Research in Fundamental Sciences (IPM). [Code](https://github.com/parsareal/LFP_Clustering)

In addition, I was in SOP Company since June 2017 as Node.js developer and responsible for implementing back-end server.
