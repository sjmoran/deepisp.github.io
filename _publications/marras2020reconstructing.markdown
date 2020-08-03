---
layout: publication
title: "Reconstructing the Noise Manifold for Image Denoising"
authors: Ioannis Marras, Grigorios G. Chrysos, Ioannis Alexiou, Gregory Slabaugh, Stefanos Zafeiriou
conference: ECCV
year: 2020
bibkey: marras2020reconstructing
additional_links:
   - {name: "PDF", url: "https://arxiv.org/abs/2002.04147"}
tags: ["Denoising", "Deep Learning", "ECCV"]
---
Deep Convolutional Neural Networks (CNNs) have been successfully used in many low-level vision problems like image denoising. Although the conditional image generation techniques have led to large improvements in this task, there has been little effort in providing conditional generative adversarial networks (cGAN)[42] with an explicit way of understanding the image noise for object-independent denoising reliable for real-world applications. The task of leveraging structures in the target space is unstable due to the complexity of patterns in natural scenes, so the presence of unnatural artifacts or over-smoothed image areas cannot be avoided. To fill the gap, in this work we introduce the idea of a cGAN which explicitly leverages structure in the image noise space. By learning directly a low dimensional manifold of the image noise, the generator promotes the removal from the noisy image only that information which spans this manifold. This idea brings many advantages while it can be appended at the end of any denoiser to significantly improve its performance. Based on our experiments, our model substantially outperforms existing state-of-the-art architectures, resulting in denoised images with less oversmoothing and better detail.
