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

    <p>
      I'm an AI engineer at the Lululab AI Research Center in Seoul, where I work on medical
      imaging and generative AI for dermatology. I'm also a research collaborator with SIMILab
      at Stanford Neurosurgery and the AI lab at Bongseng Memorial Hospital, where I work on
      surgical AI. I did my M.S. in Computer Science and Engineering at Ohio State, and my
      first M.S. and B.S. in Aerospace Engineering at UST and Inha University. I'm currently
      applying for Ph.D. positions in computer vision, robotics, and biomedical AI.
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
  I'm interested in surgical AI, biomedical image analysis, vision-language foundation models,
  and intelligent robotics. Most of my research is about recovering the surgical scene —
  anatomy, depth, and context — from intraoperative video, with the goal of making surgery
  safer and more accessible.
</p>

{% include work-list.html kinds="research" %}

<h2 class="section-label" id="projects">Projects</h2>

<p class="section-intro">
  Work that didn't end up as a paper — things I built in industry, for coursework,
  and on my own.
</p>

{% include work-list.html kinds="project,capstone" %}
