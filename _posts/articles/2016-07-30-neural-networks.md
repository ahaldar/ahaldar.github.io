---
layout: post
title: "Neural Networks"
author: ahaldar
categories: articles
excerpt:
tags: [neural networks, neural style, art]
image:
  feature: so-simple-sample-image-7.jpg
  credit:
  creditlink:
comments: true
share: true
---

Recently, a program that enthralled me was based on a paper on “A neural algorithm of artistic style”, which was able to combine two images preserving the content of one and the artistic style of the other. I tuned some parameters, had my GPU struggling for hours, and was delighted by the resulting images.

Here's a sample:

The input image I fed the network:
![Image](https://raw.githubusercontent.com/ahaldar/neural-style/master/1-my-content.jpg "Image")

The style I wanted the resulting image to be in:
![Style](https://raw.githubusercontent.com/ahaldar/neural-style/master/1-my-style.jpg "Style")

The output after several hours:
![Output](https://raw.githubusercontent.com/ahaldar/neural-style/master/1-my-output.jpg "Output")

Imagine my surprise when the Prisma smartphone app became hugely popular just a month later, as it seemed to be based on the very same convolutional neural network techniques, with the advantage of big external servers for speed! That feeling of being at the very cutting-edge of research was unforgettable.



