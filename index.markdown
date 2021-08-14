---
layout: post
title: "KDD2021 Tutorial: High-Dimensional Similarity Query Processing for Data Science"
date: 2021-05-23 12:00:00 +0800
---

<style>
    dl>dt {
        font-size: 1.25em;
        font-weight: bold;
    }
    dl>dt:not(:first-child){
        margin-top: .5em;
    }
</style>

# High-Dimensional Similarity Query Processing for Data Science

Lecture Tutorial for The KDD Conference 2021, August 14-18, 2021

### Jianbin Qin, Wei Wang, Chuan Xiao, Ying Zhang, Yaoshu Wang

## Abstract 

Similarity query (a.k.a. nearest neighbor query) processing has been an active research topic for several decades. It is an essential procedure in a wide range of applications (e.g., classification & regression, deduplication, image retrieval, and recommender systems). Recently, representation learning and auto-encoding methods as well as pre-trained models have gained popularity. They basically deal with dense highdimensional data, and this trend brings new opportunities and challenges to similarity query processing. Meanwhile, new techniques have emerged to tackle this long-standing problem theoretically and empirically. This tutorial aims to provide a comprehensive review of high-dimensional similarity query processing for data science. It introduces solutions from a variety of research communities, including data mining (DM), database (DB), machine learning (ML), computer vision (CV), and theoretical computer science (TCS), thereby highlighting the interplay between modern DM, DB, ML, CV, and TCS technologies. We first discuss the importance of high-dimensional similarity query processing in data science applications, and then review query processing algorithms such as cover tree, locality sensitive hashing, product quantization, proximity graphs, as well as recent advancements such as learned indexes. We analyze their strengths and weaknesses and discuss the selection of algorithms in various application scenarios. Moreover, we consider the selectivity estimation of high-dimensional similarity queries, and show how researchers are bringing in state-of-the-art ML techniques to address this problem. We expect that this tutorial will provide an impetus towards new technologies for data science.



## Authors

Jianbin Qin
: Shenzhen University & Shenzhen Institute of Computing Sciences
: Shenzhen, Guangdong, China
: qinjianbin@szu.edu.cn
: +86-755-26532350

Wei Wang
: The Hong Kong University of Science and Technology
: Clear Water Bay, HKSAR, China
: weiwcs@ust.hk
: +852-2358-7029

Chuan Xiao
: Osaka University & Nagoya University
: Suita, Osaka, Japan
: chuanx@ist.osaka-u.ac.jp
: +81-6-6105-6502

Ying Zhang
: University of Technology Sydney
: Ultimo, NSW, Australia
: Ying.Zhang@uts.edu.au
: +61-2-9514-1103

Yaoshu Wang
: Shenzhen University & Shenzhen Institute of Computing Sciences
: Shenzhen, Guangdong, China
: yaoshuw@sics.ac.cn
: +86-755-26532350

## Abstract

Similarity query (a.k.a. nearest neighbor query) processing
has been an active research topic for several decades. It is an
essential procedure in a wide range of applications (e.g., 
classification & regression, deduplication, image retrieval, and
recommender systems). Recently, representation learning
and auto-encoding methods as well as pre-trained models
have gained popularity. They basically deal with dense 
high-dimensional data, and this trend brings new opportunities
and challenges to similarity query processing. Meanwhile,
new techniques have emerged to tackle this long-standing
problem theoretically and empirically.
This tutorial aims to provide a comprehensive review of
high-dimensional similarity query processing for data science. 
It introduces solutions from a variety of research communities, 
including data mining (DM), database (DB), machine learning (ML), 
computer vision (CV), and theoretical
computer science (TCS), thereby highlighting the interplay
between modern DM, DB, ML, CV, and TCS technologies. We
first discuss the importance of high-dimensional similarity
query processing in data science applications, and then review 
query processing algorithms such as cover tree, locality
sensitive hashing, product quantization, proximity graphs,
as well as recent advancements such as learned indexes. We
analyze their strengths and weaknesses and discuss the selection 
of algorithms in various application scenarios. Moreover,
we consider the selectivity estimation of high-dimensional
similarity queries, and show how researchers are bringing
in state-of-the-art ML techniques to address this problem.
We expect that this tutorial will provide an impetus towards
new technologies for data science.

## Slides

Slides
Part I: Introduction [slides](/assets/KDD21-tutorial-1-intro-wang.pdf)

Part II: Exact Query Processing [slides](/assets/KDD21-tutorial-2-exact-qin.pdf)

Part IIIa: Approximate Query Processing A [slides](/assets/KDD21-tutorial-3a-ANN-wang.pdf)

Part IIIb: Approximate Query Processing B [slides](/assets/KDD21-tutorial-3b-ANN-wang.pdf)

Part IV: Neighbourhood-based Nearest Neighbour Search [slides](/assets/KDD21-tutorial-4-knn-graph-zhang.pdf)

Part V: Selectivity Estimation [slides](/assets/KDD21-tutorial-5-selectivity-xiao.pdf)

Part V: Epilogue [slides](/assets/KDD21-tutorial-6-epilogue-wang.pdf)


## Paper

Jianbin Qin, Wei Wang, Chuan Xiao, Ying Zhang, and Yaoshu Wang: High-Dimensional Similarity Query Processing for Data Science [PDF](/assets/KDD_2021_Tutorial.pdf)



## References
TBA




