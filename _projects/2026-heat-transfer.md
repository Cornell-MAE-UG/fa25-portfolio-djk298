---
layout: project
title: Heat Transfer Analysis
description: Analyzing Heat Transfer Modes
technologies: [Thermal Analysis]
image: /assets/images/heat-transfer.png
---

<style>
  .proj-hero {
    background: linear-gradient(135deg, #5a3030 0%, #3a3f58 100%);
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

  .mode-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
    margin: 1rem 0 2rem;
  }
  .mode-card {
    background: #fff;
    border: 1px solid #dde0ea;
    border-radius: 8px;
    padding: 1.1rem 1rem;
    text-align: center;
  }
  .mode-card .mode-icon {
    font-size: 1.8rem;
    display: block;
    margin-bottom: 0.5rem;
  }
  .mode-card h4 {
    font-family: 'Merriweather', serif;
    font-size: 0.88rem;
    color: #3a3f58;
    margin: 0 0 0.4rem;
  }
  .mode-card p {
    font-size: 0.82rem;
    color: #555;
    margin: 0;
    line-height: 1.5;
  }

  .problem-block {
    border-left: 3px solid #3a3f58;
    padding-left: 1.1rem;
    margin: 1rem 0 1.5rem;
  }
  .problem-block h4 {
    font-family: 'Merriweather', serif;
    font-size: 0.95rem;
    color: #3a3f58;
    margin: 0 0 0.4rem;
  }
  .problem-block p {
    margin: 0;
    font-size: 0.95rem;
    line-height: 1.75;
    color: #333;
  }

  .download-btn {
    display: inline-block;
    margin-top: 1rem;
    padding: 0.6rem 1.3rem;
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

  @media (max-width: 600px) {
    .mode-grid { grid-template-columns: 1fr; }
  }
</style>

<a class="back-arrow" href="{{ "/projects/" | relative_url }}">← Back to Projects</a>

<div class="proj-hero">
  <span class="course-tag">MAE / ENGRD — Heat Transfer</span>
  <h1>Heat Transfer Analysis</h1>
  <p>Analyzing the three fundamental modes of heat transfer — conduction, convection, and radiation — through applied engineering problems in spacecraft, electronics, and building systems.</p>
</div>

<p class="section-label">Skills & Concepts</p>
<div class="skill-chips">
  <span class="chip">Conduction</span>
  <span class="chip">Convection</span>
  <span class="chip">Radiation</span>
  <span class="chip">Thermal Modeling</span>
  <span class="chip">Electronics Cooling</span>
  <span class="chip">Spacecraft Thermal Protection</span>
</div>

<p class="section-label">Heat Transfer Modes</p>
<div class="mode-grid">
  <div class="mode-card">
    <span class="mode-icon">🔥</span>
    <h4>Conduction</h4>
    <p>Heat transfer through direct contact within a solid medium.</p>
  </div>
  <div class="mode-card">
    <span class="mode-icon">💨</span>
    <h4>Convection</h4>
    <p>Heat transfer via fluid motion — dominant in atmospheric and cooling applications.</p>
  </div>
  <div class="mode-card">
    <span class="mode-icon">☀️</span>
    <h4>Radiation</h4>
    <p>Heat transfer through electromagnetic waves — the only mode effective in a vacuum.</p>
  </div>
</div>

<p class="section-label">Problems Analyzed</p>

<div class="problem-block">
  <h4>Problem 1 — Spacecraft Thermal Environment</h4>
  <p>
    In the vacuum of space, radiation is the dominant heat transfer mode — there is no fluid medium
    for convection and no contact for conduction. During atmospheric reentry, high-speed airflow
    around the vehicle makes convection the primary mechanism. This problem required analyzing how
    the dominant transfer mode shifts with the spacecraft's environment.
  </p>
</div>

<div class="problem-block">
  <h4>Problem 2 — Silicon Chip Cooling</h4>
  <p>
    A silicon chip with insulated sides and back was modeled to show how conduction within the solid
    and convection at the surface boundary interact. Heat must travel through the chip material before
    being removed by the surrounding coolant — a configuration directly applicable to electronics
    cooling system design.
  </p>
</div>

<div class="problem-block">
  <h4>Problem 3 — Rooftop Heat Transfer</h4>
  <p>
    This problem combined convection and radiation to model heat transfer in a realistic outdoor
    scenario. Applying both modes simultaneously reinforced how they interact and must be considered
    together in real engineering analyses such as building thermal design.
  </p>
</div>

<p class="section-label">Reflection</p>
<div class="highlight-box">
  This assignment reinforced how the importance of each heat transfer mode changes dramatically with
  physical environment. The spacecraft problem highlighted radiation's dominance in vacuum conditions,
  while the silicon chip problem demonstrated how conduction and convection work together at solid–fluid
  boundaries. These concepts are directly applicable to electronics cooling, spacecraft thermal
  protection, and broader thermal system design.
</div>

<p class="section-label">Full Assignment</p>
<a class="download-btn" href="{{ "/assets/ht-problem-set-1.pdf" | relative_url }}" target="_blank">⬇ Download Assignment PDF</a>