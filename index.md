---
layout: default
title: Home
permalink: /
---

<!-- HERO -->
<section class="relative">
  <!-- soft gradient background accent -->
  <div class="pointer-events-none absolute inset-0 -z-10">
    <div class="mx-auto max-w-[1100px] h-56 sm:h-64 bg-gradient-to-r from-[#4E2A84]/12 via-[#06c]/10 to-[#C6007E]/12 rounded-b-[36px]"></div>
  </div>

  <div class="wrap mx-auto px-4 sm:px-6 pt-10 sm:pt-14 pb-8">
    <div class="grid grid-cols-1 sm:grid-cols-[120px,1fr] gap-6 items-center">
      <div class="flex sm:block justify-center">
        <img src="{{ '/SBK-Headshot.jpeg' | relative_url }}" alt="Headshot of Saul B. Kleinfeld"
             class="h-28 w-28 sm:h-32 sm:w-32 rounded-full object-cover ring-1 ring-a-line shadow" width="128" height="128" loading="eager">
      </div>
      <div>
        <h1 class="text-4xl sm:text-5xl font-semibold tracking-tight">Saul B. Kleinfeld</h1>
        <p class="mt-2 text-lg text-a-gray">Systems Builder & Playbook Architect — Product × Sports</p>

        <!-- colorful role chips -->
        <div class="mt-4 flex flex-wrap gap-2">
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-[#06c]/10 text-[#06c]">Senior PM @ RazorMetrics</span>
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-[#4E2A84]/10 text-[#4E2A84]">VP, Rookie League (NTABL)</span>
          <span class="inline-flex items-center px-3 py-1.5 rounded-full text-[13px] bg-[#C6007E]/10 text-[#C6007E]">MSA — Northwestern</span>
        </div>

        <div class="mt-6 flex flex-wrap gap-3">
          <a href="{{ '/biography/' | relative_url }}"
             class="inline-flex items-center rounded-full bg-a-black text-white px-4 py-2 text-sm hover:opacity-90">
            Read biography
          </a>
          <a href="{{ '/contact/' | relative_url }}"
             class="inline-flex items-center rounded-full border border-a-line px-4 py-2 text-sm hover:bg-white">
            Get in touch
          </a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- HIGHLIGHTS (replaces “What I do”) -->
<section class="wrap mx-auto px-4 sm:px-6 py-10">
  <h2 class="text-2xl font-semibold">Highlights</h2>

  <div class="mt-6 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <!-- Highlight 1 -->
    <article class="rounded-2xl bg-white shadow border border-a-line p-5">
      <div class="flex items-center gap-2">
        <span class="h-2.5 w-2.5 rounded-full bg-[#06c]"></span>
        <h3 class="font-medium">Config Tool MVP (RazorMetrics)</h3>
      </div>
      <p class="mt-2 text-[15px] text-a-black/90">
        Designed and led an internal configuration tool to streamline onboarding and reduce time-to-value.
      </p>
      <a href="{{ '/resume/' | relative_url }}" class="mt-3 inline-block text-[15px] alink">See resume</a>
    </article>

    <!-- Highlight 2 -->
    <article class="rounded-2xl bg-white shadow border border-a-line p-5">
      <div class="flex items-center gap-2">
        <span class="h-2.5 w-2.5 rounded-full bg-[#4E2A84]"></span>
        <h3 class="font-medium">League Growth & Media (NTABL)</h3>
      </div>
      <p class="mt-2 text-[15px] text-a-black/90">
        Expanded the Rookie League, stood up livestream “Game of the Week,” and built sponsor inventory playbooks.
      </p>
      <a href="{{ '/sports/' | relative_url }}" class="mt-3 inline-block text-[15px] alink">Explore sports</a>
    </article>

    <!-- Highlight 3 -->
    <article class="rounded-2xl bg-white shadow border border-a-line p-5">
      <div class="flex items-center gap-2">
        <span class="h-2.5 w-2.5 rounded-full bg-[#C6007E]"></span>
        <h3 class="font-medium">Northwestern Projects</h3>
      </div>
      <p class="mt-2 text-[15px] text-a-black/90">
        Coursework in sports analytics; dashboards and notebooks focused on player development and league ops.
      </p>
      <a href="{{ '/sports/' | relative_url }}" class="mt-3 inline-block text-[15px] alink">View projects</a>
    </article>
  </div>
</section>

<!-- QUICK LINKS -->
<section class="wrap mx-auto px-4 sm:px-6 pb-12">
  <div class="rounded-2xl border border-a-line bg-white p-5 flex flex-wrap gap-3">
    <a class="inline-flex items-center rounded-full border border-a-line px-4 py-2 hover:bg-a-bg"
       href="mailto:saul@kleinfeld.io?subject=Hello%20Saul&body=Hi%20Saul%2C%0D%0A%0D%0A">Email</a>
    <a class="inline-flex items-center rounded-full border border-a-line px-4 py-2 hover:bg-a-bg"
       href="https://calendly.com/saul-dallasmsbl/30min" target="_blank" rel="noopener">Book time</a>
    <a class="inline-flex items-center rounded-full border border-a-line px-4 py-2 hover:bg-a-bg"
       href="https://www.linkedin.com/in/saul-kleinfeld" target="_blank" rel="noopener">LinkedIn</a>
    <a class="inline-flex items-center rounded-full border border-a-line px-4 py-2 hover:bg-a-bg"
       href="{{ '/Sports_PdM _Saul_Kleinfeld_Resume.pdf' | relative_url | uri_escape }}" target="_blank" rel="noopener">Download résumé</a>
  </div>
</section>