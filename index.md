---
layout: default
title: Home
permalink: /
---

<!-- HERO (dark with soft color blobs) -->
<section class="relative overflow-hidden">
  <!-- background blobs -->
  <div class="pointer-events-none absolute inset-0 -z-10">
    <div class="absolute -top-40 left-1/2 -translate-x-1/2 h-[580px] w-[1200px] rounded-full blur-3xl"
         style="background:radial-gradient(ellipse at center, rgba(10,132,255,.18), rgba(191,90,242,.12) 45%, transparent 65%)"></div>
  </div>

  <div class="wrap mx-auto px-4 sm:px-6 pt-10 sm:pt-14 pb-10">
    <div class="grid grid-cols-1 sm:grid-cols-[120px,1fr] gap-6 items-center">
      <!-- Headshot with conic accent ring -->
      <div class="flex sm:block justify-center">
        <div class="relative h-28 w-28 sm:h-32 sm:w-32 rounded-full p-[2px]"
             style="background:conic-gradient(from 180deg, #0A84FF, #BF5AF2, #FF375F, #FF9F0A, #FFD60A, #30D158, #0A84FF)">
          <img src="{{ '/SBK-Headshot.jpeg' | relative_url }}" alt="Headshot of Saul B. Kleinfeld"
               class="h-full w-full rounded-full object-cover ring-1 ring-d-line shadow-card bg-d-card">
        </div>
      </div>

      <div>
        <h1 class="text-4xl sm:text-5xl font-semibold tracking-tight">Saul B. Kleinfeld</h1>
        <p class="mt-2 text-lg text-d-sub">Systems Builder & Playbook Architect — Product × Sports</p>

        <!-- colorful role chips -->
        <div class="mt-4 flex flex-wrap gap-2">
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-a-blue/15 text-a-blue">Senior PM @ RazorMetrics</span>
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-a-purple/15 text-a-purple">VP, Rookie League (NTABL)</span>
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-a-pink/15 text-a-pink">MSA — Northwestern</span>
        </div>

        <div class="mt-6 flex flex-wrap gap-3">
          <a href="{{ '/biography/' | relative_url }}"
             class="inline-flex items-center rounded-full bg-white text-black px-4 py-2 text-sm hover:opacity-90">
            Read biography
          </a>
          <a href="{{ '/contact/' | relative_url }}"
             class="inline-flex items-center rounded-full border border-d-line px-4 py-2 text-sm hover:bg-white/5">
            Get in touch
          </a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- “COLOR SPECS” STRIP (Apple infographic vibe) -->
<section class="wrap mx-auto px-4 sm:px-6">
  <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
    <div class="rounded-xl bg-a-blue/15 p-3 text-center">
      <div class="text-[12px] text-d-sub">Experience</div>
      <div class="text-xl font-semibold">15+ yrs</div>
    </div>
    <div class="rounded-xl bg-a-purple/15 p-3 text-center">
      <div class="text-[12px] text-d-sub">Leadership</div>
      <div class="text-xl font-semibold">VP, NTABL</div>
    </div>
    <div class="rounded-xl bg-a-green/15 p-3 text-center">
      <div class="text-[12px] text-d-sub">Treks</div>
      <div class="text-xl font-semibold">25+</div>
    </div>
    <div class="rounded-xl bg-a-yellow/15 p-3 text-center">
      <div class="text-[12px] text-d-sub">Focus</div>
      <div class="text-xl font-semibold">Product Ops</div>
    </div>
    <div class="rounded-xl bg-a-orange/15 p-3 text-center">
      <div class="text-[12px] text-d-sub">Leagues</div>
      <div class="text-xl font-semibold">Expos / Bulls</div>
    </div>
    <div class="rounded-xl bg-a-pink/15 p-3 text-center">
      <div class="text-[12px] text-d-sub">Program</div>
      <div class="text-xl font-semibold">Northwestern</div>
    </div>
  </div>
</section>

<!-- HIGHLIGHTS (two cards — Config Tool removed) -->
<section class="wrap mx-auto px-4 sm:px-6 py-10">
  <h2 class="text-2xl font-semibold">Highlights</h2>

  <div class="mt-6 grid sm:grid-cols-2 gap-6">
    <!-- Highlight 1 -->
    <article class="rounded-2xl bg-d-card shadow-card border border-d-line p-5">
      <div class="flex items-center gap-2">
        <span class="h-2.5 w-2.5 rounded-full bg-a-purple"></span>
        <h3 class="font-medium">League Growth & Media (NTABL)</h3>
      </div>
      <p class="mt-2 text-[15px] text-d-fg/90">
        Expanded the Rookie League, launched livestream “Game of the Week,” and built sponsor inventory playbooks.
      </p>
      <a href="{{ '/sports/' | relative_url }}" class="mt-3 inline-block text-[15px] alink">Explore sports</a>
    </article>

    <!-- Highlight 2 -->
    <article class="rounded-2xl bg-d-card shadow-card border border-d-line p-5">
      <div class="flex items-center gap-2">
        <span class="h-2.5 w-2.5 rounded-full bg-a-blue"></span>
        <h3 class="font-medium">Northwestern Projects</h3>
      </div>
      <p class="mt-2 text-[15px] text-d-fg/90">
        Coursework in sports analytics—dashboards and notebooks on player development and league operations.
      </p>
      <a href="{{ '/sports/' | relative_url }}" class="mt-3 inline-block text-[15px] alink">View projects</a>
    </article>
  </div>
</section>

<!-- QUICK LINKS -->
<section class="wrap mx-auto px-4 sm:px-6 pb-12">
  <div class="rounded-2xl border border-d-line bg-d-card p-5 flex flex-wrap gap-3">
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="mailto:saul@kleinfeld.io?subject=Hello%20Saul&body=Hi%20Saul%2C%0D%0A%0D%0A">Email</a>
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="https://calendly.com/saul-dallasmsbl/30min" target="_blank" rel="noopener">Book time</a>
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="https://www.linkedin.com/in/saul-kleinfeld" target="_blank" rel="noopener">LinkedIn</a>
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="{{ '/Sports_PdM _Saul_Kleinfeld_Resume.pdf' | relative_url | uri_escape }}" target="_blank" rel="noopener">Download résumé</a>
  </div>
</section>