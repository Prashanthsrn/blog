---
title: "ImageNet Classification with Deep Convolutional Neural Networks"
collection: talks
permalink: /talks/AlexNet
---

This paper tackles the challenge of training very deep neural networks, which often suffer from vanishing and exploding gradients, leading to a degradation problem where performance worsens as layers increase. The researchers address this problem by using a residual learning framework. Instead of approximating a function *H(x)*, they approximate *F(x) = H(x) - x*.

The building block of a ResNet is a residual block where the input is added to the output of a few stacked layers *[y = F(x, {Wi}) + x]*, where *{Wi}* is the weights of the stacked layers. In addition to this, shortcut connections, where a few layers are skipped provide a direct path is also part of this framework. 
The ResNet built with this framework was trained with different depths and performed better with more layers. ResNet, using this framework, achieved state-of-the-art results on the ImageNet classification and COCO object detection tasks.
This innovative approach not only overcame the challenges of training very deep networks but also set a new benchmark in computer vision tasks, influencing the design of many subsequent deep learning models.
