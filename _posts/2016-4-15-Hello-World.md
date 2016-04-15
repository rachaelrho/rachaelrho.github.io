---
layout: post
title: Categorical clustering (k-modes)
---

For my first github post, I want to give a preview of an exploration I've been working on. 

K-means clustering is a widely used unsupervised learning technique for cluster/segmentation analysis. However, since k-means uses numeric distance to determine cluster groups, the algorithim is only applicable to numeric variables. K-modes, a python package, was recently released to address this constraint and enable clustering of both numeric and categorical variables.

You can read more about the package [here](https://pypi.python.org/pypi/kmodes/), in which it can apply [Z. Huang's method](http://cicip.sxu.edu.cn/achievement/paper/A_new_initialization_method_for_categorical_data_clustering_20121102010105.pdf) and the more recently published [F. Cao's method](http://www.cse.ust.hk/~qyang/537/Papers/huang98extensions.pdf). There are many unsupervised learning possibilies with the expansion into categorical variables -- stay tuned for my next post on applying k-modes to analyze actor/actress similarity in the film industry.
