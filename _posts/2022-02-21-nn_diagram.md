---
layout: post
title: Neural Network learning diagram
date: 2022-02-21 00:00:00 +0300
description: Simple diagram of how neural networks learn, including data, weights, activations and gradients.
img: NN_diagram.jpg 
tags: [Artificial Intelligence, Neural Network, Diagram, Map]
---

The learning process of artificial neural networks is pretty straightforward. Assuming the status of a neural network is represented by a set of weights, the neural net first processes some input data, reacts to that data, computes the error commited, and modifies itself (the set of weights) to reduce the error.

I've talked and taught this so many times, sometimes it seems like it's hidding something else. I did this simple diagram to illustrate the temporal evolution of a neural net, just in case it was hidding something I missed.

* D stands for data. What the neural net learns from.
* W stands for weights. The internal status of the neural net in a given time.
* A stands for activations. The reaction and outcome of the neural net (W) when processing D.
* G stands for gradients. The modification the neural net applies to itself (W) in order to minimize the error commited when processing D.

![Neural Net Diagram]({{site.baseurl}}/assets/img/NN_diagram.jpg)

And that's it. Loss/Objective function, backprop and gradient descent are missing from the diagram, since these are temporally static components. Primas are used to illustrate the temporal change of D and W (in the case of D, accounts for different training samples). Data is painted yellow because its exogeneous to the network.

If you find this diagram useful or thought provoking, let me know!
