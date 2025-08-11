---
layout: portfolio
title: "Home"
---

<div class="hero">
  <div class="container">
    <div class="hero-content">
      <div class="hero-text">
        <h1>Ibrahim Kaiser</h1>
        <p class="subtitle">Civil Engineer | Python Developer | AI Enthusiast</p>
        <p class="description">
          Civil engineer blending domain expertise with Python, AI, and automation to modernize transportation workflows. With 5+ years in infrastructure development and project management, I build intelligent tools - from Streamlit dashboards for site coordination to GenAI models for road defect detection. I hold a BSc in Civil Engineering from Bangladesh University of Engineering & Technology (BUET).
        </p>
        <div style="display: flex; gap: 1rem; margin-top: 2rem;">
          <a href="{{ '/projects' | relative_url }}" class="btn btn-primary">
            View My Work
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <line x1="7" y1="17" x2="17" y2="7"></line>
              <polyline points="7,7 17,7 17,17"></polyline>
            </svg>
          </a>
          <a href="{{ '/about#contact' | relative_url }}" class="btn btn-outline">Get in Touch</a>
        </div>
      </div>
      <div class="hero-image">
        <img src="/assets/images/profile.jpg" alt="Ibrahim Kaiser" class="profile-image" 
             onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
        <div class="profile-image" style="display: none; background: linear-gradient(135deg, #2563eb, #10b981); color: white; font-size: 4rem; font-weight: bold;">
          IK
        </div>
      </div>
    </div>
  </div>
</div>

<section class="section">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">Core Expertise</h2>
      <p class="section-subtitle">
        Bridging the gap between traditional civil engineering and modern technology solutions
      </p>
    </div>
    
    <div class="skills-grid">
      <div class="skill-card">
        <h3>🏗️ Civil Engineering</h3>
        <p>Structural analysis, transportation planning, project management, and infrastructure design with focus on sustainable and efficient solutions.</p>
        <div class="skill-tags">
          <span class="tag">AutoCAD</span>
          <span class="tag">SAP2000</span>
          <span class="tag">ETABS</span>
          <span class="tag">Project Management</span>
        </div>
      </div>
      
      <div class="skill-card">
        <h3>🐍 Python Development</h3>
        <p>Data analysis, automation, web development, and creating engineering tools using Python ecosystem and modern frameworks.</p>
        <div class="skill-tags">
          <span class="tag">Django</span>
          <span class="tag">Pandas</span>
          <span class="tag">NumPy</span>
          <span class="tag">Matplotlib</span>
        </div>
      </div>
      
      <div class="skill-card">
        <h3>🚗 Transportation Systems</h3>
        <p>Traffic analysis, transportation modeling, smart city solutions, and sustainable mobility planning for urban environments.</p>
        <div class="skill-tags">
          <span class="tag">Traffic Modeling</span>
          <span class="tag">GIS Analysis</span>
          <span class="tag">Smart Cities</span>
          <span class="tag">Sustainability</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section" style="background: var(--surface);">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">Recent Highlights</h2>
      <p class="section-subtitle">A glimpse into my latest projects and achievements</p>
    </div>    
    <div class="projects-grid">
      <div class="project-card">
        <div class="project-image">
          <img src="/assets/images/ai_contest.jpeg" alt="AI Contest">
        </div>
        <div class="project-content">
          <h3 class="project-title">2nd Runner Up, AI Contest</h3>
          <p class="project-description">            
          </p>
          <div class="project-tech">
            <span class="tech-tag">Python</span>
            <span class="tech-tag">NLP</span>
            <span class="tech-tag">TensorFlow</span>
          </div>
        </div>
      </div>      
      <div class="project-card">
        <div class="project-image">
          <img src="/assets/images/utility.jpg" alt="Utility Dashboard">
        </div>
        <div class="project-content">
          <h3 class="project-title">Utility Relocation Dashboard</h3>
          <p class="project-description">
            Web application for utility relocation work monitoring and management. Daily progress report generator.
          </p>
          <div class="project-tech">
            <span class="tech-tag">Python</span>
            <span class="tech-tag">Streamlit</span>
            <span class="tech-tag">Pandas</span>
          </div>
          <div class="project-links">
            <a href="https://mrtl1-utility.streamlit.app/" target="_blank" rel="noopener noreferrer">Live Demo</a>
            <a href="https://github.com/ikReza/mrtl1_utility" target="_blank" rel="noopener noreferrer">GitHub</a>
          </div>
        </div>
      </div>
      <!-- Add more project cards as needed -->
      <div class="project-card">
        <div class="project-image iframe-container">
          <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7357788650811609089?compact=1" 
                  frameborder="0" 
                  allowfullscreen="" 
                  title="Road Inspect">
          </iframe>
        </div>
        <div class="project-content">
          <h3 class="project-title">Site Inspection & Reporting</h3>
          <p class="project-description">
            Automation of site inspection & reporting using Generative AI with integrating multiple technologies.
          </p>
          <div class="project-tech">
            <span class="tech-tag">Roboflow</span>
            <span class="tech-tag">YOLOv12</span>
            <span class="tech-tag">Gemini AI</span>
          </div>
          <div class="project-links">
            <a href="https://github.com/ikReza/road_inspect">GitHub</a>
          </div>
        </div>
      </div>
    </div>
    
    <div class="text-center mt-4">
      <a href="{{ '/projects' | relative_url }}" class="btn btn-primary">View All Projects</a>
    </div>
  </div>
</section>
