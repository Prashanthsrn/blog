---
title: "Mastering the Game of Go with Deep Neural Networks and Tree Search"
collection: papers
permalink: /papers/AlphaGo
---

The paper discusses the working and achievements of the AlphaGo model, trained specifically for the complex game of Go. AlphaGo was able to achieve superhuman levels of playing Go and was able to beat world champions.

The AlphaGo model has two components, policy networks and value networks. Policy networks are trained to predict next moves given the current position. These are first trained through supervised learning, using expert human games, followed by reinforced learning through self-play. Value networks evaluate the winning probability of a position. AlphaGo combines these 2 networks within an Monte-Carlo Tree Search framework. This combination of Deep learning and Tree Search enabled AlphaGo to outperform previous models and human champions, marking a major milestone in artificial intelligence. You can find the original paper [here]([https://arxiv.org/abs/2006.08381](https://www.davidsilver.uk/wp-content/uploads/2020/03/unformatted_final_mastering_go.pdf))

