---
date: 2023-05-12 12:00:00
layout: post
title: Blender - Decoupeur d'animation
subtitle: Un script Python permettant de decouper automatiquement un fichier d'animation en de multiple animation action dans Blender.
description: Un script Python permettant de decouper automatiquement un fichier d'animation en de multiple animation action dans Blender.
image: /assets/img/posts/AnimationSplitter.png
optimized_image: /assets/img/posts/AnimationSplitter_Optimized.png
category: blender
tags:
  - blender
  - python
author: damien
---

Cet outil est n&eacute; de la n&eacute;cessit&eacute; de trier les fichiers d&#39;animation extraits de la version PS1 du jeu Metal Gear Solid et de s&eacute;parer chaque animation dans sa propre animation action dans Blender.

Il s&#39;agit d&#39;une impl&eacute;mentation en Python de la formule RMSE qui permet de mesurer les diff&eacute;rences entre deux valeurs en attribuant un score en fonction de leur diff&eacute;rence. Ici, nous v&eacute;rifions les rotations de chaque bone sur chaque frame des animations. Si la diff&eacute;rence de rotation entre chaque frame est sup&eacute;rieure au seuil qu&#39;on d&eacute;fini, cela signifie probablement que la frame appartient &agrave; une autre animation. Dans ce cas, le script coupera automatiquement l&#39;animation et cr&eacute;era sa propre action.

Cet outil n&#39;est pas parfait et n&eacute;cessite une supervision humaine pour v&eacute;rifier les d&eacute;coupes, mais il permet d&#39;automatiser une grande partie du travail.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/AnimationSlicer.mp4" type="video/mp4" preload="auto"></video>
</div>

