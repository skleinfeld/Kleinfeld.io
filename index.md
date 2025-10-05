---
layout: default
title: Home
permalink: /
---

<!-- HERO -->
<section class="relative overflow-hidden">
  <!-- soft dark gradient -->
  <div class="pointer-events-none absolute inset-0 -z-10">
    <div class="absolute -top-44 left-1/2 -translate-x-1/2 h-[520px] w-[1200px] rounded-full blur-3xl"
         style="background:radial-gradient(ellipse at center, rgba(10,132,255,.18), rgba(191,90,242,.12) 45%, transparent 65%)"></div>
  </div>

  <div class="wrap mx-auto px-4 sm:px-6 pt-10 sm:pt-14 pb-8">
    <div class="grid grid-cols-1 sm:grid-cols-[120px,1fr] gap-6 items-center">
      <!-- Headshot with subtle accent ring -->
      <div class="flex sm:block justify-center">
        <div class="relative h-28 w-28 sm:h-32 sm:w-32 rounded-full p-[2px]"
             style="background:conic-gradient(from 180deg, #0A84FF, #BF5AF2, #0A84FF)">
          <img src="{{ '/SBK-Headshot.jpeg' | relative_url }}" alt="Headshot of Saul B. Kleinfeld"
               class="h-full w-full rounded-full object-cover ring-1 ring-d-line shadow-card bg-d-card">
        </div>
      </div>

      <div>
        <h1 class="text-4xl sm:text-5xl font-semibold tracking-tight">Saul B. Kleinfeld</h1>
        <p class="mt-2 text-lg text-d-sub">Systems Builder & Playbook Architect — Product × Sports</p>

        <!-- role chips -->
        <div class="mt-4 flex flex-wrap gap-2">
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-white/10 text-d-fg">Senior PM @ RazorMetrics</span>
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-white/10 text-d-fg">VP, Rookie League (NTABL)</span>
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-white/10 text-d-fg">MSA — Northwestern</span>
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

<!-- HIGHLIGHTS (compact, no preview text) -->
<section class="wrap mx-auto px-4 sm:px-6 py-8">
  <h2 class="text-2xl font-semibold">Highlights</h2>

  <div class="mt-6 grid sm:grid-cols-2 gap-6">
    <!-- NTABL -->
    <a href="{{ '/sports/' | relative_url }}"
       class="group block rounded-2xl bg-d-card border border-d-line p-5 shadow-card hover:bg-white/5 transition-colors">
      <div class="flex items-center gap-4">
        <img src="{{ '/ntabl-logo.png' | relative_url }}" alt="NTABL" class="h-10 w-10 rounded-md bg-white/90 object-contain p-1">
        <div>
          <h3 class="font-medium">League Growth & Media (NTABL)</h3>
          <p class="text-[13px] text-d-sub mt-1">View work</p>
        </div>
      </div>
    </a>

    <!-- Northwestern -->
    <a href="{{ '/sports/' | relative_url }}"
       class="group block rounded-2xl bg-d-card border border-d-line p-5 shadow-card hover:bg-white/5 transition-colors">
      <div class="flex items-center gap-4">
        <img src="{{ '/northwestern-seal.png' | relative_url }}" alt="Northwestern University"
             class="h-10 w-10 rounded-md bg-white/90 object-contain p-1">
        <div>
          <h3 class="font-medium">Northwestern University MSA Coursework</h3>
          <p class="text-[13px] text-d-sub mt-1">View projects</p>
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
       href="https://calendly.com/saul-dallasmsbl/30min" target="_blank" rel="noopener">Book time</a>
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="https://www.linkedin.com/in/saul-kleinfeld" target="_blank" rel="noopener">LinkedIn</a>
    <a class="inline-flex items-center rounded-full border border-d-line px-4 py-2 hover:bg-white/5"
       href="{{ '/Sports_PdM _Saul_Kleinfeld_Resume.pdf' | relative_url | uri_escape }}" target="_blank" rel="noopener">Download résumé</a>
  </div>
</section>