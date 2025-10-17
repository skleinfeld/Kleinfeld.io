---
layout: default
title: Home
permalink: /
---

<section class="home-hero">
  <div class="home-hero__inner">

    <!-- Glowing ring headshot -->
    <div class="home-headshot-wrapper">
      <div class="home-headshot-ring"></div>
      <img class="home-headshot" src="{{ '/SBK-Headshot.jpeg' | relative_url }}" alt="Saul B. Kleinfeld headshot">
    </div>

    <!-- Name -->
    <h1 class="home-title">Saul B. Kleinfeld</h1>

    <!-- Subtitle -->
    <p class="home-subtitle">
      Product Leader | Aspiring Sports Leader | Data-Driven Strategist
    </p>

    <!-- Welcome Blurb -->
    <p class="home-blurb">
      Welcome to my digital home. Here you can explore my journey as a product leader, baseball executive,
      and student of the game. Feel free to learn more about my work, projects, and experiences —
      or get in touch directly.
    </p>

    <div class="home-divider" aria-hidden="true"></div>

    <!-- Three feature cards -->
    <div class="home-grid">
      <article class="home-card">
        <h3 class="home-card__title">Product Leadership</h3>
        <p class="home-card__body">
          12+ years building SaaS platforms that scale revenue and improve user engagement across
          healthcare, retail, and sports technology.
        </p>
        <a class="home-btn" href="{{ '/resume/' | relative_url }}">View Resume</a>
      </article>

      <article class="home-card">
        <h3 class="home-card__title">Baseball Operations</h3>
        <p class="home-card__body">
          Vice President of Rookie Division at NTABL, managing team operations, player development,
          and digital transformation initiatives.
        </p>
        <a class="home-btn" href="{{ '/baseball/' | relative_url }}">See Stats</a>
      </article>

      <article class="home-card">
        <h3 class="home-card__title">Sports Administration</h3>
        <p class="home-card__body">
          Master’s student at Northwestern University specializing in Sports Administration with dual
          concentrations in Analytics and NCAA Management.
        </p>
        <a class="home-btn" href="{{ '/northwestern/' | relative_url }}">View Coursework</a>
      </article>
    </div>

    <!-- CTA band -->
    <div class="home-cta">
      <h2 class="home-cta__title">Ready to connect?</h2>
      <a class="home-cta__btn" href="{{ '/contact/' | relative_url }}">Let’s Connect</a>
    </div>

  </div>
</section>