---
layout: academic
permalink: /
title: Taeyun Ha
redirect_from:
  - /about/
  - /about.html
---

<section class="intro" id="home" aria-label="About Taeyun Ha">
  <img class="portrait" src="{{ '/images/profile.jpg' | relative_url }}" alt="Taeyun Ha" width="230" height="230">
  <div class="intro-copy">
    <h1>Taeyun Ha</h1>
    <p>I am a first-year PhD student at <a href="https://en.snu.ac.kr/">Seoul National University</a>, advised by <a href="https://jhugestar.github.io/">Prof. Hanbyul Joo</a>. My research focuses on robotics and 3D computer vision.</p>
    <p>I received my B.S. in Electrical and Computer Engineering, <em>summa cum laude</em>, from Seoul National University.</p>
    <div class="contact-links" aria-label="Profile links">
      <a href="https://scholar.google.com/citations?user=jfMqD9wAAAAJ&hl=en">Google Scholar</a><span class="sep">/</span>
      <a href="https://github.com/hahahataeyun">GitHub</a><span class="sep">/</span>
      <a href="https://www.linkedin.com/in/taeyunha/">LinkedIn</a><span class="sep">/</span>
      <a href="{{ '/files/CV_TAEYUN%20HA.pdf' | relative_url }}">CV</a><span class="sep">/</span>
      <a href="mailto:taeyun012@gmail.com">taeyun012@gmail.com</a>
    </div>
  </div>
</section>

<section class="section-block" id="research">
  <div class="section-head"><h2>Research</h2></div>
  <ul class="research-list">
    <li>I work on human-to-robot learning and dexterous manipulation, with an interest in making robot skills generalize beyond a single hand or environment.</li>
    <li><span class="research-label">Current interests</span>
      <ul>
        <li><strong>Scaling human-to-robot learning:</strong> using human demonstrations and data to teach robot hands.</li>
        <li><strong>Dexterous manipulation:</strong> learning robust grasping and interaction with diverse objects.</li>
        <li><strong>Real-to-sim-to-real:</strong> connecting real-world data and simulation
      </ul>
    </li>
  </ul>
</section>

<section class="section-block" id="publications">
  <div class="section-head"><h2>Publications</h2></div>
  {% include publication-list.html %}
</section>

<section class="section-block" id="projects">
  <div class="section-head"><h2>Projects</h2></div>
  {% include project-list.html %}
</section>
