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

/* Blog post entry */
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
    border-bottom: none;
    padding-bottom: 0;
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

/* Emphasis and key terms */
.content-wrapper strong, 
.content-wrapper b {
    color: var(--secondary-color);
    font-weight: 600;
}

.content-wrapper em, 
.content-wrapper i {
    color: var(--primary-color);
    font-style: italic;
}
</style>

<div class="content-wrapper">

  <!-- Intro Paragraph -->
  <p>
    Welcome to a curated collection offering background insights into my research. 
    This evolving compendium delves into foundational concepts and theoretical perspectives essential for exploring human–environment relationships. 
    Covering topics from climatic stationarity and niche construction to topographic regionalization and cultural ecological frameworks, 
    each entry provides a critical perspective on the dynamic interplay between people and their surroundings. 
    Use this gateway to dive deeper into each specialized post and enrich your understanding of these complex interconnections.
  </p>

  <hr class="subtle-divider">

  <!-- Example: link to "disclaimer" page -->
  <p>
    <strong>Ethnobotanical Data Disclaimer:</strong>
    <!-- Adjust /disclaimer/ if your actual permalink is different -->
    <a href="{{ "/disclaimer/" | relative_url }}" class="read-more">Read Full Post →</a>
  </p>

  <hr class="subtle-divider">
  
  <!-- Blog 1: Two-Eyed Seeing -->
  <div class="blog-entry">
      <h2>1. Two-Eyed Seeing</h2>
      <p class="post-meta">Posted: <em>2-25-25</em></p>
      <p><em>Integrating Indigenous and Western Knowledge Systems</em></p>
      
      <div class="highlights">
          <ul>
              <li>Presents the concept of <em>Etuaptmumk</em> ("Two-Eyed Seeing"), introduced by Mi'kmaw Elder Albert Marshall, as a guiding framework.</li>
              <li>Encourages viewing the world through <strong>two distinct yet complementary lenses</strong>—Traditional Ecological Knowledge and Western science.</li>
              <li>Shows how bridging these perspectives leads to deeper insights, collaborative research approaches, and more inclusive stewardship practices.</li>
              <li>Emphasizes <strong>mutual respect</strong> and <strong>dynamic integration</strong>, rather than blending knowledge systems into a single, uniform perspective.</li>
          </ul>
      </div>

      <!-- Adjust /two-eye/ if your actual permalink is different -->
      <a href="{{ "/two-eye/" | relative_url }}" class="read-more">Read Full Post →</a>
  </div>
  
  <hr class="subtle-divider">

  <!-- Blog 2: Cultural-Ecological Disconnect -->
  <div class="blog-entry">
      <h2>2. Cultural-Ecological Disconnect</h2>
      <p class="post-meta">Posted: <em>TBA</em></p>
      <p><em>Understanding How We Became Separated from Our Natural Context</em></p>
      
      <div class="highlights">
          <ul>
              <li>Defines the "cultural-ecological disconnect" and traces its roots in industrialization and colonial expansion.</li>
              <li>Examines impacts like resource overexploitation, reduced adaptive capacity, and erosion of Indigenous knowledge systems.</li>
              <li>Explores how bridging TEK with scientific frameworks fosters reconnection and resilience.</li>
          </ul>
      </div>
      
      <!-- If the page is not ready, keep # or update the link once you have the page/permalink -->
      <a href="#" class="read-more">Read Full Post →</a>
  </div>
  
  <hr class="subtle-divider">

  <!-- Blog 3: Bronfenbrenner's Bioecological Model -->
  <div class="blog-entry">
      <h2>3. Bronfenbrenner's Bioecological Model</h2>
      <p class="post-meta">Posted: <em>TBA</em></p>
      <p><em>Understanding Human Development Through the PPCT Lens</em></p>
      
      <div class="highlights">
          <ul>
              <li>Introduces Urie Bronfenbrenner's bioecological model, highlighting the <strong>Process-Person-Context-Time (PPCT)</strong> framework.</li>
              <li>Explains how <strong>microsystems, mesosystems, exosystems, and macrosystems</strong> shape individual growth within an ecological context.</li>
              <li>Emphasizes <strong>process</strong> (reciprocal interactions), <strong>person</strong> (individual characteristics), <strong>context</strong> (environmental layers), and <strong>time</strong> (temporal shifts) as interconnected factors.</li>
              <li>Draws parallels to environmental anthropology, illustrating how social structures and personal experiences are nested within broader ecological and cultural systems.</li>
          </ul>
      </div>

      <a href="#" class="read-more">Read Full Post →</a>
  </div>
  
  <hr class="subtle-divider">

  <!-- Repeat the pattern for each subsequent blog entry... -->
  
  <!-- Blog 4: Julian Steward and Karl Butzer -->
  <div class="blog-entry">
      <h2>4. Julian Steward and Karl Butzer</h2>
      <p class="post-meta">Posted: <em>TBA</em></p>
      <p><em>Where Cultural Ecology Meets Archaeology as Human Ecology</em></p>
      
      <div class="highlights">
          <ul>
              <li>Compares Steward's cultural ecology (multilinear evolution) with Butzer's "archaeology as human ecology".</li>
              <li>Discusses Butzer's five critical dynamics (environment, technology, economy, social organization, ideology).</li>
              <li>Highlights environment-culture feedback loops and the importance of holistic, long-term perspectives.</li>
          </ul>
      </div>
      
      <a href="#" class="read-more">Read Full Post →</a>
  </div>

  <!-- Continue similarly for each entry. Just ensure the href matches the actual permalink. -->

</div>
