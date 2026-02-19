---
permalink: /
title: "Ross Jenkinson"
layout: single
classes: page--home
author_profile: false
---

{% include base_path %}

<section class="hero">
  <div class="hero__text">
    <p class="hero__eyebrow">Theoretical physicist · Postdoctoral researcher</p>
    <h1 class="hero__title">Quantum fields, black holes, and the information they keep.</h1>
    <p class="hero__subtitle">
      I study how quantum information behaves in extreme space‑time settings – from curved backgrounds and
      the Unruh effect to black holes and Hawking radiation – with an eye on what we can simulate on real‑world qubit devices.
    </p>

    <div class="hero__actions">
      <a class="btn btn--primary" href="{{ base_path }}/publications/">View publications</a>
      <a class="btn btn--inverse" href="{{ base_path }}/cv/">Download CV</a>
    </div>

    <p class="hero__meta">
      Postdoctoral Researcher · University of Manchester
    </p>

    <div class="hero-social">
      <a class="btn-pill" href="mailto:ross.jenkinson@manchester.ac.uk">
        <i class="fa-solid fa-envelope"></i>
        <span>Email</span>
      </a>
      {% if site.author.googlescholar %}
      <a class="btn-pill" href="{{ site.author.googlescholar }}">
        <i class="ai ai-google-scholar"></i>
        <span>Google Scholar</span>
      </a>
      {% endif %}
      <a class="btn-pill" href="https://github.com/your-github-handle" target="_blank" rel="noopener">
        <i class="fa-brands fa-github"></i>
        <span>GitHub</span>
      </a>
      <a class="btn-pill" href="https://linkedin.com/in/your-linkedin-handle" target="_blank" rel="noopener">
        <i class="fa-brands fa-linkedin"></i>
        <span>LinkedIn</span>
      </a>
    </div>
  </div>

  <div class="hero__photo">
    <img src="{{ base_path }}/images/bio-photo.jpg" alt="Photo of Ross Jenkinson" loading="lazy">
  </div>
</section>

<section class="section-cards">
  <article class="section-card">
    <h2>About me</h2>
    <p>
      A short overview of my background, current position, and broader research story – from quantum
      field theory to quantum technologies.
    </p>
    <a class="section-link" href="{{ base_path }}/about/">Read more</a>
  </article>

  <article class="section-card">
    <h2>Publications</h2>
    <p>
      Peer‑reviewed work spanning quantum field theory, curved space‑time, and quantum information, with
      links to arXiv and journal versions where available.
    </p>
    <a class="section-link" href="{{ base_path }}/publications/">Browse publications</a>
  </article>

  <article class="section-card">
    <h2>Talks</h2>
    <p>
      Slides and abstracts from invited talks, seminars, and conference presentations on quantum
      information in relativistic settings.
    </p>
    <a class="section-link" href="{{ base_path }}/talks/">See recent talks</a>
  </article>

  <article class="section-card">
    <h2>CV</h2>
    <p>
      A concise overview of my academic path, teaching, and service, plus a downloadable PDF for
      applications and reference.
    </p>
    <a class="section-link" href="{{ base_path }}/cv/">Open CV</a>
  </article>
</section>

