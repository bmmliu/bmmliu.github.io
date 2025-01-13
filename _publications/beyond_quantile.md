---
title: "Beyond Quantile Methods: Improved Top-K Threshold Estimation for Traditional and Learned Sparse Indexes (IEEE BigData 2024)"
collection: publications
category: conferences
permalink: /publication/beyond_quantile
excerpt: ''
citation: ''
date: 2024-12-14
venue: 'Jinrui Gou, Yifan Liu, Minghao Shao, Torsten Suel'
slidesurl: 'https://scholar.google.com/citations?view_op=view_citation&hl=en&user=pplw1EYAAAAJ&sortby=pubdate&citation_for_view=pplw1EYAAAAJ:ufrVoPGSRksC'
paperurl: 'https://arxiv.org/abs/2412.10701'
citation: ''
---

Top-k threshold estimation is the problem of estimating the score of the k-th highest ranking result of a search query. A good estimate can be used to speed up many common top-k query processing algorithms, and thus a number of researchers have recently studied the problem. Among the various approaches that have been proposed, quantile methods appear to give the best estimates overall at modest computational costs, followed by sampling-based methods in certain cases. In this paper, we make two main contributions. First, we study how to get even better estimates than the state of the art. Starting from quantile-based methods, we propose a series of enhancements that give improved estimates in terms of the commonly used mean under-prediction fraction (MUF). Second, we study the threshold estimation problem on recently proposed learned sparse index structures, showing that our methods also work well for these cases. Our best methods substantially narrow the gap between the state of the art and the ideal MUF of 1.0, at some additional cost in time and space.
