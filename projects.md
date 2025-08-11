---
layout: portfolio
title: "Projects"
---

<section class="section">
  <div class="container">
    <div class="section-header">
      <h1 class="section-title">My Projects</h1>
      <p class="section-subtitle">
        Showcasing AI-powered solutions, machine learning models, and GIS applications for civil engineering challenges
      </p>
    </div>
    <!-- AI Projects Section -->
    <div style="margin-bottom: 4rem;">
      <h2 style="color: var(--primary-color); margin-bottom: 2rem; font-size: 2rem; text-align: center;">🤖 AI Projects</h2>
      <div class="projects-grid">
        <div class="project-card">
          <div class="project-image">
            <img src="/assets/images/traffic-safety-ai.jpg" alt="Traffic Safety AI Dashboard" 
                 style="width: 100%; height: 200px; object-fit: cover; border-radius: 0.5rem;"
                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
            <div style="display: none; width: 100%; height: 200px; background: linear-gradient(135deg, #3b82f6, #1d4ed8); border-radius: 0.5rem; color: white; font-size: 3rem; align-items: center; justify-content: center;">
              🚦
            </div>
          </div>
          <div class="project-content">
            <h3 class="project-title">Traffic Safety AI Agent</h3>
            <p class="project-description">
              Intelligent AI agent using RAG (Retrieval-Augmented Generation) for traffic safety analysis. 
              Features interactive Streamlit dashboard for real-time traffic pattern analysis, incident prediction, 
              and safety recommendations deployed on Hugging Face Spaces.
            </p>
            <div class="project-tech">
              <span class="tech-tag">Python</span>
              <span class="tech-tag">RAG</span>
              <span class="tech-tag">Streamlit</span>
              <span class="tech-tag">HuggingFace</span>
              <span class="tech-tag">LangChain</span>
            </div>
            <div class="project-links">
              <a href="#" target="_blank">Live Demo</a>
              <a href="#" target="_blank">GitHub</a>
              <a href="#" target="_blank">HF Spaces</a>
            </div>
          </div>
        </div>
        <!-- Road Defect Detection -->
        <div class="project-card">
          <div class="project-image iframe-container">
            <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7357788650811609089?compact=1" 
                  frameborder="0" 
                  allowfullscreen="" 
                  title="Road Inspect">
          </iframe>
            <div style="display: none; width: 100%; height: 200px; background: linear-gradient(135deg, #10b981, #059669); border-radius: 0.5rem; color: white; font-size: 3rem; align-items: center; justify-content: center;">
              🛣️
            </div>
          </div>
          <div class="project-content">
            <h3 class="project-title">Site Inspection & Reporting</h3>
            <p class="project-description">
              Advanced GenAI solution for automatic road defect identification and classification. System processes road imagery, stores defect data with geolocation, and generates comprehensive maintenance reports using computer vision and natural language generation.
            </p>
            <div class="project-tech">
              <span class="tech-tag">Python</span>
              <span class="tech-tag">Gemini AI</span>
              <span class="tech-tag">Computer Vision</span>
              <span class="tech-tag">YOLOv12</span>
              <span class="tech-tag">SQLite</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/ikReza/road_inspect" target="_blank" rel="noopener">GitHub</a>
              <a href="https://docs.google.com/document/d/1n0YTiJiMWSe0nBY46Qdom51mbwB-ObAGF359VwsMnQU/edit?usp=sharing" target="_blank" rel="noopener">Report Sample</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- ML Projects Section -->
    <div style="margin-bottom: 4rem;">
      <h2 style="color: var(--primary-color); margin-bottom: 2rem; font-size: 2rem; text-align: center;">🧠 Machine Learning Projects</h2>
      <div class="projects-grid">
        <div class="project-card">
          <div class="project-image">
            <img src="/assets/images/traffic-sign-classification.jpg" alt="Traffic Sign Classification"
                 style="width: 100%; height: 200px; object-fit: cover; border-radius: 0.5rem;"
                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
            <div style="display: none; width: 100%; height: 200px; background: linear-gradient(135deg, #8b5cf6, #7c3aed); border-radius: 0.5rem; color: white; font-size: 3rem; align-items: center; justify-content: center;">
              🚸
            </div>
          </div>
          <div class="project-content">
            <h3 class="project-title">Traffic Sign Classification</h3>
            <p class="project-description">
              Deep learning model for real-time traffic sign recognition and classification.
              Trained on Kaggle dataset. Implemented using CNN architecture with data augmentation techniques.
            </p>
            <h4>Tasks:</h4>
            <ol style="padding-left:1.5rem;">
              <li><span style="text-decoration:underline;">Data Augmentation:</span> Horizontal/Vertical shifts, horizontal flip, shear, zoom</li>
              <li><span style="text-decoration:underline;">Input Processing:</span> Random RGB normalization (outperformed grayscale)</li>
              <li><span style="text-decoration:underline;">Architecture:</span> 3x3 kernels with max pooling</li>
            </ol>
            <div class="project-links">
              <a href="https://github.com/ikReza/traffic-sign-classification" target="_blank" rel="noopener">GitHub Repo</a>
            </div>
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="/assets/images/bulldozer-price-prediction.jpg" alt="Bulldozer Price Prediction"
                 style="width: 100%; height: 200px; object-fit: cover; border-radius: 0.5rem;"
                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
            <div style="display: none; width: 100%; height: 200px; background: linear-gradient(135deg, #f59e0b, #d97706); border-radius: 0.5rem; color: white; font-size: 3rem; align-items: center; justify-content: center;">
              🚜
            </div>
          </div>
          <div class="project-content">
            <h3 class="project-title" style="text-align:center;">Predict the Sell Price of Bulldozers</h3>
            <p class="project-description">
              Kaggle competition solution predicting heavy equipment auction prices using ensemble machine learning. Achieved top 10% ranking with Random Forest and XGBoost models.
            </p>
            <div>
              <h4>Tasks:</h4>
              <ol style="padding-left:1.5rem;">
                <li><span style="text-decoration:underline;">Data Source & Preprocessing:</span>  Kaggle dataset | EDA | Missing value imputation | Date parsing</li>
                <li><span style="text-decoration:underline;">Model Selection:</span> Random Forest Regressor</li>
                <li><span style="text-decoration:underline;">Hyperparameter Tuning:</span> GridSearchCV | RandomizedSearchCV</li>
              </ol>
            </div>
            <div class="project-links">
              <a href="#" target="_blank">Kaggle</a>
              <a href="https://github.com/ikReza/ML-projects/tree/master/Blue%20Book%20for%20Bulldozers" target="_blank" rel="noopener">GitHub</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- GIS Projects Section -->
    <div style="margin-bottom: 4rem;">
      <h2 style="color: var(--primary-color); margin-bottom: 2rem; font-size: 2rem; text-align: center;">🗺️ GIS Projects</h2>
      <div class="projects-grid">
        <div class="project-card">
          <div class="project-image">
            <img src="/assets/images/gis-web-mapping.jpg" alt="GIS Web Mapping Project"
                 style="width: 100%; height: 200px; object-fit: cover; border-radius: 0.5rem;"
                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
            <div style="display: none; width: 100%; height: 200px; background: linear-gradient(135deg, #06b6d4, #0891b2); border-radius: 0.5rem; color: white; font-size: 3rem; align-items: center; justify-content: center;">
              🌍
            </div>
          </div>
          <div class="project-content">
            <h3 class="project-title">GIS Web Mapping Project</h3>
            <p class="project-description">
              Interactive web-based GIS application demonstrating spatial data visualization and analysis capabilities. Proof of concept showcasing the complete workflow from GIS data processing to web deployment for urban infrastructure mapping and analysis.
            </p>
            <div style="margin: 1rem 0;">
              <h4 style="color: var(--primary-color); margin-bottom: 0.5rem; font-size: 1rem;">Key Components:</h4>
              <ul style="margin: 0; padding-left: 1.5rem; font-size: 0.9rem;">
                <li><strong>QGIS Data Processing:</strong> Digitized road networks & exported GeoJSON features</li>
                <li><strong>Web Visualization:</strong> Built interactive map with React + Leaflet.js</li>
                <li><strong>Toolchain:</strong> QGIS → GeoJSON → React/JavaScript → Leaflet API</li>
              </ul>
            </div>
            <div class="project-tech">
              <span class="tech-tag">QGIS</span>
              <span class="tech-tag">React</span>
              <span class="tech-tag">Leaflet.js</span>
              <span class="tech-tag">GeoJSON</span>
              <span class="tech-tag">JavaScript</span>
            </div>
            <div class="project-links">
              <a href="https://urbaniq-lake.vercel.app/" target="_blank" rel="noopener">Live Map</a>
              <a href="https://github.com/ikReza/urbaniq" target="_blank" rel="noopener">GitHub</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
