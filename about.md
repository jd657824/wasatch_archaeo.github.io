---
layout: page
title: "About"
permalink: /about/
---

<style>
    /* This is the critical part - hide the auto-generated About heading */
    h1.post-title, h1.page-title, header.post-header h1 {
        display: none !important;
    }
    
    /* Text-only styling that preserves existing navigation and footer */
    :root {
        --primary-color: #5b7e5f;
        --secondary-color: #8a6552;
        --accent-color: #d8b976;
        --light-bg: #f8f8f5;
        --dark-text: #333333;
    }
    
    /* Main content styles only */
    .content-wrapper {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.7;
        color: var(--dark-text);
        max-width: 900px;
        margin: 0 auto;
        padding: 0 20px;
    }
    
    /* Content headings */
    .content-wrapper h2 {
        font-size: 1.7rem;
        color: var(--secondary-color);
        margin: 2.2rem 0 1.2rem;
        font-weight: 500;
    }
    
    .content-wrapper h3 {
        font-size: 1.35rem;
        color: var(--primary-color);
        margin: 1.8rem 0 1rem;
        font-weight: 500;
    }
    
    /* Paragraph styling */
    .content-wrapper p {
        margin-bottom: 1.2rem;
        font-size: 1.05rem;
        line-height: 1.7;
        text-align: justify;
    }
    
    /* Emphasis */
    .content-wrapper strong, 
    .content-wrapper b {
        color: var(--secondary-color);
        font-weight: 600;
    }
    
    /* Horizontal rules */
    .content-wrapper hr {
        border: none;
        height: 1px;
        background-color: #e0e0e0;
        margin: 2rem 0;
    }
    
    /* Lists */
    .content-wrapper ul {
        margin-left: 1rem;
        margin-bottom: 1.5rem;
    }
    
    .content-wrapper li {
        margin-bottom: 0.7rem;
        position: relative;
        padding-left: 1.2rem;
        list-style-type: none;
    }
    
    .content-wrapper li::before {
        content: "•";
        color: var(--accent-color);
        font-weight: bold;
        position: absolute;
        left: 0;
    }
    
    /* Key terms */
    .key-term {
        background-color: rgba(216, 185, 118, 0.2);
        padding: 0 4px;
        border-radius: 3px;
    }
    
    /* Section dividers (subtle) */
    .subtle-divider {
        height: 1px;
        background: linear-gradient(to right, transparent, #e0e0e0, transparent);
        margin: 2rem 0;
        border: none;
    }
    
    /* Researcher title styling */
    .researcher-title {
        font-size: 1.2rem;
        font-weight: 500;
        text-align: center;
        margin: 1.5rem 0;
        color: var(--secondary-color);
        font-style: italic;
    }
    
    /* Box for important content */
    .highlight-box {
        border-left: 3px solid var(--accent-color);
        background-color: rgba(216, 185, 118, 0.1);
        padding: 1rem 1.5rem;
        margin: 1.5rem 0;
        border-radius: 0 4px 4px 0;
    }
    
    /* Quote styling */
    .content-wrapper blockquote {
        border-left: 3px solid var(--accent-color);
        padding: 0.5rem 0 0.5rem 1rem;
        margin: 1.5rem 0 1.5rem 1rem;
        font-style: italic;
        color: #555;
    }
</style>

<div class="content-wrapper">
  <p>
    Welcome to a curated collection offering background insights into my research. This evolving compendium delves into foundational concepts and theoretical perspectives essential for exploring human–environment relationships.
  </p>
  
  <hr class="subtle-divider">
  
  <!-- Two-Eyed Seeing Page -->
  <div class="blog-entry">
    <h2><a href="{{ site.baseurl }}/two-eye" class="read-more">Two-Eyed Seeing</a></h2>
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
    <a href="{{ site.baseurl }}/two-eye" class="read-more">Read Full Post →</a>
  </div>
  
  <hr class="subtle-divider">
  
  <!-- Ethnobotanical Data Disclaimer Page -->
  <div class="blog-entry">
    <h2><a href="{{ site.baseurl }}/disclaimer" class="read-more">Ethnobotanical Data Disclaimer</a></h2>
    <p class="post-meta">Posted: [TBA]</p>
    <p><em>Important information regarding the use of ethnobotanical data.</em></p>
    <a href="{{ site.baseurl }}/disclaimer" class="read-more">Read Full Post →</a>
  </div>
  
  <hr class="subtle-divider">
  
  <!-- Cultural-Ecological Disconnect Page -->
  <div class="blog-entry">
    <h2><a href="{{ site.baseurl }}/cultural-ecological" class="read-more">Cultural-Ecological Disconnect</a></h2>
    <p class="post-meta">Posted: 3-31-25</p>
    <p><em>Understanding How We Became Separated from Our Natural Context</em></p>
    <div class="highlights">
      <ul>
        <li>Defines the "cultural-ecological disconnect" and traces its roots in industrialization and colonial expansion.</li>
        <li>Examines impacts like resource overexploitation, reduced adaptive capacity, and erosion of Indigenous knowledge systems.</li>
        <li>Explores how bridging Traditional Ecological Knowledge with scientific frameworks fosters reconnection and resilience.</li>
      </ul>
    </div>
    <a href="{{ site.baseurl }}/cultural-ecological" class="read-more">Read Full Post →</a>
  </div>
  
</div>
