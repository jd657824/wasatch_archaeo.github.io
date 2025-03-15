---
layout: page
title: "About"
permalink: /about/
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wasatch-Archaeo | Dr. Justin "JD" Dolinar</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #5b7e5f;
            --secondary-color: #8a6552;
            --accent-color: #d8b976;
            --light-bg: #f5f5f0;
            --dark-text: #333333;
            --light-text: #fcfcfc;
            --section-padding: 3rem 2rem;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--dark-text);
            background-color: var(--light-bg);
        }
        
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--light-text);
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .header-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .site-title {
            font-size: 1.8rem;
            font-weight: 300;
            letter-spacing: 1px;
        }
        
        .site-title a {
            color: var(--light-text);
            text-decoration: none;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 1.5rem;
        }
        
        nav ul li a {
            color: var(--light-text);
            text-decoration: none;
            font-weight: 500;
            font-size: 1.1rem;
            padding: 0.5rem 0;
            border-bottom: 2px solid transparent;
            transition: border-bottom 0.3s;
        }
        
        nav ul li a:hover {
            border-bottom: 2px solid var(--accent-color);
        }
        
        main {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .hero {
            background: url('/api/placeholder/1000/400') center/cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 3rem;
            border-radius: 8px;
            overflow: hidden;
            position: relative;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.4);
        }
        
        .hero-content {
            position: relative;
            color: white;
            text-align: center;
            max-width: 800px;
            padding: 2rem;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 1.5rem;
            font-weight: 300;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
        }
        
        section {
            margin-bottom: 3rem;
            background: white;
            padding: var(--section-padding);
            border-radius: 8px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.05);
        }
        
        h2 {
            font-size: 2rem;
            color: var(--primary-color);
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--accent-color);
        }
        
        h3 {
            font-size: 1.4rem;
            color: var(--secondary-color);
            margin: 1.5rem 0 1rem 0;
        }
        
        p {
            margin-bottom: 1.2rem;
            font-size: 1.05rem;
        }
        
        strong {
            color: var(--secondary-color);
        }
        
        hr {
            border: none;
            height: 1px;
            background-color: #e0e0e0;
            margin: 2rem 0;
        }
        
        ul {
            margin-left: 1.5rem;
            margin-bottom: 1.5rem;
        }
        
        li {
            margin-bottom: 0.5rem;
            position: relative;
            list-style-type: none;
            padding-left: 1.5rem;
        }
        
        li:before {
            content: "\f00c";
            font-family: "Font Awesome 6 Free";
            font-weight: 900;
            position: absolute;
            left: 0;
            color: var(--primary-color);
        }
        
        .subtitle {
            text-align: center;
            font-size: 1.2rem;
            font-weight: 500;
            margin-bottom: 2rem;
            color: var(--secondary-color);
        }
        
        .profile-container {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            margin-bottom: 2rem;
        }
        
        .profile-image {
            flex: 0 0 200px;
            height: 200px;
            background: url('/api/placeholder/200/200') center/cover;
            border-radius: 50%;
            border: 4px solid var(--accent-color);
        }
        
        .profile-content {
            flex: 1;
            min-width: 300px;
        }
        
        .method-card {
            background-color: #f9f9f9;
            border-left: 4px solid var(--primary-color);
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            border-radius: 0 8px 8px 0;
        }
        
        footer {
            background-color: var(--dark-text);
            color: var(--light-text);
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }
        
        @media (max-width: 768px) {
            header {
                padding: 1rem 2rem;
            }
            
            .header-content {
                flex-direction: column;
            }
            
            nav ul {
                margin-top: 1rem;
            }
            
            nav ul li {
                margin-left: 1rem;
                margin-right: 1rem;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .profile-container {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <h1 class="site-title"><a href="#">Wasatch-Archaeo</a></h1>
            <nav>
                <ul>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Credentials</a></li>
                    <li><a href="#">Podcast</a></li>
                    <li><a href="#">Projects</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main>
        <div class="hero">
            <div class="hero-content">
                <h1>Environmental Archaeology &amp; Human-Environment Co-evolution</h1>
                <p>Exploring the dynamic interplay between cultural practices and ecological processes</p>
            </div>
        </div>
        
        <section id="about">
            <h2>About the Researcher</h2>
            <div class="profile-container">
                <div class="profile-image"></div>
                <div class="profile-content">
                    <h3>Dr. Justin "JD" Dolinar</h3>
                    <p class="subtitle">Environmental Archaeologist &amp; Human-Environment Co-evolution Specialist</p>
                    <p>My doctoral research at the University of Utah examined the dynamic interplay between cultural practices and ecological processes throughout the Holocene period in the Intermountain West. This work culminated in the development of the <strong>Environmental Archaeology Heuristic (EAH)</strong>, an innovative framework integrating Optimal Foraging Theory with Niche Construction Theory.</p>
                </div>
            </div>
        </section>
        
        <section id="theoretical-framework">
            <h2>Theoretical Framework</h2>
            <p>The EAH framework extends Butzer's (1982) "Archaeology as Human Ecology" concept by incorporating Bronfenbrenner's Bioecological Model—specifically its nested, multi-scalar PPCT framework—to enable comprehensive analysis of human-environment interactions across temporal and spatial scales.</p>
            
            <div class="method-card">
                <h3>Methodological Approach</h3>
                <p>My research employs a <strong>Two-Eyed Seeing approach</strong> that synthesizes:</p>
                <ul>
                    <li>Indigenous Traditional Ecological Knowledge</li>
                    <li>Quantitative Western scientific methodologies</li>
                </ul>
                <p>This integration illuminates how prehistoric hunter-gatherers not only optimized immediate resource extraction but actively modified their landscapes to ensure long-term environmental sustainability.</p>
            </div>
        </section>
        
        <section id="research-methods">
            <h2>Research Methods</h2>
            <p>My investigations utilize:</p>
            <ul>
                <li>Advanced geospatial analysis</li>
                <li>Statistical Computation</li>
                <li>Western North American Archaeological Theory</li>
                <li>Archaeo- &amp; Ethno-botanical techniques</li>
                <li>Evolutionary ecology methods</li>
                <li>Geomorphic &amp; Biogeographic Principles</li>
            </ul>
            <p>These approaches support my examination of subsistence-settlement patterns, floral diversity, and phenotypic adaptations—with Utah juniper serving as a key case study.</p>
        </section>
        
        <section id="impact">
            <h2>Impact &amp; Commitment</h2>
            <p>My work contributes to theoretical discussions on human resilience and sustainability by demonstrating the reciprocal feedbacks between cultural agency and environmental change. I remain committed to advancing interdisciplinary scholarship and fostering collaborative partnerships with Indigenous communities to enrich our collective understanding of past and present human ecological dynamics.</p>
        </section>
        
        <section id="why-environmental-archaeology">
            <h2>Why Environmental Archaeology?</h2>
            <p>Environmental archaeology provides a critical lens for understanding the complex, reciprocal relationships between human societies and their environments over time. This discipline transcends traditional archaeological narratives that treat culture and nature as distinct domains, instead emphasizing that human actions—from subsistence practices to land management—are inextricably linked to and co-constitutive of the natural world.</p>
            
            <p>The field builds upon Julian Steward's cultural ecology and Butzer's (1982) seminal concept of "Archaeology as Human Ecology." Steward's pioneering work on cultural adaptation to environmental conditions established the foundation for understanding how core cultural features evolve in response to ecological challenges. Butzer expanded this framework by emphasizing the bidirectional relationship—framing human behavior as both responding to and actively shaping environmental processes.</p>
            
            <p>Through this ecological lens, researchers identify dynamic feedback loops that sustain or transform ecosystems over millennia. Environmental archaeology further benefits from Bronfenbrenner's Bioecological Model, particularly its nested PPCT (Process, Person, Context, Time) framework, enabling multi-scalar analysis of human–environment interactions.</p>
            
            <p>This approach moves beyond environmental determinism by recognizing the agency of prehistoric peoples who actively modified landscapes—not merely adapting to existing conditions but engineering environments to enhance resource predictability and resilience. The methodological synergy of advanced geospatial analyses, archaeobotanical studies, and evolutionary ecology enriches our understanding of past subsistence–settlement patterns and the co-evolutionary processes underlying sustainable human–environment systems.</p>
            
            <p>Environmental archaeology offers profound insights into strategies underpinning long-term human resilience and sustainability—increasingly relevant as contemporary societies face ecological challenges that echo those of the past.</p>
        </section>
        
        <section id="why-intermountain-west">
            <h2>Why the Intermountain West?</h2>
            <p>The Intermountain West serves as a natural laboratory for environmental archaeological inquiry, where ecological, cultural, and climatic complexities converge. This region's environmental heterogeneity—encompassing riparian corridors, sagebrush steppes, juniper woodlands, sub-irrigated valleys, and rugged foothills—creates a mosaic of microhabitats that historically sustained diverse subsistence strategies.</p>
            
            <p>A defining feature of this landscape is its climatic stationarity punctuated by pronounced variability, exemplified by the western North American late Holocene moisture dipole. This phenomenon created a dynamic interplay between mesic and arid zones, fostering persistent floral and faunal refugia. In mesic areas, abundant water supported stable, productive ecosystems that served as resource-rich havens, while in arid regions, drought-adapted plant and animal communities maintained resilience despite harsh conditions. These refugial zones provided prehistoric populations with reliable resources and critical fallback positions during climatic fluctuations.</p>
            
            <p>This climatic complexity drove innovative adaptive strategies among prehistoric groups. In southwestern Wyoming, hunter-gatherers exploited both mesic refugia—capitalizing on predictable plant and animal resources—and arid zones, where specialized adaptations ensured survival under resource-constrained conditions. This duality exemplifies the reciprocal relationship between environmental conditions and human agency that forms a core principle of environmental archaeology.</p>
            
            <p>The region's well-documented archaeological record, combined with its inherent ecological diversity, provides crucial insights into the co-evolutionary processes of human–environment interactions. Prehistoric communities actively managed landscapes through practices such as surplus storage, controlled burning, and selective harvesting—practices effectively captured by the Environmental Archaeology Heuristic (EAH).</p>
            
            <p>The Intermountain West, with its blend of climatic stationarity, late Holocene moisture gradients, and persistent refugial zones, offers an ideal context for advancing our understanding of sustainability, resilience, and the transformative power of cultural practices on ecological systems.</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2025 Dr. Justin "JD" Dolinar | Wasatch-Archaeo</p>
    </footer>
</body>
</html>
