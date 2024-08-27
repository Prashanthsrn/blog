---
title: "Interior Design Generator"
excerpt: "An AI powered tool that generates rooms in different interior design styles"
collection: portfolio
---

This project aimed at developing a tool that could give outputs of a room in different interior design styles, given the input of a basic room's image. 

*Implementation*
  - The model was trained using LoRA (Low-Rank Adaptation) and Kohya SS. The model was trained for specific rooms and styles.
  - The AI was capable of generating rooms in styles such as cyberpunk, Mediterranean, minimalist, and Indian royal. Specific rooms, like puja rooms, which are more specific to the Indian cultural context were also trained
  - Created a ComfyUI workflow, where the users could input an image of their room and would get outputs of that room in different styles. (This was done using the edge control trait)

<img title="Comfy UI workflow" src="../images/Screenshot 2024-08-27 at 10.11.12 AM.png">
