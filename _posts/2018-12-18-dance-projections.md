---
layout: post
title: "Dance concert video projections"
author: Dr. Kessner
date: '2018-12-18'
image: /assets/img/2018-12-18-dance-concert-poster-small.jpg
introduction:  Computer science and the performing arts come together at this year's
               All School Dance Concert.
tags: ["STEM+", "Coding"]
---

{% include base.html %}

This year's All School Dance Concert (December 6-7, 2018), _Haiku_, directed by
Ms.  Holly Rothschild, featured interactive animations created by students in
Honors Computer Science Projects, taught by Dr. Darren Kessner. 

Catherine '20 and Kyra '19 wrote an animation based on a physics simulation for
the piece _let me stay gentle_, choreographed and performed by Micah '21 and
Cordelia '21.  Catherine and Kyra used virtual models of springs to create a
string that ripples and breaks apart.

For a piece called _Overwhelmed_, choreographed by Ms. Rothschild, Catherine
'20 created an interactive particle system using a blend of math, physics, and
computer science.  Below is a web version of the program, which was projected
on stage behind the dancers.  Catherine used a Microsoft Kinect sensor to get
depth information from the dancers on stage, which allowed the dancers to
interact with the particle system.

Congratulations to our students on an impressive display of art and science!


<center>
<script src="../danceprojection_web/processing.min.js"></script>
<canvas data-processing-sources="../danceprojection_web/danceprojection_web.pde ../danceprojection_web/Particle.pde"></canvas>
</center>

<img src="{{ base }}/assets/img/2018-12-18-dance-concert-poster.jpg" width="65%"/>
