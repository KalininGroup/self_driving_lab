---
layout: page
title: Self-Driving Lab
menu_title: Home
menu_icon: house-door
---

<style>
  
.section-card {
  background: #fafbfd;
  border: 1px solid #e8ecf3;
  border-radius: 14px;
  padding: 20px 24px;
  margin: 40px auto;
  box-shadow: 0 1px 2px rgba(16,24,40,.04);
  max-width: 900px;
}
  .section-title {
  text-align: center;
  margin-bottom: 18px;
  font-size: 1.4rem;
  font-weight: 700;
  color: #1d2a56;
}

/* Grids for different sections */
.section-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 22px;
  margin: 20px auto 40px;
  max-width: 900px;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 15px;
  margin: 20px auto 40px;
  max-width: 900px;
}

.two-col-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
}

.project-card {
  background: #fafbfd;
  border: 1px solid #e8ecf3;
  border-radius: 14px;
  padding: 18px 14px;
  text-align: center;
  box-shadow: 0 1px 2px rgba(16,24,40,.04);
  height: 100%;
}

.project-card img {
  max-width: 120px;
  max-height: 80px;
  width: auto;
  height: auto;
  margin-top: 10px;
  object-fit: contain;
  opacity: 0.95;
}

.project-card p {
  margin: 10px 0 0 0;
  font-size: 0.95rem;
  font-weight: 500;
  color: #333;
}

.project-card h3 {
  margin: 0;
  font-size: 1.1rem;
  font-weight: 700;
  color: #1d2a56;
}

/* Template Card Styling */
.template-card {
  border: 2px dashed #bdc3c7;
  background-color: #f8f9fa;
  opacity: 0.7;
}
 
  .utk-float-btn {
    position: fixed;
    bottom: 40px;
    right: 20px;
    background: rgba(29, 29, 29, 0.75); 
    backdrop-filter: blur(8px);
    -webkit-backdrop-filter: blur(8px);
    color: #ffffff !important; 
    padding: 10px 18px;
    border-radius: 10px;
    font-weight: 600;
    text-decoration: none;
    box-shadow: 0 4px 12px rgba(0,0,0,0.25);
    z-index: 999;
    transition: transform 0.2s ease;
  }
  
  .utk-float-btn:hover {
    transform: translateY(-2px);
  }

  /* Mobile scaling */
@media (max-width: 700px) {
  .section-grid, .projects-grid, .two-col-grid {
    grid-template-columns: 1fr;
  }
  .project-card img {
    max-width: 110px;
    max-height: 70px;
  }
}
  
</style>


<div class="section-card">
  <h2 class="section-title">Primary Goals</h2>
  <p style="text-align: center; margin: 0; color: #333;">Accelerating scientific discovery by transitioning from human-speed microscopy to autonomous operations. We harness large language models and machine learning to uncover structure-property relationships and close the loop on material synthesis and characterization.
  </p>
</div>

<h2 class="section-title">ML & AE</h2>
<div class="section-card">
  <div class="section-grid">
    <div class="project-card">
      <p><strong>Agentic</strong></p>
    </div>
    <div class="project-card">
      <p><strong>Optimization</strong></p>      
    </div>
    <div class="project-card">
      <h3>Hackathon</h3>
      <p>Upcoming events</p>      
      <p><strong>Other</strong></p>
    </div>
  </div>
</div>

<div class="section-grid">
  
  <div class="project-card" style="padding: 0;">
    <a href="ahmadi-lab.html" style="display: block; padding: 18px 14px; text-decoration: none; color: inherit; height: 100%;">
      <h3>AHMADI Research Lab</h3>
      <p style="margin-bottom: 8px;"><em><strong>A</strong>ccelerating <strong>H</strong>ybrid <strong>M</strong>aterials by <strong>A</strong>utomated <strong>D</strong>iscovery <strong>I</strong>nnovation.</em></p>
      <p style="margin-top: 0;">Pioneering AI-driven automated synthesis and high-throughput workflows to solve global renewable energy and optoelectronic challenges.</p>
    </a>
  </div>
  
  <div class="project-card" style="padding: 0;">
    <a href="cmp.html" style="display: block; padding: 18px 14px; text-decoration: none; color: inherit; height: 100%;">
      <h3>Center for Materials Processing</h3>
      <p style="margin-bottom: 8px;"><em>Directed by Philip Rack</em></p>
      <p style="margin-top: 0;">Fostering interdisciplinary research in materials processing to drive new product development, solve performance challenges, and improve industrial competitiveness.</p>
    </a>
  </div>
  
  <div class="project-card">
    <h3>Nanoindentation<br>Dayakar Penumadu Lab</h3>
    <p> </p>
  </div>
  
</div>


<h2 class="section-title" style="padding-top: 40px;">Techniques & Workflows</h2>
<div class="projects-grid">

  <div class="project-card" style="padding: 0;">
    <a href="ae-spm.html" style="display: block; padding: 18px 14px; text-decoration: none; color: inherit; height: 100%;">
      <h3>AE SPM</h3>
      <p>Pioneering intelligent SPM workflows to unravel complex material behaviors, accelerating the pace of discovery and enabling transformative advances across diverse fields.</p>
    </a>
  </div>

  <div class="project-card" style="padding: 0;">
    <a href="ae-stem.html" style="display: block; padding: 18px 14px; text-decoration: none; color: inherit; height: 100%;">
      <h3>AE STEM</h3>
      <p>Developing cutting-edge automated STEM methodologies that leverage machine learning algorithms and autonomous agents for real-time decision-making and adaptive experimentation.</p>
    </a>
  </div>
  
  <div class="project-card" style="padding: 0;">
    <a href="fabrication.html" style="display: block; padding: 18px 14px; text-decoration: none; color: inherit; height: 100%;">
      <h3>Fabrication / Synthesis</h3>
      <p style="font-style: italic; color: #555; font-size: 0.9rem; margin: 10px 0 6px 0;">
        "What I cannot make, I cannot understand."<br>
        <span style="font-size: 0.8rem; font-style: normal; color: #CC6600; font-weight: 600;">— Richard Feynman</span>
      </p>
      <p style="margin-top: 0;">Leveraging ML to move from passive observation to active, high-throughput materials discovery and autonomous atomic-scale manufacturing.</p>
    </a>
  </div>
  <div class="project-card template-card">
    <h3>Xray</h3>
    <p><em>Currently in development.</em></p>
  </div>
</div>

<!-- <a href="#" class="utk-float-btn">Contact Lab</a> -->
