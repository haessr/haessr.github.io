---
layout: default
title: "About"
permalink: /about/
---

<!-- Google Fonts: Space Mono for brutalist aesthetic -->
<link href="https://fonts.googleapis.com/css2?family=Space+Mono&display=swap" rel="stylesheet">

<style>
  .about-container {
    font-family: 'Space Mono', monospace;
    background: #fff;
    color: #111;
  }

  .landing {
    text-align: center;
    margin-bottom: 4rem;
    border-bottom: 2px solid #000;
    padding-bottom: 2rem;
  }

  .button {
    display: inline-block;
    background: #000;
    color: #fff;
    padding: 0.5em 1.25em;
    text-decoration: none;
    font-weight: bold;
    text-transform: uppercase;
    margin-top: 1.5rem;
    border: 2px solid #000;
  }

  .button:hover {
    background: #fff;
    color: #000;
  }

  .portfolio-grid {
    display: grid;
    gap: 2rem;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  }

  .project-card {
    border: 2px solid #000;
    background: #fff;
    display: flex;
    flex-direction: column;
  }

.project-image {
  width: 100%;
  border-bottom: 2px solid #000;
}

.project-image img {
  width: 100%;
  height: auto;
  display: block;
}

  .project-content {
    padding: 1.25rem;
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
  }

  .project-title {
    font-size: 1.25rem;
    font-weight: bold;
    text-transform: uppercase;
    margin: 0;
  }

  .project-tagline {
    font-size: 1rem;
    font-style: italic;
    color: #555;
  }

  .project-description {
    font-size: 0.95rem;
    line-height: 1.5;
  }

  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    align-items: center;
    margin-top: 0.5rem;
  }

  .tech-stack img {
    width: 24px;
    height: 24px;
  }

  .project-content a {
    font-weight: bold;
    color: #000;
    text-decoration: underline;
    margin-top: 0.5rem;
  }

  .project-content a:hover {
    text-decoration: none;
  }

  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1.5rem;
    font-family: 'Space Mono', monospace;
  }

  .project-card {
    position: relative;
    background: #fff;
    border: 2px solid #000;
    padding: 1rem;
    transition: all 0.2s ease;
  }

  .project-card:hover {
    box-shadow: 0 0 0 2px black;
    transform: scale(1.01);
  }

  .status-badge {
    position: absolute;
    top: 0.5rem;
    right: 0.5rem;
    background: #000;
    color: #fff;
    font-size: 0.7rem;
    text-transform: uppercase;
    padding: 2px 6px;
    font-weight: bold;
  }

  .project-title {
    font-size: 1rem;
    text-transform: uppercase;
    font-weight: bold;
    margin: 0 0 0.25rem 0;
  }

  .project-tagline {
    font-size: 0.85rem;
    font-style: italic;
    color: #555;
    margin-bottom: 0.5rem;
  }

  .project-description summary {
    cursor: pointer;
    text-decoration: underline;
    font-weight: bold;
    font-size: 0.85rem;
  }

  .project-description p {
    margin: 0.5rem 0 0 0;
    font-size: 0.85rem;
    line-height: 1.4;
  }

  .tech-stack {
    display: flex;
    gap: 0.5rem;
    align-items: center;
    margin: 0.75rem 0;
  }

  .tech-stack img {
    width: 22px;
    height: 22px;
  }

  .project-link {
    font-size: 0.85rem;
    font-weight: bold;
    text-decoration: underline;
    color: #000;
  }

  .project-link:hover {
    text-decoration: none;
  }

  .landing {
    max-width: 700px;
    margin: 0 auto 4rem;
    padding: 0 1rem;
    text-align: center;
    border-bottom: 2px solid #000;
    padding-bottom: 2rem;
    font-family: 'Space Mono', monospace;
  }

  .landing-title {
    font-size: 2rem;
    text-transform: uppercase;
    font-weight: bold;
    margin-bottom: 0.5rem;
  }

  .landing-subtitle,
  .landing-tagline {
    font-size: 1rem;
    margin-bottom: 1rem;
    line-height: 1.6;
    color: #111;
  }

  .landing-points {
    text-align: left;
    margin: 0 auto 2rem;
    max-width: 600px;
    font-size: 0.9rem;
    line-height: 1.5;
  }

  .landing-links {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    justify-content: center;
  }

  .button {
    display: inline-block;
    background: #000;
    color: #fff;
    padding: 0.5em 1.25em;
    text-decoration: none;
    font-weight: bold;
    text-transform: uppercase;
    border: 2px solid #000;
    transition: all 0.2s ease;
  }

  .button:hover {
    background: #fff;
    color: #000;
  }
</style>

<div class="about-container">
  <section class="landing">
    <h1 class="landing-title">Haess Romani</h1>
    <p class="landing-subtitle" id="rotating-subtitle">
      I build things with intention. Mostly with Rails. Always with care.
    </p>
    <p class="landing-tagline">
      Living in Spain 🇪🇸 | Open to remote opportunities worldwide.
    </p>
    <div class="landing-links">
      <a href="https://www.linkedin.com/in/haessr" target="_blank" class="button">LinkedIn</a>
      <a href="https://github.com/haessr" target="_blank" class="button">GitHub</a>
      <a href="https://x.com/haessr" target="_blank" class="button">X</a>
      <a href="https://drive.google.com/uc?export=download&id=YOUR_FILE_ID" class="button">Download CV</a>
    </div>
  </section>

  <section class="projects-grid">
    <!-- Project 1 -->
    <div class="project-card">
      <span class="status-badge">Live</span>
      <h2 class="project-title">Ride Monitoring Dashboard</h2>
      <p class="project-tagline">"Move fast. Track faster."</p>
      <details class="project-description">
        <summary>View Description</summary>
        <p>Real-time dashboard for managing and dispatching drivers across LATAM. Built with Firebase, React, and Apollo.</p>
      </details>
      <div class="tech-stack">
        <img src="https://cdn.simpleicons.org/react/000000" alt="React">
        <img src="https://cdn.simpleicons.org/firebase/000000" alt="Firebase">
        <img src="https://cdn.simpleicons.org/apollographql/000000" alt="Apollo">
        <img src="https://cdn.simpleicons.org/javascript/000000" alt="JS">
      </div>
      <a href="https://github.com/haessromani/picapweb" class="project-link" target="_blank">GitHub →</a>
    </div>

    <!-- Project 2 -->
    <div class="project-card">
      <span class="status-badge">Live</span>
      <h2 class="project-title">Ponle Fecha</h2>
      <p class="project-tagline">"Plan hangouts like it’s 2025."</p>
      <details class="project-description">
        <summary>View Description</summary>
        <p>Syncs Google Calendars to help groups find common availability. Built in Rails + HOTWIRE.</p>
      </details>
      <div class="tech-stack">
        <img src="https://cdn.simpleicons.org/rubyonrails/000000" alt="Rails">
        <img src="https://cdn.simpleicons.org/googlecalendar/000000" alt="Google Calendar">
        <img src="https://cdn.simpleicons.org/hotwire/000000" alt="HOTWIRE">
        <img src="https://cdn.simpleicons.org/postgresql/000000" alt="PostgreSQL">
      </div>
      <a href="https://github.com/haessromani/ponle-fecha" class="project-link" target="_blank">GitHub →</a>
    </div>

    <!-- Project 3 -->
    <div class="project-card">
      <span class="status-badge">WIP</span>
      <h2 class="project-title">Rutea Fácil</h2>
      <p class="project-tagline">"Routing made ridiculously simple."</p>
      <details class="project-description">
        <summary>View Description</summary>
        <p>Delivery routing platform that optimizes driver routes and tracks service states live using Mapbox.</p>
      </details>
      <div class="tech-stack">
        <img src="https://cdn.simpleicons.org/rubyonrails/000000" alt="Rails">
        <img src="https://cdn.simpleicons.org/mapbox/000000" alt="Mapbox">
        <img src="https://cdn.simpleicons.org/sidekiq/000000" alt="Sidekiq">
        <img src="https://cdn.simpleicons.org/postgresql/000000" alt="PostgreSQL">
      </div>
      <a href="https://github.com/haessromani/rutea-facil" class="project-link" target="_blank">GitHub →</a>
    </div>

    <!-- Project 4 -->
    <div class="project-card">
      <span class="status-badge">WIP</span>
      <h2 class="project-title">AI Wardrobe</h2>
      <p class="project-tagline">"Look sharp. Smarter."</p>
      <details class="project-description">
        <summary>View Description</summary>
        <p>AI-based outfit generator and wardrobe manager that suggests looks from your real closet. Built with React + FastAPI.</p>
      </details>
      <div class="tech-stack">
        <img src="https://cdn.simpleicons.org/react/000000" alt="React">
        <img src="https://cdn.simpleicons.org/python/000000" alt="Python">
        <img src="https://cdn.simpleicons.org/fastapi/000000" alt="FastAPI">
        <img src="https://cdn.simpleicons.org/openai/000000" alt="OpenAI">
      </div>
      <a href="#" class="project-link" target="_blank">GitHub →</a>
    </div>
  </section>
</div>

<script>
  const phrases = [
    "I build things with intention. Mostly with Rails. Always with care.",
    "Performance-minded, product-driven, always shipping.",
    "Engineering with clarity — product thinking included."
  ];

  let index = 0;
  const subtitleEl = document.getElementById("rotating-subtitle");

  setInterval(() => {
    index = (index + 1) % phrases.length;
    subtitleEl.textContent = phrases[index];
  }, 4000);
</script>
