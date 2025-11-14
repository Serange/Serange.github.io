---
layout: project
title: 'Vulkan Ray Tracing Engine'
date: '22-05-2023'
description: >
    University Dissertation
sitemap: false
image: /assets/portfolio/university/fyp/fyp.gif
---
For my final year project, I opted to take my passion for low level graphics even further and delved into the new generation of graphics APIs, DirectX 12 and Vulkan.

As part of this project I wanted to really explore what makes these newer APIs different from the previous generation of DirectX 11 and OpenGL. 
Beyond its verbosity to aid CPU overhead the key feature that was introduced was hardware ray tracing.

The aim of my final year project was to create an engine that was capable of supporting both raster and ray tracing techniques in real time.
I wanted to explore what existing rasterization techniques could be affected by the introduction of ray tracing;
highlighting each technique’s strengths and weaknesses in terms of both performance and fidelity.

Before any comparisons could begin, a basic implementation of Vulkan was required. This is where Vulkan’s reputation really came to fruition.
Vulkan has an exorbitant amount of boiler plate code, code which is repeated in multiple places with little to no variation,
unlike DirectX 11 and OpenGL both DirectX12 and Vulkan are very explicit and require every element of rendering to be setup manually.
Some setup time was taken into consideration; however, as development proceeded, it was clear that it was drastically underestimated.
More aspects required manual setup than initially planned, largely due to naivety, this severely hindered development early on.

A basic rasterised scene using PBR techniques with a 8K shadow map.
![](/assets/portfolio/university/fyp/raster_shadow.png)

To streamline development, I integrated several libraries in areas where research and development were not the focus:

- [GLM](https://github.com/icaven/glm), - Mathematics library
- [GLFW](https://github.com/glfw/glfw), - Window and input handling
- [VkBootstrap](https://github.com/charles-lunarg/vk-bootstrap) – Simplified Vulkan boilerplate setup
- [VMA](https://gpuopen.com/vulkan-memory-allocator/) – GPU memory management (used in Godot, Quake RTX)
- [Assimp](https://github.com/assimp/assimp), [stb_image](https://github.com/nothings/stb) – Asset Loading

With this being a final year project; managing time between research, learning and development was something that became paramount to the project.
The process strengthened my understanding of modern graphics architecture and imbued me with a valuable set of skills that I’ve since carried forward into my professional career.

Throughout development I learned how modern APIs work through concepts such as:
- Command Buffers
- Queues
- Command Pools
- Frame Buffers
- Renderpasses
- Pipelines
- Sync Structures (Fences, Semaphores)

Alongside these new practices, I also learned the fundamental concepts required to support ray tracing using low-level graphics APIs,
including creating and managing acceleration structures (Bottom-Level Acceleration Structures and Top-Level Acceleration Structures)
implementing ray generation, closest-hit, miss shaders and understanding how to efficiently manage GPU memory and synchronization for real-time ray traversal.

![](/assets/portfolio/university/fyp/acceleration_structures.png)

:-:|:-: 
TLAS | BLAS
![](/assets/portfolio/university/fyp/tlas.png) | ![](/assets/portfolio/university/fyp/blas.png)

A hybrid scene using PBR techinques with ray traced shadows.
![](/assets/portfolio/university/fyp/rt_shadow.png)

After finishing my project I submitted it for [GradEx](https://www.staffs.ac.uk/gradex), Staffordshire University student showcase event.
As part of this event, I condensed my dissertation into a small presentation and went on to win 2nd place out of around 100 Games Programming students.

:-:|:-: 
![](/assets/portfolio/university/fyp/gradex.jpg) | ![](/assets/portfolio/university/fyp/gradex_cert.jpg)

The project explored the evolution of graphics APIs from DirectX 11 & OpenGL to DirectX 12 & Vulkan, 
focusing on the hybridisation of real-time ray tracing alongside traditional rasterization.
I developed a custom engine capable of hybrid rendering, gaining deep insight into modern graphics pipelines, GPU memory management, and low-level rendering concepts.
The project not only enhanced my technical expertise in modern APIs and ray tracing; but, also earned 2nd place at the Staffordshire University GradEx showcase.