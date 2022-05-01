---
layout: post
title: Neural Network learning diagram
date: 2022-02-21 00:00:00 +0300
description: Simple diagram of how neural networks learn, including data, weights, activations and gradients.
img: NN_diagram.jpg 
tags: [Artificial Intelligence, Neural Network, Diagram, Map]
---

The learning process of artificial neural networks can be summarized as follows. Assuming the status of a neural network is represented by a set of trainable weights, the neural net processes some input data samples, reacting to it internally through a set of activations. When the output of the net is reached, the error committed is computed, and an update process takes place, in which the trainable weights are modified with the goal of minimizing the error committed.

I've taught this so many times, sometimes it feels strange. Like when you keep repeating a word until you no longer recognize it. At times it feel like it's hiding something else, something fundamental. For my own satisfaction (currently I don't see the point of using this as teaching material) I created a diagram to illustrate the temporal evolution of a neural net. This is a representation I had not seen before, and it could be hiding something.

* D stands for data. What the neural net learns from.
* W stands for weights. The internal status of the neural net in a given time.
* A stands for activations. The reaction and outcome of the neural net (W) when processing D.
* G stands for gradients. The modification the neural net applies to itself (W) in order to minimize the error comited when processing D.

![Neural Net Diagram]({{site.baseurl}}/assets/img/NN_diagram.jpg)

And that's it. Loss/Objective function, backprop and gradient descent are missing from the diagram, since these are temporally static components. Primas are used to illustrate the temporal change of D and W (in the case of D, accounts for different training samples). Data is painted yellow because its exogenous to the network.

If you find this diagram useful or inspiring, let me know! It was an interesting exercise, but I didn't got any revelation myself...

Cheers
