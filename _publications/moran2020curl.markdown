---
layout: publication
title: "CURL: Neural Curve Layers for Global Image Enhancement"
authors: Sean Moran, Steven McDonagh, Gregory Slabaugh
conference: Arxiv
year: 2020
bibkey: moran2020curl
additional_links:
   - {name: "PDF", url: "https://arxiv.org/pdf/1911.13175.pdf"}
   - {name: "Code", url: "https://github.com/sjmoran/neural_curve_layers"}
tags: ["End-to-End", "Deep Learning", "Arxiv"]
---
We present a novel approach to adjust global image properties such as colour, saturation, and luminance using human-interpretable image enhancement curves, inspired by the Photoshop curves tool. Our method, dubbed neural CURve Layers (CURL), is designed as a multi-colour space neural retouching block trained jointly in three different colour spaces (HSV, CIELab, RGB) guided by a novel multi-colour space loss. The curves are fully differentiable and are trained end-to-end for different computer vision problems including photo enhancement (RGB-to-RGB) and as part of the image signal processing pipeline for image formation (RAW-to-RGB). To demonstrate the effectiveness of CURL we combine this global image transformation block with a pixel-level (local) image multi-scale encoder-decoder backbone network. In an extensive experimental evaluation we show that CURL produces state-of-the-art image quality versus recently proposed deep learning approaches in both objective and perceptual metrics, setting new state-of-the-art performance on multiple public datasets.
