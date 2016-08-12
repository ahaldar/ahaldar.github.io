---
layout: post
title: "Can Any Noun Be Verbed?"
author: ahaldar
categories: articles
excerpt:
tags: [graph theory, NLP]
image:
  feature: so-simple-sample-image-5.jpg
  credit:
  creditlink:
comments: true
share: true
---

Somewhat recently, the erstwhile distinct worlds of computational linguistics and graph theorists collided. Researchers discovered that graphs offered a convenient way to represent text.
The nodes could be words, sentences, or entire documents. The edges and their weights could suggest connections and similarities between nodes.

Thus was born the area of graph-based natural language processing, and under it fell intriguing tasks such as text summarisation, document classification, sentiment ananlysis, and more.

# TL;DR
To summarise a piece of text, traditional methods use statistical means to identify keywords, and then try to ensure that the relevant sentences are given priority.
Graph-based methods instead employ techniques like random walks, to "travel" through the entire document. The summaries generated are rated to select the best.

![Emoji summary](http://www.epicreads.com/uploads/blog/EmojiReads_TFIOS_EpicReads.jpg "Emoji summary")

# Garden paths

Graphs can be used to express how a sentence is split into the various noun phrases and verb phrases and determiners and connectors and so on and so forth.

The occasional sentence might trip it up though. Here's a classic example that leaves a human chuckling and a computer (figuratively) scratching its head:

> Time flies like an arrow; fruit flies like a banana

![Arrow Banana](http://www.thequotepedia.com/images/32/fruit-flies-like-a-banana-time-quote.jpg "Arrow Banana")
