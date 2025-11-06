---
title: "Human Presence Detection Using Thermal Camera and STM32 by DFS Cluster Detection"
excerpt: "STM32 H723ZG, MLX90640 and ILI9341 based low resolution thermal camera with bi-linear upscaling
---

![Thesis Test Setup](/Demos/img1.jpg "Thesis Test Setup")

It is a **low-resolution, low-cost thermal camera** with video streaming support via USB Serial.  
The code detects clusters using a **Depth-First Search (DFS)** algorithm and triggers an output whenever the cluster size exceeds a threshold.  
This is an experimental attempt to detect **human presence using an MCU**.  
A Python client script is also available to stream the thermal camera output as video.

| Demo Python Client | Demo Python Client |
|:---------------:|:----------------:|
| ![Front CAD View](/Demos/img_13.png "Front CAD View") | ![Front Real View](/Demos/img_9.png "Front Real View") |

<p align="center">
  <b>
    <a href="https://drive.google.com/file/d/12doL1PNrvsDzEYfPceme25Krje_h22S3/view?usp=drive_link">
      ▶️ Video Demo
    </a>
  </b>
</p>
