---
title: "A Min-Max Optimization Framework for Multi-task Deep Neural Network Compression"
collection: publications
category: manuscripts
permalink: /publication/Minmax_ISCAS_24
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-05-22
venue: 'Conference 1'
paperurl: '[http://academicpages.github.io/files/paper1.pdf](https://ieeexplore.ieee.org/abstract/document/10557958)'
bibtexurl: '[http://academicpages.github.io/files/bibtex1.bib](https://scholar.googleusercontent.com/scholar.bib?q=info:EGkHfZxwl5MJ:scholar.google.com/&output=citation&scisdr=CgLp_XGoEK-M0YhYQQ8:AAZF9b8AAAAAaDteWQ-wO2m3dQQcH2lPbPfiDI8&scisig=AAZF9b8AAAAAaDteWVPGxeDLsrh1jP_KN5_xdqU&scisf=4&ct=citation&cd=-1&hl=zh-CN)'
citation: 'Jiacheng Guo, Huiming Sun, et al. (2024). &quot;A Min-Max Optimization Framework for Multi-task Deep Neural Network Compression.&quot; <i>2024 IEEE International Symposium on Circuits and Systems (ISCAS), 2024</i>. 1(1).'
---
Abstract: Multi-task learning is a subfield of machine learning in which the data is trained with a shared model to solve different tasks simultaneously. Instead of training multiple models corresponding to different tasks, we only need to train a single model with shared parameters by using multi-task learning. Multi-task learning highly reduces the number of parameters in the machine learning models and thus reduces the computational and storage requirements. When we apply multi-task learning on deep neural networks (DNNs), we need to further compress the model since the model size of a single DNN is still a critical challenge to many computation systems, especially for edge platforms. However, when model compression is applied to multi-task learning, it is challenging to maintain the performance of all the different tasks. To deal with this challenge, we propose a min-max optimization framework for the training of highly compressed multi-task DNN models. Our proposed framework can automatically adjust the learnable weighting factors corresponding to different tasks to guarantee that the task with worst-case performance across all the different tasks will be optimized.
