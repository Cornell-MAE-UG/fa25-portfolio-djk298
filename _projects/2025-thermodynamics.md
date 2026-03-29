---
layout: project
title: Thermodynamic System Analysis
description: Applying Thermodynamic Concepts to Niagara Falls
technologies: [Thermodynamics]
image: /assets/images/thermo/thermo-7.png
---

<style>
  .proj-hero {
    background: linear-gradient(135deg, #2a4858 0%, #3a6070 100%);
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
  .proj-hero .authors {
    margin-top: 0.8rem;
    font-size: 0.85rem;
    color: rgba(255,255,255,0.65);
    font-style: italic;
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

  .image-grid-2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin: 1rem 0 2rem;
  }
  .image-grid-2 img {
    width: 100%;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.11);
    display: block;
  }
  .image-single {
    margin: 1rem 0 2rem;
  }
  .image-single img {
    width: 100%;
    max-width: 600px;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.11);
    display: block;
  }
  .img-caption {
    font-size: 0.82rem;
    color: #777;
    margin-top: 0.5rem;
    font-style: italic;
  }

  .equation-block {
    background: #1e2235;
    color: #e8eaf0;
    border-radius: 8px;
    padding: 1.4rem 1.8rem;
    margin: 1rem 0 2rem;
    overflow-x: auto;
  }
  .equation-block p {
    margin: 0.5rem 0;
    font-family: 'Courier New', monospace;
    font-size: 0.95rem;
    line-height: 1.8;
    color: #c8d0f0;
  }
  .equation-block .eq-result {
    color: #a8d8a8;
    font-weight: bold;
  }

  .result-card {
    display: inline-block;
    background: #3a3f58;
    color: #fff;
    border-radius: 8px;
    padding: 1rem 1.5rem;
    margin: 0.5rem 0 1.5rem;
    font-family: 'Merriweather', serif;
  }
  .result-card .result-number {
    font-size: 2rem;
    font-weight: 700;
    display: block;
    line-height: 1.2;
  }
  .result-card .result-label {
    font-size: 0.8rem;
    opacity: 0.75;
    letter-spacing: 0.05em;
  }

  .refs { font-size: 0.85rem; line-height: 2; }
  .refs a { color: #3a3f58; }
</style>

<a class="back-arrow" href="{{ "/projects/" | relative_url }}">← Back to Projects</a>

<div class="proj-hero">
  <span class="course-tag">ENGRD 2210 — Thermodynamics</span>
  <h1>Niagara Falls — Rankine Generation Station</h1>
  <p>Applying thermodynamic energy balance and efficiency analysis to a historical hydroelectric power station.</p>
  <p class="authors">Isaac Kahn · Bridget McAvoy · Deepti Kousik</p>
</div>

<p class="section-label">Skills & Concepts</p>
<div class="skill-chips">
  <span class="chip">Thermodynamics</span>
  <span class="chip">Energy Balance</span>
  <span class="chip">Efficiency Analysis</span>
  <span class="chip">Francis Turbines</span>
  <span class="chip">Hydroelectric Power</span>
</div>

<p class="section-label">Chosen System</p>
<div class="highlight-box">
  The <strong>Rankine Generating Station</strong> (1901–2005) was a hydroelectric facility on the Canadian side of Niagara Falls, built by the Canadian Niagara Power Company. Named after its founder William Birch Rankine — and notably <em>not</em> employing a Rankine Cycle — it generated power from the gravitational potential energy of the Niagara River, delivering electricity to the surrounding region for over a century through eleven Francis turbines with a combined output of <strong>76.4 MW</strong>.
</div>

<p class="section-label">Station Photographs</p>
<div class="image-grid-2">
  <img src="{{ "/assets/images/thermo/thermo-1.png" | relative_url }}" alt="Niagara Falls Power Station exterior" />
  <img src="{{ "/assets/images/thermo/thermo-2.png" | relative_url }}" alt="Turbine diagram" />
  <img src="{{ "/assets/images/thermo/thermo-3.png" | relative_url }}" alt="Interior of Power Station" />
  <img src="{{ "/assets/images/thermo/thermo-4.png" | relative_url }}" alt="Historical Power Station view" />
</div>

<p class="section-label">Qualitative Description</p>
<div class="highlight-box">
  Water from the Niagara River was diverted into a forebay, then channeled through penstocks into eleven Francis turbines. Francis turbines are radial-flow machines optimized for high-pressure, low-flow-rate applications. For this analysis, changes in kinetic energy and enthalpy from the top of the penstock to the turbine outlet were assumed negligible. Mass flow rate, height change, and output power were sourced from historical records to calculate station efficiency.
  <br><br>
  The station closed in 2005 due to its generators outputting 25 Hz AC current (vs. the modern US standard of 60 Hz) and turbine shaft misalignment over time.
</div>

<p class="section-label">System Diagrams</p>
<div class="image-single">
  <img src="{{ "/assets/images/thermo/thermo-5.png" | relative_url }}" alt="Overall system diagram of the generation station" />
  <p class="img-caption">Overall diagram of the Rankine Generation Station</p>
</div>
<div class="image-grid-2">
  <div>
    <img src="{{ "/assets/images/thermo/thermo-6.png" | relative_url }}" alt="Turbine schematic" />
    <p class="img-caption">Turbine schematic for analysis</p>
  </div>
  <div>
    <img src="{{ "/assets/images/thermo/thermo-7.png" | relative_url }}" alt="Flow path visualization" />
    <p class="img-caption">Flow path visualization</p>
  </div>
</div>

<p class="section-label">Physical Equations & Analysis</p>

<div class="equation-block">
  <p>Mass balance:&nbsp;&nbsp; ṁ_in = ṁ_out</p>
  <p>Energy balance:&nbsp;&nbsp; Ė_CV = 0 = −Ẇ_shaft + ṁ [ (v_in² − v_out²)/2 + (h_in − h_out) + g(z_in − z_out) ]</p>
  <p>Simplified (KE &amp; Δh negligible):&nbsp;&nbsp; Ẇ_shaft = ṁ · g · (z_in − z_out)</p>
  <p>Ẇ_shaft = (0.1 × 1600 m³/s × 1000 kg/m³) × (9.81 m/s²) × (54.9 m) = <span class="eq-result">86.2 MW</span></p>
  <p>η = W_act / W_shaft = 76.4 / 86.2 = <span class="eq-result">88.7%</span></p>
</div>

<div>
  <span class="result-card">
    <span class="result-number">88.7%</span>
    <span class="result-label">Turbine Efficiency</span>
  </span>
  &nbsp;&nbsp;
  <span class="result-card">
    <span class="result-number">76.4 MW</span>
    <span class="result-label">Actual Power Output</span>
  </span>
</div>

<p class="section-label">Changes to Operating Conditions</p>
<div class="highlight-box">
  Several modifications could increase power output: raising the forebay water level, optimizing penstock intake gates, or lowering the turbine pit — each increasing the effective head and extracting more energy per unit of water. However, these changes also raise mechanical stress, risk of cavitation, and potential for system failure.
  <br><br>
  Turbines also have optimal flow ranges; operating outside them increases hydraulic losses. Refurbishing turbine blades to reduce turbulence — and improving flow conditions in the penstocks and forebay — would raise overall efficiency without changing head geometry.
</div>

<p class="section-label">References</p>
<div class="refs">
  [1] <a href="http://spiff.rit.edu/classes/phys213/lectures/niagara/niagara.html" target="_blank">RIT Physics — Niagara Falls Lecture</a><br>
  [2] <a href="http://www.niagarafrontier.com/power.html" target="_blank">Niagara Frontier — Power History</a><br>
  [3] <a href="https://freaktography.com/canadian-niagara-power-station-and-tailrace-urban-exploring/" target="_blank">Freaktography — Canadian Niagara Power Station</a><br>
  [4] <a href="https://www.croatianhistory.net/etf/teslan.html" target="_blank">Croatian History — Tesla &amp; Niagara</a><br>
  [5] <a href="https://vividcomm.com/2025/08/14/niagara-parks-power-station-history-technology-and-legacy/" target="_blank">Vivid Comm — Niagara Parks Power Station Legacy</a>
</div>