---
permalink: /
title: "Jinhee Lee"
hide_title: true
redirect_from:
  - /about/
  - /about.html
---

<section class="intro">
  <img class="intro__portrait" src="{{ '/images/profile1.png' | relative_url }}" alt="Jinhee Lee" fetchpriority="high">

  <div class="intro__body">
    <h1 class="intro__name">Jinhee Lee</h1>

    <p class="intro__lead">
      I am seeking a Ph.D. opportunity to pursue research in computer vision, robotics,
      and AI for healthcare.
    </p>

    <p>
      I'm currently a CV &amp; AI Engineer at iQ Surgical, developing surgical vision pipelines
      (3D reconstruction and multi-view correspondence) to support neurosurgeons. I'm also a
      research collaborator with SIMILab at Stanford Neurosurgery and the AI lab at Bongseng
      Memorial Hospital. I did my M.S. in Computer Science and Engineering at Ohio State
      University, and my M.Eng. and B.S. in Aerospace Engineering at UST&ndash;KARI and
      Inha University.
    </p>

    <ul class="intro__links">
      <li><a href="mailto:jinny6876@gmail.com">Email</a></li>
      <li><a href="{{ '/files/JinheeLee_CV.pdf' | relative_url }}">CV</a></li>
      <li><a href="https://scholar.google.com/citations?user=nVyn5OsAAAAJ">Scholar</a></li>
    </ul>
  </div>
</section>

<h2 class="section-label" id="research">Research</h2>

<p class="section-intro">
  I'm interested in computer vision, surgical AI, biomedical image analysis, and
  vision-language models. I've conducted research on segmentation, depth estimation, image
  generation, and vision-language models, with a primary focus on supporting surgeons in
  understanding and interpreting surgical scenes.
</p>

{% include work-list.html kinds="research" %}

<h2 class="section-label" id="projects">Projects</h2>

<p class="section-intro">
  Projects I've worked on at my job, at school, and on my own.
</p>

{% include work-list.html kinds="project,capstone" %}
