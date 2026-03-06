---
permalink: /
layout: single
classes: page--home
author_profile: false
---

{% include base_path %}

<section class="hero hero--with-bg">
  <div class="hero__bg-image" style="background-image: url('{{ base_path }}/images/portrait-building.jpg');"></div>
  <div class="hero__overlay"></div>
  <div class="hero__content">
    <div class="hero__text">
      <p class="hero__eyebrow">Theoretical physicist // Postdoctoral researcher</p>
      <h1 class="hero__title">Quantum fields, black holes, and the future of computing.</h1>
      <p class="hero__subtitle">
        I'm a postdoc at the University of Manchester working on the connections between quantum field theory and quantum computing. My research covers causal approaches to particle scattering, quantum properties of black holes, and the potential for AI to change how we do theoretical physics.
      </p>

      <div class="hero__actions">
        <a class="btn btn--primary" href="{{ base_path }}/publications/">Publications</a>
        <a class="btn btn--inverse" href="{{ base_path }}/cv/">Curriculum Vitae</a>
      </div>

      <p class="hero__meta">
        Postdoctoral Researcher, University of Manchester
      </p>

      <div class="hero-social">
        <a class="btn-pill" href="mailto:ross.jenkinson@manchester.ac.uk">
          <i class="fa-solid fa-envelope"></i>
          <span>Email</span>
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
      <img src="{{ base_path }}/images/speaking-stage.jpg" alt="Ross Jenkinson speaking at a conference in the Middle East" loading="eager">
    </div>
  </div>
</section>

<section class="section-cards animate-on-scroll">
  <article class="section-card">
    <h2>About</h2>
    <p>
      My path through quantum physics, from Oxford to Manchester, and the people and ideas that shape my research.
    </p>
    <a class="section-link" href="{{ base_path }}/about/">Read more</a>
  </article>

  <article class="section-card">
    <h2>Publications</h2>
    <p>
      Papers on causal quantum field theory, the Unruh effect, and particle scattering, with links to arXiv and journals.
    </p>
    <a class="section-link" href="{{ base_path }}/publications/">Browse</a>
  </article>

  <article class="section-card">
    <h2>CV</h2>
    <p>
      Education, research experience, talks, teaching, awards, and a downloadable PDF.
    </p>
    <a class="section-link" href="{{ base_path }}/cv/">View CV</a>
  </article>
</section>

<section class="photo-gallery animate-on-scroll" style="margin-top: 3rem;">
  <div class="photo-gallery__item photo-gallery__item--wide">
    <img class="photo-gallery__img" src="{{ base_path }}/images/with-brian-lounge.jpg" alt="Ross Jenkinson with Prof. Brian Cox" loading="lazy" style="height: 320px;">
    <div class="photo-gallery__caption">With Prof. Brian Cox at the University of Manchester</div>
  </div>
  <div class="photo-gallery__item">
    <img class="photo-gallery__img" src="{{ base_path }}/images/portrait-lab.jpg" alt="Ross Jenkinson in the physics lab" loading="lazy">
    <div class="photo-gallery__caption">In the teaching labs</div>
  </div>
  <div class="photo-gallery__item">
    <img class="photo-gallery__img" src="{{ base_path }}/images/speaking-fireside.jpg" alt="Ross Jenkinson at a fireside chat in the Middle East" loading="lazy">
    <div class="photo-gallery__caption">Fireside chat at a campaign launch in the UAE</div>
  </div>
</section>
