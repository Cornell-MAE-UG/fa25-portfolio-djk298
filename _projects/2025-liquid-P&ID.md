---
layout: project
title: Bi-Propellant Rocket Fluid Systems
description: Cornell Rocketry System Design
technologies: [Piping & Instrumentation Diagrams]
image: /assets/images/liquid-CAD.png
---

<style>
  .proj-hero {
    background: linear-gradient(135deg, #1c2340 0%, #3a3f58 100%);
    color: #fff;
    border-radius: 10px;
    padding: 2.2rem 2rem 1.8rem;
    margin-bottom: 2rem;
  }
  .proj-hero h1 {
    font-family: 'Merriweather', serif;
    font-size: 1.8rem;
    margin: 0 0 0.4rem;
    color: #fff;
  }
  .proj-hero .course-tag {
    display: inline-block;
    background: rgba(255,255,255,0.15);
    border-radius: 20px;
    padding: 0.2rem 0.8rem;
    font-size: 0.8rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    margin-bottom: 1rem;
  }
  .proj-hero p {
    margin: 0;
    line-height: 1.7;
    color: rgba(255,255,255,0.88);
    max-width: 680px;
    font-size: 0.97rem;
  }

  .section-label {
    font-family: 'Merriweather', serif;
    font-size: 0.72rem;
    text-transform: uppercase;
    letter-spacing: 0.14em;
    color: #3a3f58;
    border-left: 3px solid #3a3f58;
    padding-left: 0.6rem;
    margin: 2rem 0 0.8rem;
  }

  .highlight-box {
    background: #f0f2f8;
    border-radius: 8px;
    padding: 1.2rem 1.5rem;
    margin: 1.2rem 0;
    line-height: 1.75;
    font-size: 0.97rem;
  }

  .skill-chips {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin: 0.8rem 0 1.5rem;
  }
  .chip {
    background: #e8eaf0;
    color: #3a3f58;
    border-radius: 20px;
    padding: 0.25rem 0.85rem;
    font-size: 0.8rem;
    font-weight: 600;
    letter-spacing: 0.04em;
  }

  .responsibilities {
    margin: 0.5rem 0 1rem 1.2rem;
    padding: 0;
    line-height: 1.9;
    font-size: 0.97rem;
  }
  .responsibilities li { margin: 0.2rem 0; }

  .asset-block {
    margin: 1rem 0 2rem;
  }
  .asset-block a img {
    width: 100%;
    max-width: 720px;
    border-radius: 8px;
    box-shadow: 0 4px 16px rgba(0,0,0,0.13);
    display: block;
    transition: box-shadow 0.2s, transform 0.2s;
  }
  .asset-block a img:hover {
    box-shadow: 0 8px 28px rgba(0,0,0,0.2);
    transform: translateY(-2px);
  }
  .asset-caption {
    font-size: 0.82rem;
    color: #777;
    margin-top: 0.5rem;
    font-style: italic;
  }

  .download-btn {
    display: inline-block;
    margin-top: 0.8rem;
    padding: 0.55rem 1.2rem;
    background: #3a3f58;
    color: #fff;
    border-radius: 6px;
    font-size: 0.88rem;
    font-weight: 600;
    text-decoration: none;
    letter-spacing: 0.03em;
    transition: background 0.2s;
  }
  .download-btn:hover { background: #5a6080; }
</style>

<a class="back-arrow" href="{{ "/projects/" | relative_url }}">← Back to Projects</a>

<div class="proj-hero">
  <span class="course-tag">Cornell Rocketry — 2025–2026</span>
  <h1>Bi-Propellant Rocket Fluid Systems</h1>
  <p>Designing the system architecture for the fluid systems of Cornell Rocketry's first-ever bipropellant liquid rocket engine — from trade studies to final P&amp;ID.</p>
</div>

<p class="section-label">Skills & Concepts</p>
<div class="skill-chips">
  <span class="chip">P&amp;ID Design</span>
  <span class="chip">Trade Studies</span>
  <span class="chip">Fluid Systems Architecture</span>
  <span class="chip">Component Sourcing</span>
  <span class="chip">Safety Procedures</span>
  <span class="chip">Rocket Propulsion</span>
</div>

<p class="section-label">Project Overview</p>
<div class="highlight-box">
  This project centers on designing the full fluid system architecture for Cornell Rocketry's first bipropellant liquid rocket engine. I am responsible for taking the system from concept to a complete, safety-reviewed design.
</div>

<p class="section-label">Responsibilities</p>
<ul class="responsibilities">
  <li>Conducting trade studies to select fuel and oxidizer</li>
  <li>Determining required valves, sensors, and instrumentation</li>
  <li>Sourcing physical components and verifying compatibility</li>
  <li>Calculating fluid line lengths and pressure drops</li>
  <li>Creating testing and safety procedures</li>
  <li>Assembling the final piping &amp; instrumentation diagram (P&amp;ID)</li>
</ul>

<p class="section-label">Piping & Instrumentation Diagram</p>
<div class="asset-block">
  <a href="{{ "/assets/images/liquid-diagram.png" | relative_url }}" target="_blank">
    <img
      src="{{ "/assets/images/liquid-diagram.png" | relative_url }}"
      alt="High-level P&ID for bipropellant liquid rocket fluid systems"
    />
  </a>
  <p class="asset-caption">High-level P&amp;ID for the bipropellant liquid rocket fluid systems — click to view full size</p>
</div>

<p class="section-label">System Tech Report</p>
<div class="asset-block">
  <a href="{{ "/assets/TechReport.pdf" | relative_url }}" target="_blank">
    <img
      src="{{ "/assets/images/TechReport-preview.png" | relative_url }}"
      alt="Tech Report preview"
    />
  </a>
  <p class="asset-caption">Full system tech report — click to open PDF</p>
  <a class="download-btn" href="{{ "/assets/TechReport.pdf" | relative_url }}" download>⬇ Download Tech Report (PDF)</a>
</div>