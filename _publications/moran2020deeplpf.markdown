---
layout: publication
title: "DeepLPF: Deep Local Parametric Filters for Image Enhancement"
authors: Sean Moran, Pierre Marza, Steven McDonagh, Sarah Parisot, Gregory Slabaugh
conference: CVPR
year: 2020
bibkey: moran2020deeplpf
additional_links:
   - {name: "PDF", url: "https://arxiv.org/pdf/2003.13985.pdf"}
   - {name: "Code", url: "https://github.com/sjmoran/deep_local_parametric_filters"}  
tags: ["CVPR", "Image Enhancement", "Deep Learning"]
---
Digital artists often improve the aesthetic quality of digital photographs through manual retouching. Beyond global adjustments, professional image editing programs provide local adjustment tools operating on specific parts of an image. Options include parametric (graduated, radial filters) and unconstrained brush tools. These highly expressive tools enable a diverse set of local image enhancements. However, their use can be time consuming, and requires artistic capability. State-of-the-art automated image enhancement approaches typically focus on learning pixel-level or global enhancements. The former can be noisy and lack interpretability, while the latter can fail to capture fine-grained adjustments. In this paper, we introduce a novel approach to automatically enhance images using learned spatially local filters of three different types (Elliptical Filter, Graduated Filter, Polynomial Filter). We introduce a deep neural network, dubbed Deep Local Parametric Filters (DeepLPF), which regresses the parameters of these spatially localized filters that are then automatically applied to enhance the image. DeepLPF provides a natural form of model regularization and enables interpretable, intuitive adjustments that lead to visually pleasing results. We report on multiple benchmarks and show that DeepLPF produces state-of-the-art performance on two variants of the MIT-Adobe-5K dataset, often using a fraction of the parameters required for competing methods.
