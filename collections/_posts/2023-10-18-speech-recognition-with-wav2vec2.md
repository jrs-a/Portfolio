---
layout: post
title: "speech recognition with wav2vec2"
date: 2023-10-18 00:00:00 +0800
filter: ml
tags:
  - audio processing
  - speech recognition
  - wav2vec2
  - python
  - transformers
  - pytorch
img: assets/images/thesis.png
permalink: /:year/:month/:title
---
This project [fine-tunes](https://huggingface.co/jrs-a/wav2vec2_batangueno) a base facebook/wav2vec2-base model from huggingface. For this study the recordings for the [dataset](https://huggingface.co/datasets/jrs-a/batangueno-accent) was gathered by us. Hyperparameter search was also done to find the best hyperparameters. This resulted in a word error rate (WER) of 26% and a loss of 0.57%.

[link to google colab](https://colab.research.google.com/drive/1HS-7o2_LCTIrZuy0wZUATCL9aXK7Q42j?usp=sharing)