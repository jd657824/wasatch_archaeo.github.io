---
layout: page
title: ""
permalink: /
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
    
    /* Links styling */
    .content-wrapper a {
        color: var(--primary-color);
        text-decoration: none;
        border-bottom: 1px solid var(--accent-color);
        transition: color 0.2s, border-color 0.2s;
        font-weight: 500;
    }
    
    .content-wrapper a:hover {
        color: var(--secondary-color);
        border-color: var(--secondary-color);
    }
    
    /* Image styling */
    .content-wrapper img {
        display: block;
        max-width: 100%;
        height: auto;
        margin: 2rem auto;
        border-radius: 4px;
        box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    }
    
    /* Donation Section Styles */
    .donation-section {
        margin-top: 2rem;
        padding: 1rem;
        background-color: rgba(216, 185, 118, 0.1);
        border: 1px solid rgba(216, 185, 118, 0.3);
        border-radius: 4px;
    }
    
    .donation-section h2 {
        font-size: 1.6rem;
        color: var(--secondary-color);
        margin-bottom: 0.5rem;
    }
    
    .donation-section a {
        color: var(--primary-color);
        text-decoration: none;
        font-weight: 600;
    }
    
    .donation-section a:hover {
        text-decoration: underline;
    }
</style>

<div class="content-wrapper">
    <img src="./images/IMG_0081.jpeg" alt="Description of image" style="width: 400px; max-width: 100%; height: auto;">
    
    <p>
        Welcome to my personal research blog—a scholarly space dedicated to sharing insights from fieldwork, research perspectives, and rigorous explorations of both theoretical constructs and imaginative inquiries. My aim is not only to confront the unknown but also to present these challenges in an accessible manner, enabling diverse audiences to engage with and comprehend the intricate dynamics of our Earth system and the extraordinary adaptive strategies that have sustained human societies throughout time.
    </p>
    
    <!-- Donation Section -->
    <div class="donation-section">
        <h2>Support Research</h2>
        <p>
            Your generous donations help support ongoing research projects and enable further interdisciplinary inquiry. If you would like to contribute to advancing this work, please consider making a donation.
        </p>
        <p>
            <a href="https://example.com/donate" target="_blank">Donate Now</a>
        </p>
    </div>
    
</div>
