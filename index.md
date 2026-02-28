---
layout: default
title: About
permalink: /
---

<div class="about">

  <!-- ── Photo & Social ─────────────────────────────────────────────── -->
  <div class="about__photo-col">
    <img class="about__photo"
         src="{{ site.author.photo }}"
         alt="Portrait of {{ site.author.name }}"
         loading="eager">

    <div class="about__social">
      <a class="about__social-link"
         href="https://github.com/{{ site.author.github }}"
         target="_blank" rel="noopener noreferrer">
        <i class="fab fa-github" aria-hidden="true"></i>
        <span>GitHub</span>
      </a>
      <a class="about__social-link"
         href="{{ site.author.linkedin }}"
         target="_blank" rel="noopener noreferrer">
        <i class="fab fa-linkedin" aria-hidden="true"></i>
        <span>LinkedIn</span>
      </a>
      <a class="about__social-link"
         href="{{ site.author.university_profile }}"
         target="_blank" rel="noopener noreferrer">
        <i class="fas fa-university" aria-hidden="true"></i>
        <span>University Profile</span>
      </a>
    </div>
  </div>

  <!-- ── Bio & Content ──────────────────────────────────────────────── -->
  <div class="about__content">
    <h1>{{ site.author.name }}</h1>
    <p class="subtitle">
      Ph.D. Candidate in Generative AI &amp; Mathematics<br>
      Maastricht University
    </p>

<p>
  I am a Ph.D. candidate at Maastricht University (since February 2025), working on
  convergent algorithms and principled evaluation for generative models.
</p>

<p>
  I hold a B.Sc. in Mathematics from the University of Ioannina (2021) and
  a M.Sc. in Data Science for Decision Making from Maastricht University (2024).
  During my studies, I worked as a Teaching Assistant and later as a Junior Lecturer in
  mathematics and programming courses.
</p>

    <h3>Research Interests</h3>
    <ul class="interests-list">
      <li>Generative AI optimization and evaluation</li>
      <li>Equilibrium computation</li>
      <li>Algorithmic convergence</li>
      <li>Decision-making under uncertainty</li>
      <li>Applications in AI and large-scale optimization</li>
    </ul>

    <h3>Affiliation</h3>
    <p>
      {{ site.author.department }}<br>
      Faculty of Science and Engineering<br>
      <a href="https://www.maastrichtuniversity.nl" target="_blank" rel="noopener noreferrer">Maastricht University</a>
    </p>

    <h3>Supervisors</h3>
    <p>
      Dr. Barbara Franci &middot;
      Dr. Monica Salvioli &middot;
      Prof. Dr. M.H.M. Winands
    </p>
  </div>

</div>
