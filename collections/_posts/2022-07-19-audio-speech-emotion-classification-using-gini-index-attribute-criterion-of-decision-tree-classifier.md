---
layout: post
title: "audio/speech emotion classification using gini index attribute criterion of decision tree classifier"
date: 2022-07-19 00:00:00 +0800
filter: ml
tags:
  - audio processing
  - emotion classification
  - classification
  - decision tree
  - sklearn
  - python
img: assets/images/CS171_M2SA.png
permalink: /:year/:month/:title
docu: "/assets/docs/CS171_M2SA.pdf"
---
This is an audio processing task done with sklearn python library where we classify the emotion of the audios using decision tree with its gini index attribute criterion.
Audio features extracted namely chromagram, melspectrogram, and MFCC are used as input features for the decision tree model which yielded an accuracy of 11% during training and 15% during testing.

[link to google colab](https://colab.research.google.com/drive/1XWuLXQzcKqgFVsYdktQtULTVl5t6qzzd?usp=sharing)