
---
title: "2D Image depth estimation"
excerpt: "A program that generates the depth map of a 2D image and using this depth map develops a point cloud 3D model of the object"
collection: portfolio
---

This is a depth estimation project using GLPN for depth prediction. This depth map is then used to predict the pointcloud view of the object. 
*Implementation*
- Loaded and preprocessed an image to meet size requirements (divisible by 32 and maintain aspect ratio)
- Use GLPN Neural network to estimate the depth of each pixel in the image producing a depth map
- Tried combining the original RGB image with the depth map to produce a point cloud view of the object. (Unsatisfactory results) 
Github Repo for this project : [link](https://github.com/Prashanthsrn/DepthEstimation)



<img width="469" alt="Screenshot 2024-11-06 at 4 03 55 PM" src="https://github.com/user-attachments/assets/49b0f2ab-f946-42bb-8ecf-34affa72b067">
