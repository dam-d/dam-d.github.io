---
date: 2023-05-12 12:00:00
layout: post
title: Blender animation slicer tool
subtitle: A python script allowing to detect differences between frames and split animations accordingly.
description: A python script allowing to detect differences between frames and split animations accordingly.
image: /assets/img/posts/AnimationSplitter.png
optimized_image: /assets/img/posts/AnimationSplitter_Optimized.png
category: blender
tags:
  - blender
  - python
author: damien
---

This tool was born out of a necessity to sort out the animation files extracted from the ps1 version of the game metal gear solid and separate each animations into their own blender action.

This is a Python implementation of the RMSE formula that allows to measure the differences between two values by giving a score depending on their difference.
Here, we check each bone rotations on each frames of the animations. If the rotation difference between each frames is more than the threshold we gave it, that probably means that the frame belongs to another animation.
If that's the case, the script will automatically cut the animation and create it's own blender action with it.

This tool isn't perfect and will require human supervision to check the cuts but it allows to automatize a huge chunk of the work.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/AnimationSlicer.mp4" type="video/mp4" preload="auto"></video>
</div>

