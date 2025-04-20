---
layout: post
title: Artificial Neural Network learning methods scheme
date: 2025-03-10 00:00:00 +0300
description: As of early 2025, there's a variety of learning methods for artificial neural nets. This post includes a diagram clarifying their relative relation, making it accessible and easy to introduce to others.
img: learning.jpg 
tags: [Artificial Intelligence, Neural Network, LLM, Diagram]
---

The popularization of large language models (LLMs) has resulted in the porposal and use of a variety of learning methods. This post tries to organize the main methods being used for LLM learning as of early 2025.

Learning methods in LLMs can be first discriminated between weight-based learning (methods that change the internal state of the neural network), and in-context learning methods (methods that bias the neural network output, but do not change its parameters). While it remains arguable if in-context learning is learning at all, as it does not change the model, it is currently a very popular approach due to its low cost (do not require back-propagation) and strong effect during inference. In-context learning can be separated in two types: Prompt engineering, which only uses the model output as source of bias, and RAG, which uses external data sources.

![Learning methods]({{site.baseurl}}/assets/img/learning.jpg)

Within weight-based learning methods, model merging combines the weights of two or more compatible models, mainly by averaging analogous parameters. This is a cheap method (again, does not require back-prop.) that provides small gains on generalization capacity. Its main downside is the requirement of independent and yet compatible trained models.

Loss-based learning includes the most common learning techniques for artificial neural networks. That is, based on the back-propagation algorithm. This can be based on next token prediction on raw data (pre-train), it can be based on masked (answer only) next token prediction for assistant like data (SFT), or it can include other loss methods which are not based on token prediction (e.g., DPO, GRPO) which helps steer the model towards specific behaviors while requiring less data.

These methods can be also categorized based on their use to produce instruction following models (instruct tune), as well as the specialization of models on certain domains (domain adaptation).

Notice this is just a quick introduction to the main concepts, and excuse the brevity and lack of detail.

### Reference

This diagram is included in a manuscript under review as of early 2025. Reference to be added soon.

