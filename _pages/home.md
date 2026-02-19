---
permalink: /
title: "Ross Jenkinson"
layout: single
classes: page--home
author_profile: false
---

{% include base_path %}

<section class="hero hero--with-bg">
  <div class="hero__bg-image" style="background-image: url('{{ base_path }}/images/photo1.jpg');"></div>
  <div class="hero__overlay"></div>
  <div class="hero__content">
    <div class="hero__text">
      <p class="hero__eyebrow">Theoretical physicist · Postdoctoral researcher</p>
      <h1 class="hero__title">Quantum information, field theory, and the future of quantum technologies.</h1>
      <p class="hero__subtitle">
        I study quantum information theory and quantum field theory, exploring how fundamental physics connects to quantum computing. 
        My research spans qubit simulations of quantum field theory, causality in QFT, and quantum information in curved spacetime – 
        bridging theoretical foundations with practical quantum technologies.
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
          <span>Academic Email</span>
        </a>
        <a class="btn-pill" href="mailto:rjenkinson@outlook.com">
          <i class="fa-solid fa-envelope"></i>
          <span>Personal Email</span>
        </a>
        {% if site.author.inspire-hep %}
        <a class="btn-pill" href="{{ site.author.inspire-hep }}" target="_blank" rel="noopener">
          <i class="ai ai-inspire"></i>
          <span>InspireHEP</span>
        </a>
        {% endif %}
        {% if site.author.orcid %}
        <a class="btn-pill" href="{{ site.author.orcid }}" target="_blank" rel="noopener">
          <i class="ai ai-orcid"></i>
          <span>ORCID</span>
        </a>
        {% endif %}
        {% if site.author.github %}
        <a class="btn-pill" href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener">
          <i class="fa-brands fa-github"></i>
          <span>GitHub</span>
        </a>
        {% endif %}
        {% if site.author.linkedin %}
        <a class="btn-pill" href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank" rel="noopener">
          <i class="fa-brands fa-linkedin"></i>
          <span>LinkedIn</span>
        </a>
        {% endif %}
        {% if site.author.twitter %}
        <a class="btn-pill" href="https://x.com/{{ site.author.twitter }}" target="_blank" rel="noopener">
          <i class="fa-brands fa-x-twitter"></i>
          <span>X</span>
        </a>
        {% endif %}
        {% if site.author.instagram %}
        <a class="btn-pill" href="https://instagram.com/{{ site.author.instagram }}" target="_blank" rel="noopener">
          <i class="fa-brands fa-instagram"></i>
          <span>Instagram</span>
        </a>
        {% endif %}
      </div>
    </div>

    <div class="hero__photo">
      <img src="{{ base_path }}/images/photo1.jpg" alt="Photo of Ross Jenkinson" loading="eager">
    </div>
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
    <h2>CV</h2>
    <p>
      A concise overview of my academic path, teaching, and service, plus a downloadable PDF for
      applications and reference.
    </p>
    <a class="section-link" href="{{ base_path }}/cv/">Open CV</a>
  </article>
</section>

