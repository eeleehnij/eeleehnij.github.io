---
permalink: /
title: "Jinhee Lee"
layout: home
redirect_from:
  - /about/
  - /about.html
---

<section id="about" class="block">
  <h2 class="block__title">About Me</h2>

  <p class="lead">
    I am seeking a Ph.D. opportunity to pursue research in computer vision, robotics,
    and AI for healthcare.
  </p>

  <p>
    I'm currently a CV &amp; AI Engineer at <strong>iQ Surgical</strong>, developing surgical
    vision pipelines (3D reconstruction and multi-view correspondence) to support
    neurosurgeons. I'm also a research collaborator with SIMILab at Stanford Neurosurgery and
    the AI lab at Bongseng Memorial Hospital. I did my M.S. in Computer Science and
    Engineering at Ohio State University, and my M.Eng. and B.S. in Aerospace Engineering at
    UST&ndash;KARI and Inha University.
  </p>
</section>

<section id="research" class="block">
  <h2 class="block__title">Research</h2>

  <p class="block__intro">
    I'm interested in computer vision, surgical AI, biomedical image analysis, and
    vision-language models. I've conducted research on segmentation, depth estimation, image
    generation, and vision-language models, with a primary focus on supporting surgeons in
    understanding and interpreting surgical scenes.
  </p>

  {% include work-list.html kinds="research" %}
</section>

<section id="projects" class="block">
  <h2 class="block__title">Projects</h2>

  <p class="block__intro">
    Projects I've worked on at my job, at school, and on my own.
  </p>

  {% include work-list.html kinds="project,capstone" style="list" %}
</section>
