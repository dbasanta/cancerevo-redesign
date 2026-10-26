---
layout: default
title: Home
description: The CancerEvo Group develops mathematical and computational models of cancer ecology, evolution, treatment response, and resistance.
---

<section class="home-intro">
  <h1 class="home-title">CancerEvo</h1>
  <p class="home-sub">Cancer ecology &amp; evolution</p>
  <p class="home-affil"><a href="{{ site.imo_url }}" target="_blank" rel="noopener noreferrer">Integrated Mathematical Oncology</a> &middot; <a href="{{ site.moffitt_url }}" target="_blank" rel="noopener noreferrer">Moffitt Cancer Center</a></p>
</section>

<svg class="svg-defs" aria-hidden="true"><defs>
  <marker id="ah" viewBox="0 0 10 10" refX="8.5" refY="5" markerWidth="7" markerHeight="7" orient="auto-start-reverse">
    <path d="M1,1 L9,5 L1,9" fill="none" stroke="#222" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/></marker>
</defs></svg>

<nav class="icon-grid" aria-label="Site sections">
  <a class="tile" href="{{ '/research' | relative_url }}" style="--c: #D9483B">
    {% include icons/research.svg %}
    <span>Research</span>
  </a>
  <a class="tile" href="{{ '/publications' | relative_url }}" style="--c: #E58A1F">
    {% include icons/publications.svg %}
    <span>Publications</span>
  </a>
  <a class="tile" href="{{ '/team' | relative_url }}" style="--c: #B0418F">
    {% include icons/team.svg %}
    <span>Team</span>
  </a>
  <a class="tile" href="{{ '/models' | relative_url }}" style="--c: #2E9655">
    {% include icons/models.svg %}
    <span>Models &amp; Code</span>
  </a>
  <a class="tile" href="{{ '/outreach' | relative_url }}" style="--c: #1592A6">
    {% include icons/outreach.svg %}
    <span>Outreach</span>
  </a>
</nav>
