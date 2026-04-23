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
  text-align: left;
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

<!-- Header -->
<div class="section-card">
  <h2 class="section-title">Primary Goals</h2>
  <p style="text-align: center; margin: 0; color: #333;">Accelerating scientific discovery by transitioning from human-speed microscopy to autonomous operations. We harness large language models and machine learning to uncover structure-property relationships and close the loop on material synthesis and characterization.
  </p>
</div>

<!-- ML and AE -->
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


<!-- Labs -->
<div class="section-grid">
  
  <div class="project-card" style="padding: 0;">
    <a href="https://ahmadiresearch.utk.edu/" style="display: block; padding: 18px 14px; text-decoration: none; color: inherit; height: 100%;">
      <h3>AHMADI Research Lab</h3>
      <p style="margin-bottom: 8px;"><em><strong>A</strong>ccelerating <strong>H</strong>ybrid <strong>M</strong>aterials by <strong>A</strong>utomated <strong>D</strong>iscovery <strong>I</strong>nnovation.</em></p>
      <p style="margin-top: 0;">Pioneering AI-driven automated synthesis and high-throughput workflows to solve global renewable energy and optoelectronic challenges.</p>
    </a>
  </div>
  
  <div class="project-card" style="padding: 0;">
    <a href="https://cmp.utk.edu/" style="display: block; padding: 18px 14px; text-decoration: none; color: inherit; height: 100%;">
      <h3>Center for Materials Processing</h3>
      <p style="margin-bottom: 8px;"><em>Directed by Philip Rack</em></p>
      <p style="margin-top: 0;">Fostering interdisciplinary research in materials processing to drive new product development, solve performance challenges, and improve industrial competitiveness.</p>
    </a>
  </div>

  <div class="project-card" style="padding: 0;">
    <div style="display: block; padding: 18px 14px; height: 100%; box-sizing: border-box;">
      <h3>Nanoindentation<br>Dayakar Penumadu Lab</h3>
      <p style="margin-top: 0;"> </p>
    </div>
  </div>
  
</div>

<!-- Workflows -->
<h2 class="section-title" style="padding-top: 40px;">Techniques & Workflows</h2>

<div class="projects-grid interactive-grid">
  
  <div class="project-card expandable-card">
    <div class="card-header">
      <h3>AE SPM</h3>
    </div>
    <div class="card-body">
      <p>Pioneering intelligent SPM workflows to unravel complex material behaviors, accelerating the pace of discovery and enabling transformative advances across diverse fields.</p>      
      <div class="expanded-content">
        <video width="100%" controls muted loop>
          <source src="assets/videos/aespm-demo.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <a href="ae-spm.html" class="btn" style="margin-top: 15px;">Read Full Page</a>
      </div>
    </div>
  </div>

  <div class="project-card expandable-card">
    <div class="card-header">
      <h3>AE STEM</h3>
    </div>
    <div class="card-body">
      <p>Developing cutting-edge automated STEM methodologies that leverage machine learning algorithms and autonomous agents for real-time decision-making and adaptive experimentation.</p>      
      <div class="expanded-content">
        <video width="100%" controls muted loop>
          <source src="assets/videos/aestem-demo.mp4" type="video/mp4">
        </video>
        <a href="ae-stem.html" class="btn" style="margin-top: 15px;">Read Full Page</a>
      </div>
    </div>
  </div>

  <div class="project-card expandable-card">
    <div class="card-header">
      <h3>Fabrication / Synthesis</h3>
    </div>
    <div class="card-body">
      <p style="font-style: italic; color: #555; font-size: 0.9rem; margin: 10px 0 6px 0;">
        "What I cannot make, I cannot understand."
        <span style="display: block; text-align: right; font-size: 0.8rem; font-style: normal; color: #CC6600; font-weight: 600; margin-top: 4px;">— Richard Feynman</span>
      </p>
      <p style="margin-top: 0;">Leveraging ML to move from passive observation to active, high-throughput materials discovery and autonomous atomic-scale manufacturing.</p>      
      <div class="expanded-content">
        <video width="100%" controls muted loop>
          <source src="assets/videos/fab-demo.mp4" type="video/mp4">
        </video>
        <a href="fabrication.html" class="btn" style="margin-top: 15px;">Read Full Page</a>
      </div>
    </div>
  </div>

  <div class="project-card expandable-card template-card">
    <div class="card-header">
      <h3>Xray</h3>
    </div>
    <div class="card-body">
      <p style="margin-top: 0;"><em>Currently in development.</em></p>
      <div class="expanded-content">
        <p>Future video and content will go here.</p>
      </div>
    </div>
  </div>

</div>


<!-- <a href="#" class="utk-float-btn">Contact Lab</a> -->


<script>
document.addEventListener('DOMContentLoaded', () => {
    const grids = document.querySelectorAll('.interactive-grid');

    grids.forEach(grid => {
        const cards = grid.querySelectorAll('.expandable-card');

        cards.forEach(card => {
            card.addEventListener('click', (e) => {
                // If they click a video controls or the "Read More" button, don't collapse the card
                if(e.target.tagName === 'VIDEO' || e.target.tagName === 'A') return;

                const isCurrentlyExpanded = card.classList.contains('is-expanded');

                // Step 1: Close all cards and pause their videos
                cards.forEach(c => {
                    c.classList.remove('is-expanded');
                    const vid = c.querySelector('video');
                    if(vid) vid.pause(); // Stop video if user clicks away
                });

                // Step 2: If the clicked card wasn't already open, open it!
                if (!isCurrentlyExpanded) {
                    card.classList.add('is-expanded');
                    grid.classList.add('is-active'); // Tells the grid to collapse the others
                    
                    // Optional: Auto-play the video when opened
                    const vid = card.querySelector('video');
                    if(vid) vid.play(); 
                } else {
                    // If they clicked the already-open card, reset the grid back to normal
                    grid.classList.remove('is-active');
                }
            });
        });
    });
});
</script>
