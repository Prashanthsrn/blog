---
title: "Histogram Equalisation using Halide"
excerpt: "This is a histogram equalisation tool developed using the domain specefic language Halide"
collection: portfolio
---

A Halide-based implementation of Histogram equalization, which is an image processing technique that improves the contrast. This project uses halide optimization capabilities to efficiently process images on the CPU using parallelization and vectorization.
*Implementation*
  - First, the histogram of pixel intensities in the input image is calculated (0-255) using Halide's reduction domain (RDom) to count occurrences of each intensity level.
  - It then calculates the cumulative distribution function (CDF) by summing up the histogram values and normalizes this CDF to create a mapping function that redistributes the intensity values.
  -  Finally, it applies this mapping to each pixel in the input image using Halide's optimized pipeline, which processes the image in parallel strips and uses SIMD instructions (through vectorization) for better performance on CPUs.
  - [Github](https://github.com/Prashanthsrn/halide_projects/tree/main/halide_histogram)
  
  
  
  ![image (1)](https://github.com/user-attachments/assets/dcac126c-af4f-4f20-864d-c9fb552ccd90)
