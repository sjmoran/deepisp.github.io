---
layout: page
title: Taxonomy
description: A taxonomy of deep learning models for the image signal processor (ISP) 
---

 * [**Demosaicing Models**](quantisation.html) focus on quantising the real-valued low-dimensional projections of data-points into binary bits by positioning one or more thresholds along a projected dimension.
 
 * [**Denoising Models**](independent.html) these methods fracture the input feature space using randomly drawn hyperplanes independently of the data distribution. Given the random nature of the learning procedure they are the fastest models at training time but suffer from the disadvantage of requiring long hashcodes and many hashtables to attain a reasonable level of retrieval effectiveness.
 
 * [**Auto-White Balance (AWB) Models**](supervised.html) are models that leverage available semantic supervision in the form of, for example: class labels or must-link and cannot-link constraints between data-point pairs. The models exploit this supervision during the learning process to maximise the occurrence of related data-points being hashed to the same hashtable buckets. These models typically exhibit the highest retrieval effectiveness but suffer the disadvantage of requiring manual labels which can be challenging to collect.

 * [**Colour Mapping Models**](unsupervised.html) are models that account for the distribution of the data in an unsupervised manner without the need manually acquired labels. They typically achieve this by using techniques that factorise the data covariance matrix or cluster related data-points into groups. These models generally exhibit a good retrieval effectiveness lying somewhere between the data independent and supervised models, but suffer from the considerable advantage of being computationally expensive at training time due to the matrix factorisation component.
