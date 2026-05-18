---
layout: default
title: "Joshua E. Yu"
---

## Welcome!

My name is Josh, and I'm currently pursuing an M.S. in Computer Science at the Georgia Institute of Technology through its OMSCS program. My interests and work lie in the intersection of computer graphics, computer vision, and deep learning.

This past semester (Spring 2026), I conducted research with the [UF BioVision Lab](https://www.biovisionlab.com/home){:target="_blank"} through Georgia Tech, focusing on probabilistic uncertainty estimation within a 3D shape completion pipeline for lizard vertebrae. Last summer (2025), I was a Machine Learning Intern at [General Atomics Aeronautical Systems (GA-ASI)](https://www.ga-asi.com){:target="_blank"} where I developed a computer vision model for radar systems. I primarily used Python and PyTorch during both experiences.

On my own time, I enjoy learning 3D graphics concepts and implementing them using graphics APIs. So far, I've used WebGPU for 2D fluid simulation and OpenGL for real-time 3D rendering. Check out my [personal projects](#projects---personal) as well as my [coursework project highlights](#projects---coursework) below!

Previously, I earned a B.S. in Chemical Engineering from the University of California, Los Angeles (UCLA). Upon graduating, I worked at Takeda Pharmaceutical Company in multiple technical operations roles, the longest and most recent of which was as an Automation Engineer.

---

## Projects - Personal

<article markdown="block">
### [San Francisco's MUNI Fleet, Visualized in a WebGPU Fluid Dynamics Simulation](https://github.com/joshuaeyu/fluidmetro){:target="_blank"}

[!["Fluid simulation screenshot"](/images/fluidmetro-screenshot.png "Fluid simulation screenshot"){:.project-image}](https://github.com/joshuaeyu/fluidmetro){:target="_blank"}

This is a GPU-accelerated (via WebGPU) web browser implementation of Jos Stam's real-time fluid dynamics solver originally presented in his seminal paper "Stable Fluids" from 1999. This project additionally includes a light backend which provides live and historical vehicle positions of San Francisco's MUNI (public transit) fleet to the frontend fluid simuation. Together, these create a fun way to visualize real-world data (and a rewarding way for me to learn the basics of web development, a new graphics API, and GPGPU)!
</article>

<article markdown="block">
### [Real-Time 3D Graphics Engine](https://github.com/joshuaeyu/plum){:target="_blank"}

[![Plum graphics engine screenshot](/images/screenshot_demo1.png "Plum graphics engine screenshot"){:.project-image}](https://github.com/joshuaeyu/plum){:target="_blank"}

Plum is a simple real-time graphics engine built using OpenGL 4.1 and C++17. It features a deferred rendering pipeline and physically based shading. Users can create materials and instantiate models, primitives, and lights into the scene from the engine's GUI. While developing this, I learned a lot about software design patterns, C++ development, the OpenGL graphics API, and real-time 3D rendering techniques.
</article>

<hr>

<!-- <article markdown="block">
### [Real-Time Fluid Simulation following Jos Stam's *Stable Fluids*](https://github.com/joshuaeyu/stablefluids)

[!["Fluid simulation screenshot"](/images/stablefluids.png "Fluid simulation screenshot"){:.project-image}](https://github.com/joshuaeyu/stablefluids)

I've ported Jos Stam's original demo, written in C and GLUT for early versions of OpenGL, to OpenGL 3.3 using GLAD and GLFW. I've additionally introduced modifications such as periodic (toroidal) boundary conditions and colored visualization of velocity.
</article> -->

## Projects - Coursework

<article markdown="block">
### [Image Representation with 2D Gaussians](https://github.com/joshuaeyu/2dgs){:target="_blank"}

[!["2D Gaussian Splatting GIF 0"](/images/2dgs_movie0.gif "2D Gaussian Splatting GIF 0"){:.project-image-small}](https://github.com/joshuaeyu/2dgs){:target="_blank"}
[!["2D Gaussian Splatting GIF 1"](/images/2dgs_movie1.gif "2D Gaussian Splatting GIF 1"){:.project-image-small}](https://github.com/joshuaeyu/2dgs){:target="_blank"}

This is the code for my final project in *CS 8803 O27: Computer Graphics in the AI Era* at the Georgia Institute of Technology. This project implements a robust 2D Gaussian-based image representation model and investigates how image complexity impacts the number of Gaussians needed to achieve a certain level of reconstruction quality. Much of my 2DGS implementation is inspired by the formulation and implementation notes laid out in Zhang et al.'s Image-GS.
</article>

<hr>{:.weak-hr}

<article markdown="block">
### [Optimizing Neural Network Learning with Clustering and Dimensionality Reduction](unsuplearning)

[!["Neural network performance table"](/images/neuralnetwork_dimred_clustering.png "Neural network performance table"){:.project-image-large}](unsuplearning)

This article is an overview of my work on the corresponding assignment in *CS 7641: Machine Learning* at the Georgia Institute of Technology. This project demonstrates how unsupervised learning techniques such as clustering and dimensionality reduction can be used to optimize supervised learning for two datasets available on the UC Irvine Machine Learning Repository.
</article>

<hr>{:.weak-hr}

<article markdown="block">
### [Spider-Man Minigame](https://github.com/joshuaeyu/cs174a-spiderman-minigame)

[![Spider-Man minigame screenshot](/images/screenshot1.png "Spider-Man minigame screenshot"){:.project-image}](https://github.com/joshuaeyu/cs174a-spiderman-minigame){:target="_blank"}

This was my team's final project in *COM SCI 174A: Introduction to Computer Graphics* at UCLA. We implemented physics, swinging and wall-climbing mechanics, collision detection, audio, and player/camera controls on top of the WebGL-based graphics library that was provided by the course.
</article>

<hr>

## Coursework

### Georgia Institute of Technology

* CS 6200: Graduate Introduction to Operating Systems
* CS 6300: Software Development Process
* CS 6457: Video Game Design
* CS 6476: Computer Vision
* CS 6491: Foundations of Computer Graphics
* CS 6601: Artificial Intelligence
* CS 6750: Human-Computer Interaction
* CS 7641: Machine Learning
* CS 8001 ODA: Data Structures & Algorithms Seminar
* CS 8803 O27: Computer Graphics in the AI Era
* CS 8903: Special Projects
* CSE 6220: Introduction to High-Performance Computing

### University of California, Los Angeles

* COM SCI 31/32: Introduction to Computer Science I/II
* COM SCI 174A: Introduction to Computer Graphics
* CH ENGR 107: Process Dynamics and Control
* CH ENGR 109: Numerical and Mathematical Methods in Chemical and Biological Engineering