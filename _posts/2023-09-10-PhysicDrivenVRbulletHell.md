---
date: 2023-09-10 12:26:40
layout: post
title: Unity DOTS - Simulation physique VR
subtitle: Une quantit&#233; massive d'objets physique simul&#233; en temps r&#233;el avec Unity DOTS.
description: A massive number of physic driven entities powered by Unity DOTS.
image: /assets/img/posts/BulletHellVR.png
optimized_image: /assets/img/posts/BulletHellVR_Optimized.png
category: unity
tags:
  - unityDOTS
author: damien
---

Ce projet a &#233;t&#233; initi&#233; dans le but principal d'<strong>am&#233;liorer ma capacit&#233; &#224; d&#233;velopper du code &#233;volutifs</strong>. Mon exp&#233;rience est principalement ancr&#233;e dans la programmation orient&#233;e objet traditionnelle sous .NET et Unity, et m'aventurer sur du d&#233;veloppement orient&#233; data repr&#233;sentait donc un certain challenge. La d&#233;couverte du framework ECS DOTS d'Unity a offert une pr&#233;cieuse opportunit&#233; de m'immerger dans cette architecture.

Cela faisait un moment que je suivais avec envie l'&#233;volution de Unity DOTS, reconnu pour sa capacit&#233; &#224; g&#233;rer un grand nombre d'entit&#233;s. Ce projet m'a non seulement facilit&#233; l'apprentissage de l'architecture ECS, mais m'a &#233;galement permis de cr&#233;er des simulations visuellement impressionantes pour une &#233;x&#233;cution en temps r&#233;el : <strong>une combinaison plaisante d'esth&#233;tique et comp&#233;tences techniques.</strong>

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/BulletHell1.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>20 000 entit&#233;s physiques conduites par un syst&#232;me de mouvement profitant du multithread, burst compile et job system.</p>
</div>

Cela &eacute;tait &eacute;galement l&#39;occasion de m&#39;immerger dans la technologie <strong>VFX Graph</strong>, le but &eacute;tant de transferer la charge des effets visuel du CPU vers le GPU. &Eacute;tant donn&eacute; la nature tr&egrave;s gourmande en CPU des simulations physiques, ce changement m&#39;a permis <strong>d&#39;augmenter encore davantage le nombre d&#39;entit&eacute;s.</strong>

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BulletHellGamepad.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>Jouable &eacute;galement sur &eacute;cran standard avec une manette ou clavier souris</p>
</div>

Un travail consid&eacute;rable a &eacute;galement &eacute;t&eacute; r&eacute;alis&eacute; sur d&#39;autres optimisations afin de maintenir la fr&eacute;quence de 90 fps en r&eacute;alit&eacute; virtuelle.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BulletHell2.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>Gameplay VR d'une version sans post processing.</p>
</div>

En outre, cela m&#39;a &eacute;galement permis <strong>de renforcer et d&#39;am&eacute;liorer mes comp&eacute;tences existantes</strong> dans divers domaines, notamment les interactions VR, game et level design, mod&eacute;lisation, texturing, vfxs, la gestion audio, l&#39;&eacute;clairage et le post-processing.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BulletHell3.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>Target Locked</p>
</div>