---
date: 2023-04-21 12:00:00
layout: post
title: Bike Binder VR
subtitle: Un outil pour contr&ocirc;ler physiquement le jeu Riders Republic depuis un bike-trainer et un casque VR.
description: Un outil pour contr&ocirc;ler physiquement le jeu Riders Republic depuis un bike-trainer et un casque VR.
image: /assets/img/posts/BikeBinderVR.png
optimized_image: /assets/img/posts/BikeBinderVR_Optimized.png
category: software
tags:
  - C#
  - software
author: damien
---

Il s&#39;agissait d&#39;une petite exp&eacute;rimentation amusante pour m&#39;entra&icirc;ner davantage et rendre l&#39;utilisation d&#39;un home-trainer de v&eacute;lo plus divertissante.

Ce logiciel a &eacute;t&eacute; cr&eacute;&eacute; &agrave; l&#39;aide de .Net Windows Forms, Vigem, et des SDKs d&#39;Oculus et OpenVR.
Il v&eacute;rifie les input de mouvement des contr&ocirc;leurs VR &agrave; partir de leurs SDK respectifs et traite ces entr&eacute;es avant de les envoyer &agrave; une manette Xbox simul&eacute;e via Vigem.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BikeBinderVR1.mp4" type="video/mp4" preload="auto"></video>
</div>

Le contr&ocirc;leur gauche est attach&eacute; au pied gauche, les donn&eacute;es du gyroscope sont utilis&eacute;es pour v&eacute;rifier les mouvements de p&eacute;dalage. Selon l&#39;intensit&eacute;, il simule davantage ou moins l&#39;appui sur la g&acirc;chette droite, de sorte que la vitesse en jeu est li&eacute;e &agrave; l&#39;intensit&eacute; du p&eacute;dalage.

Le contr&ocirc;leur droit est fix&eacute; au guidon et suit son orientation. Ces donn&eacute;es sont ensuite trait&eacute;es et utilis&eacute;es pour simuler l&#39;axe du joystick gauche en jeu.

<div class="video-container">
    <video autoplay loop muted playsinline poster="/assets/img/loading.gif" src="/assets/img/videos/BikeBinderVR2.mp4" type="video/mp4" preload="auto"></video>
</div>
<div class="video-description">
    <p>The calibration process illustrated by a quickly home made stickman animation.</p>
</div>

