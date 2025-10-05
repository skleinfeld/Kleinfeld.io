---
layout: default
title: Home
permalink: /
---

<!-- HERO -->
<section class="relative overflow-hidden">
  <!-- soft dark gradient -->
  <div class="pointer-events-none absolute inset-0 -z-10">
    <div class="absolute -top-44 left-1/2 -translate-x-1/2 h-[560px] w-[1250px] rounded-full blur-3xl"
         style="background:radial-gradient(ellipse at center, rgba(10,132,255,.18), rgba(191,90,242,.12) 45%, transparent 65%)"></div>
  </div>

  <div class="wrap mx-auto px-4 sm:px-6 pt-10 sm:pt-14 pb-8">
    <div class="grid grid-cols-1 sm:grid-cols-[152px,1fr] gap-6 items-center">
      <!-- Larger headshot with accent ring -->
      <div class="flex sm:block justify-center">
        <div class="relative h-36 w-36 sm:h-40 sm:w-40 rounded-full p-[2.5px]"
             style="background:conic-gradient(from 180deg, #0A84FF, #BF5AF2, #0A84FF)">
          <img src="{{ '/SBK-Headshot.jpeg' | relative_url }}" alt="Headshot of Saul B. Kleinfeld"
               class="h-full w-full rounded-full object-cover ring-1 ring-d-line shadow-card bg-d-card">
        </div>
      </div>

      <div>
        <h1 class="text-4xl sm:text-5xl font-semibold tracking-tight">Saul B. Kleinfeld</h1>
        <p class="mt-2 text-lg text-d-sub">Systems Builder & Playbook Architect — Product × Sports</p>

        <!-- Welcome line -->
        <p class="mt-4 text-[15px] text-d-sub">
          Welcome — feel free to learn about my background, explore projects, and reach out anytime.
        </p>

        <!-- role chips -->
        <div class="mt-4 flex flex-wrap gap-2">
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-white/10 text-d-fg">Senior PM @ RazorMetrics</span>
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-white/10 text-d-fg">VP, Rookie League (NTABL)</span>
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-white/10 text-d-fg">MSA — Northwestern</span>
        </div>

        <div class="mt-6 flex flex-wrap gap-3">
          <a href="{{ '/biography/' | relative_url }}"
             class="inline-flex items-center rounded-full bg-white text-black px-4 py-2 text-sm hover:opacity-90">
            Read Biography
          </a>
          <a href="{{ '/contact/' | relative_url }}"
             class="inline-flex items-center rounded-full border border-d-line px-4 py-2 text-sm hover:bg-white/5">
            Get In Touch
          </a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CURRENT FOCUS -->
<section class="wrap mx-auto px-4 sm:px-6 py-8">
  <h2 class="text-2xl font-semibold">Current Focus</h2>

  <div class="mt-6 grid sm:grid-cols-2 gap-6">
    <!-- NTABL -->
    <a href="{{ '/sports/' | relative_url }}"
       class="group block rounded-2xl bg-d-card border border-d-line p-5 shadow-card hover:bg-white/5 transition-colors">
      <div class="flex items-center gap-4">
        <img src="{{ '/ntabl-logo.png' | relative_url }}" alt="NTABL"
             class="h-14 w-14 rounded-md bg-white/90 object-contain p-1.5">
        <div>
          <h3 class="font-medium">North Texas Amateur Baseball League</h3>
          <p class="text-[13px] text-d-sub mt-1">View Stats &amp; League Information</p>
        </div>
      </div>
    </a>

    <!-- Northwestern -->
    <a href="{{ '/sports/' | relative_url }}"
       class="group block rounded-2xl bg-d-card border border-d-line p-5 shadow-card hover:bg-white/5 transition-colors">
      <div class="flex items-center gap-4">
        <img src="{{ '/northwestern-seal.png' | relative_url }}" alt="Northwestern University"
             class="h-14 w-14 rounded-md bg-white/90 object-contain p-1.5">
        <div>
          <h3 class="font-medium">Northwestern University MSA Coursework</h3>
          <p class="text-[13px] text-d-sub mt-1">View Projects</p>
        </div>
      </div>
    </a>
  </div>
</section>

<!-- QUICK LINKS -->
<section class="wrap mx-auto px-4 sm:px-6 pb-12">
  <div class="rounded-2xl border border-d-line bg-d-card p-5 flex flex-wrap gap-3">
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="mailto:saul@kleinfeld.io?subject=Hello%20Saul&body=Hi%20Saul%2C%0D%0A%0D%0A">Email</a>
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="https://calendly.com/saul-dallasmsbl/30min" target="_blank" rel="noopener">Book Time</a>
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="https://www.linkedin.com/in/saul-kleinfeld" target="_blank" rel="noopener">LinkedIn</a>
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="{{ '/Sports_PdM _Saul_Kleinfeld_Resume.pdf' | relative_url | uri_escape }}" target="_blank" rel="noopener">Download Résumé</a>
  </div>
</section>