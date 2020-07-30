---
layout: publication
title: "Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement"
authors: Chunle Guo, Chongyi, Jichang Guo, Chen Change Loy, Junhui Hou, Sam Kwong, Runmin Cong
conference: Arxiv
year: 2020
bibkey: guo2020zero
additional_links:
   - {name: "PDF", url: "https://arxiv.org/pdf/2001.06826.pdf"}
   - {name: "URL", url: "https://li-chongyi.github.io/Proj_Zero-DCE.html"}
tags: ["CVPR", "Image Enhancement", "Low-Light", "Deep Learning"]
---
The paper presents a novel method, Zero-Reference
Deep Curve Estimation (Zero-DCE), which formulates light
enhancement as a task of image-specific curve estimation
with a deep network. Our method trains a lightweight deep
network, DCE-Net, to estimate pixel-wise and high-order
curves for dynamic range adjustment of a given image.The
curve estimation is specially designed, considering pixel
value range, monotonicity, and differentiability. Zero-DCE
is appealing in its relaxed assumption on reference images,
i.e., it does not require any paired or unpaired data during training. This is achieved through a set of carefully
formulated non-reference loss functions, which implicitly
measure the enhancement quality and drive the learning
of the network. Our method is efficient as image enhancement can be achieved by an intuitive and simple nonlinear
curve mapping. Despite its simplicity, we show that it generalizes well to diverse lighting conditions. Extensive experiments on various benchmarks demonstrate the advantages of our method over state-of-the-art methods qualitatively and quantitatively. Furthermore, the potential benefits of our Zero-DCE to face detection in the dark are
discussed. Code and model will be available at https:
//github.com/Li-Chongyi/Zero-DCE
