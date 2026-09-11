---
layout: page
permalink: /publications/
title: publications
description: A list of my publications in reverse chronological order.
nav: true
nav_order: 2
---

<div class="pub-stats">
  <div class="pub-stat-item">
    <span class="pub-stat-number">40+</span>
    <span class="pub-stat-label">Peer-Reviewed Publications</span>
  </div>
  <div class="pub-stat-divider"></div>
  <div class="pub-stat-item">
    <span class="pub-stat-number">8</span>
    <span class="pub-stat-label">Journal Articles</span>
  </div>
  <div class="pub-stat-divider"></div>
  <div class="pub-stat-item">
    <span class="pub-stat-number">3</span>
    <span class="pub-stat-label">US Patents</span>
  </div>
  <div class="pub-stat-divider"></div>
  <div class="pub-stat-item">
    <span class="pub-stat-number">4</span>
    <span class="pub-stat-label">Best Paper / Demo Awards</span>
  </div>
</div>

<div class="pub-awards-bar">
  <span class="pub-award-item">🏆 Best Paper &mdash; AsianHOST 2018</span>
  <span class="pub-award-sep">·</span>
  <span class="pub-award-item">🏅 Best Poster/Demo &mdash; ACM WiSec 2025</span>
  <span class="pub-award-sep">·</span>
  <span class="pub-award-item">🥈 Best Hardware Demo (2nd) &mdash; IEEE HOST 2024</span>
  <span class="pub-award-sep">·</span>
  <span class="pub-award-item">📝 Best Paper Nominee &mdash; ACM GLSVLSI 2017</span>
</div>

<!-- _pages/publications.md -->
<div class="publications">

{% bibliography %}

</div>

<style>
/* ── Publications summary ── */
.pub-stats {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  gap: 0;
  background: var(--global-card-bg-color, #f4f6f9);
  border-radius: 8px;
  padding: 1.2rem 2rem;
  margin: 1.5rem 0 1rem;
}
.pub-stat-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0 1.8rem;
  min-width: 90px;
}
.pub-stat-number {
  font-size: 1.8rem;
  font-weight: 700;
  color: var(--global-theme-color, #1565c0);
  line-height: 1;
}
.pub-stat-label {
  font-size: 0.7rem;
  color: var(--global-text-color-light, #777);
  text-transform: uppercase;
  letter-spacing: 0.05em;
  margin-top: 0.3rem;
  text-align: center;
}
.pub-stat-divider {
  width: 1px;
  height: 2.5rem;
  background: var(--global-divider-color, #dee2e6);
  flex-shrink: 0;
}
.pub-awards-bar {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  gap: 0.4rem 0.6rem;
  padding: 0.6rem 1rem;
  background: var(--global-card-bg-color, #f4f6f9);
  border-radius: 6px;
  margin-bottom: 1.5rem;
  font-size: 0.82rem;
}
.pub-award-item {
  color: var(--global-text-color, #333);
}
.pub-award-sep {
  color: var(--global-text-color-light, #999);
}
</style>
