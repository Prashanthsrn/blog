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




<img width="1141" alt="Screenshot 2024-11-06 at 11 53 58 AM" src="https://github.com/user-attachments/assets/fe0a1ab9-cd97-4511-a940-57de46ec4c9f">
