---
layout: post
title: "Unranked Retrieval Evaluation"
date: 2017-05-31 +0900
tags: Information_Retrieval
description: DCG and NDCG
comments: true
---

Unranked Retrieval Evaluation
====

Discounted Cumulative Gain
-----
- Popular measure for evaluating web search and related tasks
	- Highly relevant documents are more useful than marginally relevant documents

![screenshot]({{ site.url }}/assets/DCG.png)
</pre>

![screenshot]({{ site.url }}/assets/DCG2.png)

![screenshot]({{ site.url }}/assets/DCG3.png)

Normalized Discounted Cumulative Gain 
-----
- Normalize DCG at rank n by the DCG value at rank n of the ideal ranking

![screenshot]({{ site.url }}/assets/NDCG.png)