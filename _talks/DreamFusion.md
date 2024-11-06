---
title: "DreamFusion: Text-to-3D using 2D diffusion"
collection: talks
permalink: /talks/Atari
---

This paper presents a method called DreamFusion, for generating 3D models from text descriptions by leveraging pre-trained 2D diffusion models. Models like ImageGen can generate 2D images based on text descriptions. DreamFusion adapts these models to create 3D objects. 

DreamFusion allows zero-shot 3D object generation from text without the need for any 3D training data. Dreamfusion starts the diffusion process from a randomly initialized NeRF, which is a way to represent 3D scenes mathematically. Then Dreamfusion renders the NeRF from different camera views, generating 2D images, each representing the current 3D scene. 
Each of these 2D images goes through the diffusion process to more accurately match the text description. These 2D gradients are then used to update the parameters of the NeRF, this process is called SDS (Score Distillation Sampling). Thus through this process, the 3D model slowly starts matching the text description. You can find the original paper [here](https://arxiv.org/pdf/2209.14988)
