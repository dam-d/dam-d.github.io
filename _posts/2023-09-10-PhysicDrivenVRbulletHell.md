---
date: 2023-09-10 12:26:40
layout: post
title: Unity DOTS - Simulation physique VR
subtitle: Une quantit&eacute;  massive d'objets physique A massive number of physic driven entities powered by Unity DOTS.
description: A massive number of physic driven entities powered by Unity DOTS.
image: /assets/img/posts/BulletHellVR.png
optimized_image: /assets/img/posts/BulletHellVR_Optimized.png
category: unity
tags:
  - unityDOTS
author: damien
---

This project was initiated with the primary goal of <strong>enhancing my coding scalability skills</strong>. As someone with a background predominantly in traditional object-oriented programming using .NET and Unity, venturing into data-driven development was an entirely new realm for me. The introduction to Entity Component System (ECS) within Unity's DOTS framework presented an invaluable opportunity to immerse myself in and assimilate <strong>clean and scalable programming patterns</strong> within a data-driven architectural context.

Furthermore, the Unity DOTS physics package, renowned for its capacity to handle an extensive number of physics entities, captivated my interest and curiosity. This project not only facilitated my learning journey but also allowed me to create visually appealing simulations : <strong>a perfect blend of aesthetics and technical skill development.</strong> It has been a truly rewarding experience.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/BulletHell1.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>latest version : 20 000 physic entities driven by a custom movement system, recorded in editor.</p>
</div>

Additionally, this provided a good opportunity to delve into <strong>VFX graph technology</strong>, facilitating the transition of allocated resources from the CPU to the GPU. Given the CPU-intensive nature of physics simulations, this shift empowered me <strong>to further scale the number of physical entities within the project.</strong>

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BulletHellGamepad.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>Also playable on normal flatscreen with gamepad or kb/m</p>
</div>

A huge work on other optimizations has been done to maintain the VR target of 90 fps.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BulletHell2.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>VR gameplay of an earlier prototype without post processing.</p>
</div>

It also allowed me <strong>to consolidate and enhance my existing skill set</strong> encompassing various domains, including VR interactions, game and level design, modeling, texturing, VFX, audio management, lighting, and post-processing.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BulletHell3.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>Smooth entities movement chasing the player.</p>
</div>