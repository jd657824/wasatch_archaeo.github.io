---
layout: page
title: "Foundational Concepts & Theoretical Insights"
permalink: /blog-index/
---

<style>
  /* Hide auto-generated heading */
  h1.post-title, h1.page-title, header.post-header h1 {
      display: none !important;
  }
  
  /* Color Palette */
  :root {
      --primary-color: #5b7e5f;
      --secondary-color: #8a6552;
      --accent-color: #d8b976;
      --light-bg: #f8f8f5;
      --dark-text: #333333;
  }
  
  /* Main content styles */
  .content-wrapper {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.7;
      color: var(--dark-text);
      max-width: 900px;
      margin: 0 auto;
      padding: 0 20px;
  }
  
  /* Introduction paragraph */
  .content-wrapper > p {
      font-size: 1.1rem;
      margin-bottom: 1.5rem;
      text-align: justify;
  }
  
  /* Content headings */
  .content-wrapper h2 {
      font-size: 1.7rem;
      color: var(--secondary-color);
      margin: 2.2rem 0 1.2rem;
      font-weight: 500;
      border-bottom: 1px solid rgba(216, 185, 118, 0.3);
      padding-bottom: 0.5rem;
  }
  
  /* Blog post (page) entry */
  .blog-entry {
      margin-bottom: 2rem;
      padding: 1rem;
      background-color: rgba(91, 126, 95, 0.05);
      border-radius: 4px;
  }
  
  .blog-entry h2 {
      margin-top: 0;
      font-size: 1.4rem;
      color: var(--secondary-color);
  }
  
  .blog-entry .post-meta {
      font-style: italic;
      color: var(--secondary-color);
      margin-bottom: 0.5rem;
  }
  
  .blog-entry .highlights {
      margin-top: 0.5rem;
  }
  
  .blog-entry .highlights li {
      margin-bottom: 0.5rem;
      position: relative;
      padding-left: 1.2rem;
      list-style-type: none;
  }
  
  .blog-entry .highlights li::before {
      content: "•";
      color: var(--accent-color);
      font-weight: bold;
      position: absolute;
      left: 0;
  }
  
  /* Subtle section dividers */
  .subtle-divider {
      height: 1px;
      background: linear-gradient(to right, transparent, #e0e0e0, transparent);
      margin: 2rem 0;
      border: none;
  }
  
  /* Read More link */
  .read-more {
      display: inline-block;
      color: var(--secondary-color);
      text-decoration: none;
      font-weight: 600;
      margin-top: 0.5rem;
  }
  
  .read-more:hover {
      text-decoration: underline;
  }
</style>

<div class="content-wrapper">
  <p>
    Welcome to a curated collection offering background insights into my research. This evolving compendium delves into foundational concepts and theoretical perspectives essential for exploring human–environment relationships.
  </p>
  
  <hr class="subtle-divider">
  
  <!-- Two-Eyed Seeing Page -->
  <div class="blog-entry">
    <h2><a href="{{ site.baseurl }}/two-eye.html" class="read-more">Two-Eyed Seeing</a></h2>
    <p class="post-meta">Posted: 2-25-25</p>
    <p><em>Integrating Indigenous and Western Knowledge Systems</em></p>
    <div class="highlights">
      <ul>
        <li>Presents the concept of <em>Etuaptmumk</em> ("Two-Eyed Seeing"), introduced by Mi'kmaw Elder Albert Marshall.</li>
        <li>Encourages viewing the world through two distinct yet complementary lenses—Traditional Ecological Knowledge and Western science.</li>
        <li>Shows how bridging these perspectives leads to deeper insights and collaborative research approaches.</li>
        <li>Emphasizes mutual respect and dynamic integration rather than a uniform perspective.</li>
      </ul>
    </div>
    <a href="{{ site.baseurl }}/two-eye.html" class="read-more">Read Full Post →</a>
  </div>
  
  <hr class="subtle-divider">
  
  <!-- Ethnobotanical Data Disclaimer Page -->
  <div class="blog-entry">
    <h2><a href="{{ site.baseurl }}/disclaimer.html" class="read-more">Ethnobotanical Data Disclaimer</a></h2>
    <p class="post-meta">Posted: [TBA]</p>
    <p><em>Important information regarding the use of ethnobotanical data.</em></p>
    <a href="{{ site.baseurl }}/disclaimer.html" class="read-more">Read Full Post →</a>
  </div>
  
  <hr class="subtle-divider">
  
  <!-- Cultural-Ecological Disconnect Page -->
  <div class="blog-entry">
    <h2><a href="{{ site.baseurl }}/cultural-ecological.html" class="read-more">Cultural-Ecological Disconnect</a></h2>
    <p class="post-meta">Posted: 3-31-25</p>
    <p><em>Understanding How We Became Separated from Our Natural Context</em></p>
    <div class="highlights">
      <ul>
        <li>Defines the "cultural-ecological disconnect" and traces its roots in industrialization and colonial expansion.</li>
        <li>Examines impacts like resource overexploitation, reduced adaptive capacity, and erosion of Indigenous knowledge systems.</li>
        <li>Explores how bridging Traditional Ecological Knowledge with scientific frameworks fosters reconnection and resilience.</li>
      </ul>
    </div>
    <a href="{{ site.baseurl }}/cultural-ecological.html" class="read-more">Read Full Post →</a>
  </div>
  
</div>
