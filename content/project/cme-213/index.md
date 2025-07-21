+++
date = "2020-04-01T22:46:16-07:00"
draft = false
title = "Parallel neural network training using multiple GPUs"
url_code = "https://github.com/jbinagia/cme213-final-project"
tags = ["Course Projects"]
summary = " "
[image]
  caption = "Photo by Harrison Broadbent on Unsplash"
+++
Deep learning is quickly becoming the most powerful and ubiqutous tool within machine learning, performing well in a vast array of applications[^1]. However, for problems requiring many hidden layers for accurate calculations, the training of these neural networks can quickly become very computationally expensive. In this project, I learned how to significantly speed-up neutral network training by using [CUDA](https://en.wikipedia.org/wiki/CUDA?oldformat=true) to perform calculations on a [GPU](https://en.wikipedia.org/wiki/Graphics_processing_unit?oldformat=true) and [MPI](https://en.wikipedia.org/wiki/Message_Passing_Interface?oldformat=true) to perform these calculations in parallel across multiple [Tesla K80](https://en.wikipedia.org/wiki/Nvidia_Tesla?oldformat=true) devices.

[^1]: https://thenextweb.com/artificial-intelligence/2020/01/02/2010-2019-the-rise-of-deep-learning/
