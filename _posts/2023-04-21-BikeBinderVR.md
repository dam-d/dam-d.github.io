---
date: 2023-04-21 12:00:00
layout: post
title: Bike Binder VR
subtitle: A tool to physically control Riders Republic game from a bike trainer and VR setup.
description: A tool to physically control Riders Republic game from a bike trainer and VR setup.
image: /assets/img/posts/BikeBinderVR.png
optimized_image: /assets/img/posts/BikeBinderVR_Optimized.png
category: software
tags:
  - C#
  - software
author: damien
---

This was a little silly experimentation to exercise some more and making a home bike trainer funnier to use.

This software was made using .Net Windows Forms, Vigem, Oculus and OpenVR SDKs.
It checks the movements inputs of VR controllers from their respective SDKs and processes these inputs before sending them to a simulated XBOX controller through Vigem.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BikeBinderVR1.mp4" type="video/mp4" preload="auto"></video>
</div>

The left controller is attached to the left foot, the gyroscope datas is used to check for peddling movements. Depending on the intensity, it'll simulate pushing the Right Trigger more or less so the ingame speed is related to your peddling intensity.

The right controller is attached to the handle bar and tracks it's orientation. These datas are then processed and used to simulate the left joystick axis ingame.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BikeBinderVR2.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>The calibration process illustrated by a quickly home made stickman animation.</p>
</div>

