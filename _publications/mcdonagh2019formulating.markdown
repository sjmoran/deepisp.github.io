---
layout: publication
title: "Formulating Camera-Adaptive Color Constancy as a Few-shot Meta-Learning Problem"
authors: Steven McDonagh, Sarah Parisot, Fengwei Zhou, Xing Zhang, Ales Leonardis, Zhenguo Li, Gregory Slabaugh
conference: ICCVW
year: 2019
bibkey: mcdonagh2019formulating
additional_links:
   - {name: "PDF", url: "https://arxiv.org/pdf/1811.11788.pdf"}
tags: ["Color Constancy","ICCV"]
---
Digital camera pipelines employ color constancy methods to estimate an unknown scene illuminant, in order to reilluminate images as if they were acquired under an achromatic light source. Fully-supervised learning approaches
exhibit state-of-the-art estimation accuracy with cameraspecific labelled training imagery. Resulting models typically suffer from domain gaps and fail to generalise across
imaging devices. In this work, we propose a new approach
that affords fast adaptation to previously unseen cameras,
and robustness to changes in capture device by leveraging
annotated samples across different cameras and datasets.
We present a general approach that utilizes the concept of
color temperature to frame color constancy as a set of distinct, homogeneous few-shot regression tasks, each associated with an intuitive physical meaning. We integrate this
novel formulation within a meta-learning framework, enabling fast generalisation to previously unseen cameras using only handfuls of camera specific training samples. Consequently, the time spent for data collection and annotation
substantially diminishes in practice whenever a new sensor is used. To quantify this gain, we evaluate our pipeline
on three publicly available datasets comprising 12 different
cameras and diverse scene content. Our approach delivers competitive results both qualitatively and quantitatively
while requiring a small fraction of the camera-specific samples compared to standard approaches.
