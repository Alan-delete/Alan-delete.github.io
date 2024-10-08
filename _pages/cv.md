---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume

---
[pdf file here](/files/CV.pdf)
{% include base_path %}

Education
======
* M.S. in ETH Zurich, 2023 - 2025(expected)
* B.S. in The Chinese University of Hong Kong 2018 - 2023

Experience
======
* June 2024: Quest3 rendering pipeline study and UE dynamic batching implementation
  * Study the binocular rendering pipeline of the Quest 3, focusing on the difference between single-pass stereo pipeline and single-pass multiview pipeline.
  * Code the Dynamic Batching function as a plugin to the UE engine. RenderDoc and Snapdragon Profiler were used to test the Dynamic Batching on the Samsung 10e. The results show that the Dynamic Batching can significantly reduce draw call overhead.
  * Octree is applied to more reasonably batch objects with the same material, thereby improving the efficiency of frustum culling.*

* Mar 2022:  LVS-Net: Line Voting with Segmentation for Visual Localization
  * Supervised by teaching assistent R´emi Pautrat in ETH, I worked with other three team members to
    estimate camera pose from 2D-3D correspondences that are gained from extended VS-Net.
  * The project involves the preprocessing of data and network training. In contrast to the traditional
    network-based visual localization which utilizes point 2D-3D correspondence, our model outputs line
    correspondence to provide more spatial information for RANSAC-Pnp algorithm.

* Sep 2021:  3D Human Pose Reconstruction from Monocular Image
  * In the final year thesis on 3D human pose reconstruction, we refer to a model called I2L-MeshNet and
    try to improve it with other new network blocks. Human3.6M was used as our training dataset.
  * The graph convolutional network is adapted to substitute the original convolutional layers to exploit
    human skeleton structure information. Besides, we utilized other training strategies such as weakly
    supervised learning

Skills
======

* Artificial Intelligence
  * Pytorch Framework
  * Computer Vision (Deep Learning Based Knowledge, SfM)
  * Probabilistic AI (Gaussian Process, Reinforcement Learning)
* Computer Graphics
  * Path/Light Tracing Rendering, Photon Mapping
  * Participating Media Simulation
  * Unreal Engine
* Web Application
  * Javascript
  * React

<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
   -->  
   
<!-- Service and leadership
======
* Mainland O'camp for CUHK freshman for   -->
