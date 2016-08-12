---
layout: post
title: "Word Embeddings"
author: ahaldar
categories: articles
excerpt:
tags: [NLP]
image:
  feature: so-simple-sample-image-6.jpg
  credit:
  creditlink:
comments: true
share: true
---

An image is easy enough to encode as a vector with all the pixel intensity values. This means that two similar images are likely to have vectors that are similar too.
On the other hand, for text, individual words are often encoded using arbitrary reference ids. Thus despite the obvious similarities between "cat" and "dog", the ids could be vastly different.

As it turns out, to quote J. R. Firth:

> You shall know a word by the company it keeps

So a more intuitive way to represent words, known as word2vec, generates vectors in high-dimensional space for words in a text based on the neighbouring words. Given enough training examples, this seems to bring out a lot of interesting relationships.

![Word2Vec](https://www.tensorflow.org/versions/master/images/linear-relationships.png "Word2Vec")

