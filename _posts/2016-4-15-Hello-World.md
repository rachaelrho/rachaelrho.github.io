---
layout: post
title: Categorical clustering (k-modes)
---

For my first post on github, I'd like to give a preview of an exploration I'm currently working on. 

K-means clustering is an unsupervised learning technique widely used for clustering/segmentation analysis. However, since the technique groups clusters based on numeric distance, k-means can only analyze numeric variables. K-modes, a recently released python package seeks to address this limitation and enable both numeric and categorical variables in a 'k-means like' algorithm. 

You can learn more about the k-modes package [here](https://pypi.python.org/pypi/kmodes/#cao09). It includes both [Huang's method](http://www.cse.ust.hk/~qyang/537/Papers/huang98extensions.pdf) and the more recent [Cao's method](http://cicip.sxu.edu.cn/achievement/paper/A_new_initialization_method_for_categorical_data_clustering_20121102010105.pdf). There are many clustering possibilities with the expansion into categorical variables, which I will explore with actors in the film industry.
