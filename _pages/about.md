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
</style>

<div class="about-container">
  <section class="landing">
    <h1>🧱 Haess Romani</h1>
    <p>Fullstack dev & photographer. I build fast, functional & raw digital tools. Here’s some of my work.</p>
    <a href="https://drive.google.com/uc?export=download&id=YOUR_FILE_ID" class="button">Download My CV</a>
  </section>

  <section class="portfolio-grid">
    <!-- Project 1 -->
    <div class="project-card">
      <img src="https://placehold.co/800x400" alt="Picap Dashboard">
      <div class="project-content">
        <h2 class="project-title">🚕 Picap Admin Dashboard</h2>
        <p class="project-tagline">"Move fast. Track faster."</p>
        <p class="project-description">A web-based dashboard for managing and dispatching drivers in real-time across LATAM cities.</p>
        <div class="tech-stack">
          <img src="https://cdn.simpleicons.org/react/000000" alt="React">
          <img src="https://cdn.simpleicons.org/firebase/000000" alt="Firebase">
          <img src="https://cdn.simpleicons.org/apollographql/000000" alt="Apollo">
          <img src="https://cdn.simpleicons.org/javascript/000000" alt="JavaScript">
        </div>
        <a href="https://github.com/haessromani/picapweb" target="_blank">GitHub →</a>
      </div>
    </div>

    <!-- Project 2 -->
    <div class="project-card">
      <img src="https://placehold.co/800x400" alt="Ponle Fecha App">
      <div class="project-content">
        <h2 class="project-title">📅 Ponle Fecha</h2>
        <p class="project-tagline">"Plan hangouts like it’s 2025."</p>
        <p class="project-description">A smart calendar coordination tool that syncs availability across friend groups using Google Calendar.</p>
        <div class="tech-stack">
          <img src="https://cdn.simpleicons.org/rubyonrails/000000" alt="Rails">
          <img src="https://cdn.simpleicons.org/googlecalendar/000000" alt="Google Calendar">
          <img src="https://cdn.simpleicons.org/hotwire/000000" alt="HOTWIRE">
          <img src="https://cdn.simpleicons.org/postgresql/000000" alt="PostgreSQL">
        </div>
        <a href="https://github.com/haessromani/ponle-fecha" target="_blank">GitHub →</a>
      </div>
    </div>

    <!-- Project 3 -->
    <div class="project-card">
      <img src="https://placehold.co/800x400" alt="Rutea Fácil">
      <div class="project-content">
        <h2 class="project-title">🚚 Rutea Fácil</h2>
        <p class="project-tagline">"Routing made ridiculously simple."</p>
        <p class="project-description">A platform to help delivery drivers generate optimal routes and track live service states using Mapbox.</p>
        <div class="tech-stack">
          <img src="https://cdn.simpleicons.org/rubyonrails/000000" alt="Rails">
          <img src="https://cdn.simpleicons.org/mapbox/000000" alt="Mapbox">
          <img src="https://cdn.simpleicons.org/sidekiq/000000" alt="Sidekiq">
          <img src="https://cdn.simpleicons.org/postgresql/000000" alt="PostgreSQL">
        </div>
        <a href="https://github.com/haessromani/rutea-facil" target="_blank">GitHub →</a>
      </div>
    </div>
  </section>
</div>
