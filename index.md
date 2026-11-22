---
layout: default
title: Software Engineer
description: Riya Bisht is a software engineer at Amazon who builds thoughtful solutions to complex problems.
---

<div class="portfolio-home" id="top">
  <section class="hero section-shell" aria-labelledby="hero-title">
    <p class="eyebrow"><span class="status-dot"></span> Software engineer <span class="eyebrow-divider">/</span> Amazon · AWS</p>
    <h1 id="hero-title">I build useful things<br>for <span class="highlight">complex problems.</span></h1>
    <div class="hero-bottom">
      <p class="hero-intro">I’m Riya Bisht, a software engineer at Amazon. I work on the systems behind financial planning and infrastructure investments for data centers.</p>
      <a class="text-link" href="#work">Explore my work <span aria-hidden="true">↓</span></a>
    </div>
    <div class="hero-note" aria-hidden="true">
      <span>Curious by nature</span>
      <span>Thoughtful by design</span>
    </div>
  </section>

  <section class="work-section section-shell" id="work" aria-labelledby="work-title">
    <div class="section-heading">
      <div>
        <p class="eyebrow">A few things I’ve worked on</p>
        <h2 id="work-title">Selected work<span class="accent-period">.</span></h2>
      </div>
      <a class="text-link" href="{{ '/projects/' | relative_url }}">All projects <span aria-hidden="true">↗</span></a>
    </div>

    <div class="project-grid">
      <a class="project-card project-card-lime" href="{{ '/projects/#digit-recognition' | relative_url }}">
        <div class="project-visual digit-visual" aria-hidden="true">
          <span class="digit digit-one">2</span><span class="digit digit-two">8</span><span class="digit digit-three">5</span>
          <span class="visual-caption">01 / NEURAL NETWORK</span>
        </div>
        <div class="project-card-copy">
          <p class="project-type">Machine learning <span>01</span></p>
          <h3>Handwritten digit recognition</h3>
          <p>A CNN trained on MNIST, with a web app to try out handwritten digit predictions.</p>
          <span class="card-link">View project <span aria-hidden="true">↗</span></span>
        </div>
      </a>

      <a class="project-card project-card-peach" href="{{ '/projects/#recipe-recommender' | relative_url }}">
        <div class="project-visual recipe-visual" aria-hidden="true">
          <span class="recipe-orbit orbit-one"></span><span class="recipe-orbit orbit-two"></span>
          <span class="recipe-node node-center">R</span><span class="recipe-node node-top">+</span><span class="recipe-node node-left">+</span><span class="recipe-node node-right">+</span>
          <span class="visual-caption">02 / INGREDIENTS → IDEAS</span>
        </div>
        <div class="project-card-copy">
          <p class="project-type">Web application <span>02</span></p>
          <h3>Recipe recommender</h3>
          <p>A graph-powered way to discover dishes from the ingredients you already have.</p>
          <span class="card-link">View project <span aria-hidden="true">↗</span></span>
        </div>
      </a>
    </div>
  </section>

  <section class="about-strip section-shell" aria-labelledby="about-title">
    <p class="eyebrow">A little about me</p>
    <div class="about-strip-content">
      <h2 id="about-title">Good software starts with understanding the problem.</h2>
      <div>
        <p>From data-center infrastructure planning to early machine-learning projects, I enjoy bringing structure to complicated challenges and making the result useful for people.</p>
        <a class="text-link" href="{{ '/about/' | relative_url }}">More about me <span aria-hidden="true">↗</span></a>
      </div>
    </div>
  </section>

  <section class="contact-section section-shell" id="contact" aria-labelledby="contact-title">
    <p class="eyebrow">Have a good one in mind?</p>
    <div class="contact-content">
      <h2 id="contact-title">Let’s make it<br><span class="highlight">happen.</span></h2>
      <a class="contact-button" href="mailto:{{ site.author.email }}">Say hello <span aria-hidden="true">↗</span></a>
    </div>
  </section>
</div>
