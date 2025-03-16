---
layout: page
title: "Blog"
permalink: /blog/
nav_exclude: true
---

<style>
    /* Hide auto-generated heading if desired */
    h1.post-title, h1.page-title, header.post-header h1 {
        display: none !important;
    }
    
    /* Color Palette (same as your site) */
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
    
    /* Page title */
    .content-wrapper h1 {
        font-size: 2.0rem;
        color: var(--secondary-color);
        margin: 2rem 0 1.5rem;
        font-weight: 500;
        border-bottom: 1px solid rgba(216, 185, 118, 0.3);
        padding-bottom: 0.5rem;
    }
    
    /* Blog entry container */
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
    
    /* Subtle dividers */
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
    <h1>Blog</h1>

    <!-- 1. EAH Post (First Post) -->
    <div class="blog-entry">
        <h2>The Environmental Archaeology Heuristic (EAH)</h2>
        <p class="post-meta">Posted: <em>3-17-25</em></p>
        <p><em>A Multi-Scalar Temporal and Spatial Framework for Evaluating Human-Environmental Adaptive Strategies</em></p>
        
        <div class="highlights">
            <ul>
                <li>Introduces a systematic approach for analyzing how human societies adapt to environmental conditions.</li>
                <li>Focuses on temporal and spatial scales, incorporating archaeological, paleoenvironmental, and ethnographic data.</li>
                <li>Demonstrates how the EAH framework can reveal patterns of resilience and innovation in past societies.</li>
            </ul>
        </div>
        
        <!-- Link to full post -->
        <a href="/blog/the-environmental-archaeology-heuristic/" class="read-more">Read Full Post →</a>
    </div>
    
    <hr class="subtle-divider">

    <!-- 2. Add more blog entries below as needed -->
    <!-- Example second blog entry: -->
    <div class="blog-entry">
        <h2>Another Blog Post Title</h2>
        <p class="post-meta">Posted: <em>TBA</em></p>
        <p><em>A short excerpt describing the second blog post.</em></p>
        
        <div class="highlights">
            <ul>
                <li>Key point or highlight #1</li>
                <li>Key point or highlight #2</li>
            </ul>
        </div>
        
        <a href="#" class="read-more">Read Full Post →</a>
    </div>

    <!-- Add more posts as you like -->

</div>
