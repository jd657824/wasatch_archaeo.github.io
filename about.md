---
layout: page
title: "About"
permalink: /about/
---

<style>
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
