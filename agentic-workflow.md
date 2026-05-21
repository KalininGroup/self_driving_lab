---
layout: page
title: Agentic Workflows
menu_title: Agentic Workflows
permalink: /agentic-workflow/
---

<div style="max-width: 1050px; margin: 0 auto 50px auto; line-height: 1.8; color: #333; font-size: 1.05rem; text-align: justify;">
  <h2 class="section-title" style="margin-top: 10px; text-align: center;">Bridging Human Intent and Hardware</h2>
  <p style="margin: 0;">
    The core of our autonomous framework relies on <strong>Agentic Workflows</strong>—utilizing Large Language Models (LLMs) as cognitive agents to manage complex scientific tasks. Rather than relying on rigid, pre-programmed scripts, we deploy agents capable of parsing high-level user goals, reasoning through experimental parameters, and seamlessly orchestrating machine-specific instruments in real-time. By acting as the "brain" of the laboratory, these agents enable dynamic, closed-loop discovery across scanning probe microscopy, electron microscopy, and combinatorial synthesis.
  </p>
</div>

<div class="section-card" style="margin-bottom: 40px; text-align: left;">
  
  <div style="border-bottom: 1px solid #e8ecf3; padding-bottom: 12px; margin-bottom: 20px;">
    <h3 style="margin-top: 0; margin-bottom: 8px; color: #1d2a56;">LLM agent controlled STEM</h3>
    <p style="margin: 0; font-size: 0.95rem; color: #555;">
      <i class="bi bi-people-fill" style="color: #CC6600;"></i> <strong style="color: #333;">Contributors:</strong> Dominick Pelaia, Levi Dunn, Austin Houston, Utkarsh Pratiush, Gerd Duscher, Sergei Kalinin
    </p>
  </div>
  
  <p style="margin-bottom: 25px; color: #333; line-height: 1.6;">
    We built a custom LLM agent called "Angstrom" to autonomously operate the STEM. It is able to write its own code to move the stage, acquire HAADF images and EDS spectra, and perform other functions.
  </p>
  
  <iframe class="embedded-video" src="https://drive.google.com/file/d/1WoQVENSBbsmUW-ZAZBmHUy-76Cc4mE14/preview" allowfullscreen style="display: block; margin: 0 auto; width: 100%; max-width: 1000px; aspect-ratio: 16 / 9; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.15);"></iframe>

</div>


<div class="section-card" style="margin-bottom: 40px; text-align: left;">
  
  <div style="border-bottom: 1px solid #e8ecf3; padding-bottom: 12px; margin-bottom: 20px;">
    <h3 style="margin-top: 0; margin-bottom: 8px; color: #1d2a56;">AtomGPT</h3>
    <p style="margin: 0; font-size: 0.95rem; color: #555;">
      <i class="bi bi-people-fill" style="color: #CC6600;"></i> <strong style="color: #333;">Contributors:</strong> Utkarsh Pratiush, Austin Houston
    </p>
  </div>
  
  <p style="margin-bottom: 25px; color: #333; line-height: 1.6;">
    A demonstration of AtomGPT seamlessly translating raw HAADF images directly into structured atomic data. See how this LLM-driven agent automates the extraction of atomic positions to predict complex supercell structures in real-time.
  </p>
  
  <iframe class="embedded-video" src="https://drive.google.com/file/d/1z0dKXQOEiiIL2afbzvJEw8Vzt1CyRyGM/preview" allowfullscreen style="display: block; margin: 0 auto; width: 100%; max-width: 1000px; aspect-ratio: 16 / 9; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.15);"></iframe>

</div>


<!-- literature discovery agent -->
<div class="section-card" style="margin-bottom: 40px; margin-top: 20px; text-align: left;">
  
  <div style="border-bottom: 1px solid #e8ecf3; padding-bottom: 12px; margin-bottom: 20px;">
    <h3 style="margin-top: 0; margin-bottom: 8px; color: #1d2a56;">Literature agent for perovskite materials discovery</h3>
    <p style="margin: 0; font-size: 0.95rem; color: #555;">
      <i class="bi bi-people-fill" style="color: #CC6600;"></i> <strong style="color: #333;">Contributors:</strong> Jordan Marshall, Mahshid Ahmadi
    </p>
  </div>
  
  <p style="margin-bottom: 25px; color: #333; line-height: 1.6;">
    We built a literature-mining agent to read perovskite solar-cell papers and extract structured information for machine learning. The agent collects device structure, composition, processing, performance, and stability data so it can be used in our PCE and stability prediction workflow.
  </p>
  
  <iframe class="embedded-video" src="https://drive.google.com/file/d/1eKHsg5cweG7ygNtQ_yNuTjiJING5OHqQ/preview" allowfullscreen style="display: block; margin: 0 auto; width: 100%; max-width: 1000px; aspect-ratio: 16 / 9; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.15);"></iframe>

</div>


<!-- fabrication agents -->
<div style="max-width: 1050px; margin: 60px auto 40px auto; line-height: 1.8; color: #333; font-size: 1.05rem; text-align: justify;">
  
  <h2 class="section-title" style="margin-top: 10px; text-align: center;">Small Science Agentic Models</h2>
  
  <p style="margin-bottom: 20px;">
    We have developed <strong>Small Science Agentic Models</strong>. The core idea is that rather than building one large, generalist AI agent that tries to do everything—or relying solely on a single optimization algorithm like Bayesian optimization—we distribute intelligence across a set of narrow, physically grounded agents, each responsible for one well-defined stage of the experimental workflow:
  </p>
  
  <ul style="list-style: none; padding: 0; margin: 0; font-size: 1rem;">
    <li style="margin-bottom: 12px;"><i class="bi bi-cpu-fill" style="color: #CC6600; margin-right: 8px;"></i> <strong>1. Hypothesis Agent:</strong> The scientific reasoning layer.</li>
    <li style="margin-bottom: 12px;"><i class="bi bi-cpu-fill" style="color: #CC6600; margin-right: 8px;"></i> <strong>2. Protocol Agent:</strong> The translation layer.</li>
    <li style="margin-bottom: 12px;"><i class="bi bi-cpu-fill" style="color: #CC6600; margin-right: 8px;"></i> <strong>3. Characterization Agent:</strong> The state-generation layer. Critically, this agent does not treat measurements as endpoints.</li>
    <li style="margin-bottom: 12px;"><i class="bi bi-cpu-fill" style="color: #CC6600; margin-right: 8px;"></i> <strong>4. ML/Decision Agent:</strong> The optimization layer.</li>
    <li style="margin-bottom: 12px;"><i class="bi bi-cpu-fill" style="color: #CC6600; margin-right: 8px;"></i> <strong>5. Orchestrator Agent:</strong> The connective tissue.</li>
  </ul>
</div>

<div class="section-card" style="margin-bottom: 40px; text-align: left;">
  
  <div style="border-bottom: 1px solid #e8ecf3; padding-bottom: 12px; margin-bottom: 20px;">
    <h3 style="margin-top: 0; margin-bottom: 8px; color: #1d2a56; ">The Hypothesis Agent</h3>
    <p style="margin: 0; font-size: 0.95rem; color: #555;">
      <i class="bi bi-people-fill" style="color: #CC6600;"></i> <strong style="color: #333;">Contributors:</strong> Sheryl Sanchez, Ariel Thompson
    </p>
  </div>
  
  <p style="margin-bottom: 25px; color: #333; line-height: 1.6;">
    A demonstration of the scientific reasoning layer, which leverages Socratic reasoning to clarify research questions, surface hidden assumptions, and generate testable hypotheses for experimental design.
  </p>
  
  <iframe class="embedded-video" src="https://drive.google.com/file/d/1uIqvESpNpMawP3f0V80TdUTBNA1YbakE/preview" allowfullscreen style="display: block; margin: 0 auto; width: 100%; max-width: 1000px; aspect-ratio: 16 / 9; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.15);"></iframe>

</div>

<div class="section-card" style="margin-bottom: 40px; text-align: left;">
  
  <div style="border-bottom: 1px solid #e8ecf3; padding-bottom: 12px; margin-bottom: 20px;">
    <h3 style="margin-top: 0; margin-bottom: 8px; color: #1d2a56; ">The Protocol Agent</h3>
    <p style="margin: 0; font-size: 0.95rem; color: #555;">
      <i class="bi bi-people-fill" style="color: #CC6600;"></i> <strong style="color: #333;">Contributors:</strong> Sheryl Sanchez, Ariel Thompson
    </p>
  </div>
  
  <p style="margin-bottom: 25px; color: #333; line-height: 1.6;">
    A showcase of the translation layer in action, autonomously interpreting high-level hypotheses to formulate executable laboratory workflows and precise automation protocols for robotic liquid handling.
  </p>
  
  <iframe class="embedded-video" src="https://drive.google.com/file/d/1zrcIbK3zKTSGBC1kgdFilDsmt5zscE3X/preview" allowfullscreen style="display: block; margin: 0 auto; width: 100%; max-width: 1000px; aspect-ratio: 16 / 9; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.15);"></iframe>

</div>

<div class="section-card" style="margin-bottom: 40px; text-align: left;">
  
  <div style="border-bottom: 1px solid #e8ecf3; padding-bottom: 12px; margin-bottom: 20px;">
    <h3 style="margin-top: 0; margin-bottom: 8px; color: #1d2a56; ">Automated Hardware Orchestration</h3>
    <p style="margin: 0; font-size: 0.95rem; color: #555;">
      <i class="bi bi-people-fill" style="color: #CC6600;"></i> <strong style="color: #333;">Contributors:</strong> Sheryl Sanchez, Ariel Thompson
    </p>
  </div>
  
  <p style="margin-bottom: 25px; color: #333; line-height: 1.6;">
    The physical execution layer: automated robotic hardware orchestrated by the agentic framework, seamlessly carrying out high-throughput fabrication and characterization of combinatorial material libraries.
  </p>
  
  <iframe class="embedded-video" src="https://drive.google.com/file/d/1fLpvVrWGGuzx7KU1kdiLWKpJARpJmRUQ/preview" allowfullscreen style="display: block; margin: 0 auto; width: 100%; max-width: 1000px; aspect-ratio: 16 / 9; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.15);"></iframe>

</div>
