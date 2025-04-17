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
    position: relative;
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
    gap: 2.5rem; /* increase this value */
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
    font-family: 'Space Mono', monospace;
    font-size: 0.7rem;
    text-transform: uppercase;
    padding: 2px 6px;
    font-weight: bold;
    border: 2px solid #000;

    /* brutalist sticker feel */
    transform: rotate(-2deg);
    box-shadow: 2px 2px 0 #000;
  }

/*   <div class="badges">
    <span class="status-badge status-live" title="Fully launched & in use">Live</span>
    <span class="status-badge status-wip" title="Work in progress">WIP</span>
    <span class="status-badge status-beta" title="Feature-complete but needs testing">Beta</span>
    <span class="status-badge status-archived" title="No longer maintained or updated">Archived</span>
    <span class="status-badge status-experimental" title="Prototypes, R&D, trying new tech">Experimental</span>
    <span class="status-badge status-v2" title="Major version update in the works">v2 Coming</span>
    <span class="status-badge status-refactor" title="Project being refactored">Refactor</span>
  </div> */

  /* Colorful variants */
  .status-live {
    background: #16a34a; /* green-600 */
    color: #fff;
  }

  .status-wip {
    background: #facc15; /* yellow-400 */
    color: #000;
  }

  .status-beta {
    background: #3b82f6; /* blue-500 */
    color: #fff;
  }

  .status-archived {
    background: #9ca3af; /* gray-400 */
    color: #fff;
  }

  .status-experimental {
    background: #a855f7; /* purple-500 */
    color: #fff;
  }

  .status-v2 {
    background: #4b5563; /* slate-600 */
    color: #fff;
  }

  .status-refactor {
    background: #f97316; /* orange-500 */
    color: #fff;
  }

  /* Type Variantes */
  .status-product {
    background: #000;
    color: #fff;
  }

  .status-tool {
    background: #f97316; /* orange */
    color: #fff;
  }

  .status-client {
    background: #0ea5e9; /* cyan */
    color: #fff;
  }

  .status-template {
    background: #eab308; /* gold */
    color: #000;
  }

  .status-open-source {
    background: #10b981; /* emerald */
    color: #fff;
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

.type-badge {
  position: absolute;
  bottom: 0.75rem;
  right: 0.75rem;
  transform: rotate(-2deg);
  padding: 0.35rem 0.75rem;
  font-family: 'Space Mono', monospace;
  font-size: 0.65rem;
  font-weight: bold;
  text-transform: uppercase;
  border-radius: 9999px; /* pill shape */
  border: 2px solid #000;
  background: #fff;
  color: #000;
  box-shadow: 2px 2px 0 #000;
  pointer-events: none;
  z-index: 10;
  white-space: nowrap;
}

/* Core Types */

.type-default {
  background: #fff;
  color: #000;
}

.type-product {
  background: #000;
  color: #fff;
}

.type-tool {
  background: #f97316; /* orange */
  color: #fff;
}

.type-client {
  background: #0ea5e9; /* cyan */
  color: #fff;
}

.type-open-source {
  background: #10b981; /* emerald */
  color: #fff;
}

.type-template {
  background: #eab308; /* gold */
  color: #000;
}

/* Tech / Experimental Types */
.type-ai {
  background: #7c3aed; /* violet */
  color: #fff;
}

.type-api {
  background: #3b82f6; /* blue */
  color: #fff;
}

.type-library {
  background: #14b8a6; /* teal */
  color: #fff;
}

.type-cli {
  background: #1f2937; /* slate */
  color: #fff;
}

.type-devops {
  background: #6b7280; /* gray */
  color: #fff;
}

/* Origin Types */
.type-hackathon {
  background: #dc2626; /* red */
  color: #fff;
}

.type-startup {
  background: #be123c; /* rose */
  color: #fff;
}

.type-university {
  background: #334155; /* dark slate */
  color: #fff;
}

.type-side-hustle {
  background: #f59e0b; /* amber */
  color: #000;
}

.type-personal {
  background: #d946ef; /* pink */
  color: #fff;
}

/* Format / Use-Case Types */
.type-landing-page {
  background: #0f172a; /* navy */
  color: #fff;
}

.type-dashboard {
  background: #15803d; /* green */
  color: #fff;
}

.type-cms {
  background: #7e22ce; /* purple */
  color: #fff;
}

.type-ecommerce {
  background: #ef4444; /* red */
  color: #fff;
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
      <a href="https://www.youtube.com/@haessbuilds" target="_blank" class="button">YouTube</a>
      <div class="cv-dropdown">
      <a href="#" class="button cv-trigger">Download CV ▾</a>
      <div class="cv-options">
        <a href="https://drive.google.com/uc?export=download&id=ENGLISH_FILE_ID">English 🇬🇧</a>
        <a href="https://drive.google.com/uc?export=download&id=SPANISH_FILE_ID">Español 🇪🇸</a>
        <a href="https://drive.google.com/uc?export=download&id=FRENCH_FILE_ID">Français 🇫🇷</a>
      </div>
    </div>
    </div>
  </section>

  <section class="projects-grid">
    {% for project in site.data.projects %}
  <div class="project-card">
    <span class="status-badge status-{{ project.status | downcase }}">{{ project.status }}</span>
    <h2 class="project-title">{{ project.title }}</h2>
    <p class="project-tagline">"{{ project.tagline }}"</p>
    <details class="project-description">
      <summary>View Description</summary>
      <p>{{ project.description }}</p>
    </details>
    <div class="tech-stack">
      {% for tech in project.tech %}
        <img src="https://cdn.simpleicons.org/{{ tech }}/000000" alt="{{ tech | capitalize }}">
      {% endfor %}
    </div>
    <div class="project-links">
      {% if project.url %}
        <a href="{{ project.url }}" class="project-link" target="_blank">🌐 View Live</a>
      {% endif %}
      {% if project.github %}
        <a href="{{ project.github }}" class="project-link" target="_blank">GitHub →</a>
      {% endif %}
    </div>
    <!-- <span class="type-badge type-{{ project.type | downcase }}">{{ project.type }}</span> -->
  </div>
{% endfor %}
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

<!-- <script>
  document.querySelectorAll('.status-badge').forEach(badge => {
    const deg = (Math.random() - 0.5) * 4; // -2 to +2 degrees
    badge.style.transform = `rotate(${deg}deg)`;
  });
</script> -->
