---
layout: page
title: "About"
permalink: /about/
---

<style>
    /* Hide auto-generated heading if present */
    h1.post-title, h1.page-title, header.post-header h1 {
        display: none !important;
    }
    
    :root {
        --primary-color: #5b7e5f;
        --secondary-color: #8a6552;
        --accent-color: #d8b976;
        --light-bg: #f8f8f5;
        --dark-text: #333333;
    }
    
    .content-wrapper {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.7;
        color: var(--dark-text);
        max-width: 900px;
        margin: 0 auto;
        padding: 0 20px;
    }
    
    .content-wrapper h1 {
        font-size: 2.2rem;
        color: var(--secondary-color);
        margin: 2rem 0 1rem;
        font-weight: 500;
        border-bottom: 1px solid rgba(216,185,118,0.3);
        padding-bottom: 0.5rem;
    }
    
    .content-wrapper p {
        font-size: 1.1rem;
        margin-bottom: 1.5rem;
        text-align: justify;
    }
    
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
        padding-bottom: 0;
    }
    
    .blog-entry .post-meta {
        font-style: italic;
        color: var(--secondary-color);
        margin-bottom: 0.5rem;
    }
    
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
    <h1>About This Blog</h1>
    
    <p>
        Welcome to my personal research blog—a space where interdisciplinary insights meet rigorous academic inquiry. Here, I explore the complex dynamics of human–environment relationships, drawing on theoretical constructs, fieldwork, and imaginative research perspectives. Whether you’re a fellow scholar, student, or engaged reader, my aim is to present challenging topics in a manner that is both accessible and thought-provoking.
    </p>
    
    <p>
        The blog is organized into several key sections. Click the buttons below to explore each area:
    </p>
    
    <!-- Foundational Concepts & Theoretical Insights -->
    <div class="blog-entry">
        <h2>Foundational Concepts &amp; Theoretical Insights</h2>
        <p class="post-meta"><em>Core ideas and frameworks that underpin my research.</em></p>
        <a href="{{ "/blog-index/" | relative_url }}" class="read-more">Click Here →</a>
    </div>
    
    <!-- Blog -->
    <div class="blog-entry">
        <h2>Blog</h2>
        <p class="post-meta"><em>Regularly updated posts, case studies, and research discussions.</em></p>
        <a href="{{ "/blog/" | relative_url }}" class="read-more">Click Here →</a>
    </div>
    
    <!-- Projects -->
    <div class="blog-entry">
        <h2>Projects</h2>
        <p class="post-meta"><em>Ongoing research initiatives, manuscripts, and collaboration opportunities.</em></p>
        <a href="{{ "/projects/" | relative_url }}" class="read-more">Click Here →</a>
    </div>
    
    <!-- Credentials -->
    <div class="blog-entry">
        <h2>Credentials</h2>
        <p class="post-meta"><em>A summary of my academic achievements, CV, teaching philosophy, and research program.</em></p>
        <a href="{{ "/credentials/" | relative_url }}" class="read-more">Click Here →</a>
    </div>
    
    <!-- Podcast -->
    <div class="blog-entry">
        <h2>Podcast</h2>
        <p class="post-meta"><em>Episodes featuring updates and discussions on environmental research.</em></p>
        <a href="{{ "/podcast/" | relative_url }}" class="read-more">Click Here →</a>
    </div>
    
    <p>
        If you are interested in collaboration or have inquiries regarding my research, please feel free to <a href="mailto:your-email@example.com">contact me</a> using the information provided below.
    </p>
</div>
