---
title: "3D face reconstruction"
excerpt: "A program that captures a face using the webcam and converts it into an 3D obj file"
collection: portfolio
---

A real-time facial landmark detection and 3D model generation tool using MediaPipe and OpenCV. This application captures facial landmarks through your webcam and allows you to export them as 3D models in OBJ format.

*Implementation*
- Used MediaPipe's Face Mesh to detect and track 468 facial landmarks in real time from webcam feed
- these landmarks are rendered as a mesh overlay on the video feed using OpenCV, with custom scaling for better 3D visualization
- When saved, converts the facial landmarks into a 3D mesh and saves it as an OBJ file with proper vertex and face topology

Github Repo for this project : [link](https://github.com/Prashanthsrn/face_reconstruction)



<img width="840" alt="Screenshot 2024-11-06 at 12 40 17 PM" src="https://github.com/user-attachments/assets/66d7f918-872f-4bfa-8bef-0ac9d12227e8">
