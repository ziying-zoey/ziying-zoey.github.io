---
layout: default
permalink: /
title: "Ziying Huang"
description: "Academic homepage of Ziying Huang, a SUSTech graduate and incoming PhD student at the University of Melbourne."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<link rel="stylesheet" href="{{ '/assets/css/academic-home.css' | relative_url }}">
<div class="academic-home">
  <a class="home-skip" href="#main">Skip to content</a>
  <header class="home-header">
    <div class="home-container home-header-inner">
      <a class="home-brand" href="{{ '/' | relative_url }}">Ziying Huang</a>
      <nav class="home-nav" aria-label="Homepage">
        <a href="#selected-publications">Publications</a>
        <a href="#news">News</a>
        <a href="#award">Awards</a>
      </nav>
    </div>
  </header>

  <main id="main" class="home-container home-main" tabindex="-1">
    <section class="home-hero" aria-labelledby="home-name">
      <div class="home-intro">
        <h1 id="home-name">Ziying Huang</h1>
        <p class="home-bio">I graduated from Southern University of Science and Technology (SUSTech) with a bachelor’s degree in Communication Engineering. I will soon begin my PhD at the University of Melbourne.</p>
        <div class="home-actions">
          <a class="home-button home-button-primary" href="{{ '/files/CV.pdf' | relative_url }}">CV</a>
          <a class="home-button" href="{{ '/publications/' | relative_url }}">All publications</a>
        </div>
      </div>
      <div class="home-profile">
        <img src="{{ '/images/profile-pic.png' | relative_url }}" alt="Portrait of Ziying Huang" width="794" height="792">
        <ul class="home-contact" aria-label="Contact links">
          <li><a href="mailto:huangzy22@mail.sustech.edu.cn">Email</a></li>
          <li><a href="https://orcid.org/0009-0002-1783-1030">ORCID</a></li>
          <li><a href="https://www.linkedin.com/in/zoey-ziying">LinkedIn</a></li>
        </ul>
      </div>
    </section>

    <div class="home-sections">
      <section class="home-publications" id="selected-publications" aria-labelledby="home-publications-heading">
        <h2 class="home-section-title" id="home-publications-heading">Selected Publications</h2>
        <article class="home-paper">
          <p class="home-paper-venue">Findings of ACL 2026</p>
          <h3>The Model Agreed, But Didn’t Learn: Diagnosing Surface Compliance in Large Language Models</h3>
          <p class="home-paper-authors">Xiaojie Gu*, <strong>Ziying Huang</strong>*, Weicong Hong, Jian Xie, Renze Lou, Kai Zhang.</p>
          <a class="home-paper-link" href="https://openreview.net/forum?id=mxFX16IHal">OpenReview</a>
        </article>
        <article class="home-paper">
          <p class="home-paper-venue">TMLR</p>
          <h3>UltraEdit: Training-, Subject-, and Memory-Free Lifelong Editing in Language Models</h3>
          <p class="home-paper-authors">Xiaojie Gu, <strong>Ziying Huang</strong>, J.-C. Gu, Kai Zhang.</p>
          <a class="home-paper-link" href="https://arxiv.org/pdf/2505.14679">Paper</a>
        </article>
      </section>

      <div class="home-updates">
        <section class="home-news" id="news" aria-labelledby="home-news-heading">
          <h2 class="home-section-title" id="home-news-heading">News</h2>
          <ul class="home-news-list">
            <li>
              <time datetime="2026-04">Apr 2026</time>
              <p>Our paper <cite>The Model Agreed, But Didn’t Learn: Diagnosing Surface Compliance in Large Language Models</cite> was accepted to Findings of ACL 2026.</p>
            </li>
            <li>
              <time datetime="2026-03">Mar 2026</time>
              <p>Our paper <cite>UltraEdit: Training-, Subject-, and Memory-Free Lifelong Editing in Language Models</cite> was accepted by TMLR.</p>
            </li>
            <li>
              <time datetime="2025-11">Nov 2025</time>
              <p>Selected as one of the Top 15 Individuals in the G-Star Global Talent Program 2025 by the <a href="https://newturing.ai/">New Turing Institute</a>.</p>
            </li>
            <li>
              <time datetime="2025-02">Feb 2025</time>
              <p>Our <a href="https://asc-events.net/StudentChallenge/History/2025/index.html">ASC Student Supercomputer Challenge</a> team won the International Second Prize as part of Team ASC900.</p>
            </li>
          </ul>
        </section>
        <section class="home-awards" id="award" aria-labelledby="home-awards-heading">
          <h2 class="home-section-title" id="home-awards-heading">Awards</h2>
          <ul class="home-award-list">
            <li>G-Star Global Talent Program Top 15 Individual</li>
            <li>ASC Student Supercomputer Challenge International Second Prize</li>
            <li>Outstanding Student Scholarship, SUSTech – First Prize (¥5,000; top 5%) 2024 &amp; 2025</li>
          </ul>
        </section>
      </div>
    </div>

    <section class="home-visitors" id="visitors" aria-labelledby="home-visitors-heading">
      <h2 class="home-section-title" id="home-visitors-heading">Visitors</h2>
      <div class="home-visitor-map">
        <script id="clustrmaps" src="https://clustrmaps.com/map_v2.js?d=2L3_4H50djrUl8gNVgZWpqzgCUgDsCXBDJmDtSVYZwo&amp;cl=ffffff&amp;w=a"></script>
      </div>
    </section>
  </main>

  <footer class="home-footer">
    <div class="home-container home-footer-inner">
      <span>© {{ site.time | date: '%Y' }} Ziying Huang</span>
      <nav aria-label="Footer">
        <a href="{{ '/sitemap/' | relative_url }}">Sitemap</a>
        <a href="{{ '/feed.xml' | relative_url }}">RSS</a>
      </nav>
    </div>
  </footer>
</div>
