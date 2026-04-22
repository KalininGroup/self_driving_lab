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
  <p style="text-align: center; margin: 0; color: #333;">To automate and optimize material synthesis and characterization pipelines using machine learning and agentic workflows.</p>
</div>

<div class="section-card">
  <div class="two-col-grid">
    <div class="project-card">
      <h3>ML & AE</h3>
      <p><strong>Agentic</strong></p>
      <p><strong>Optimization</strong></p>
      <p><strong>Other Models</strong></p>
    </div>
    <div class="project-card">
      <h3>Hackathon</h3>
      <p>Upcoming events and rapid prototyping results.</p>
    </div>
  </div>
</div>

<h2 class="section-title" style="margin-top: 40px;">Partner Labs</h2>
<div class="section-grid">
  <div class="project-card">
    <h3>AHMADI Lab</h3>
    <p>Focusing on advanced microscopy automation and autonomous data acquisition.</p>
  </div>
  <div class="project-card">
    <h3>Philip Rack Lab</h3>
    <p>Nanofabrication, focused electron beam induced processing, and material characterization.</p>
  </div>
  <div class="project-card">
    <h3>Nanoindentation<br>(Dayakar Lab)</h3>
    <p>High-throughput mechanical testing and autonomous property mapping.</p>
  </div>
</div>

<h2 class="section-title">Techniques & Workflows</h2>
<div class="projects-grid">
  <div class="project-card">
    <h3>AE SPM</h3>
    <p>Automated scanning probe microscopy and KPFM surface potential workflows.</p>
  </div>
  <div class="project-card">
    <h3>AE STEM</h3>
    <p>Transmission electron microscopy automation, HAADF mode physics, and spectral analysis.</p>
  </div>
  <div class="project-card">
    <h3>Fabrication / Synthesis</h3>
    <p>Closed-loop material synthesis and experimental validation.</p>
  </div>
  <div class="project-card template-card">
    <h3>Xray</h3>
    <p><em>Template for future project integration. Currently in development.</em></p>
  </div>
</div>

<!-- <a href="#" class="utk-float-btn">Contact Lab</a> -->
