---
layout: portfolio
title: "Research"
---

<style>
.research-section {
    padding: 3rem 0;
    max-width: 1200px;
    margin: 0 auto;
}

.research-grid {
    display: grid;
    gap: 3rem;
    margin-bottom: 4rem;
}

.research-category {
    background: var(--bg-secondary, #f9fafb);
    border-radius: 12px;
    padding: 2.5rem;
    box-shadow: var(--shadow-sm);
    border: 1px solid var(--border, #e5e7eb);
}

.category-title {
    font-size: 1.8rem;
    font-weight: 600;
    color: var(--primary-color);
    margin-bottom: 2rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    flex-wrap: wrap;
}

.category-icon {
    width: 32px;
    height: 32px;
    background: var(--primary-color);
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 1.2rem;
}

.research-item {
    background: white;
    border-radius: 8px;
    padding: 2rem;
    box-shadow: var(--shadow-md);
    border-left: 4px solid var(--primary-color);
    margin-bottom: 2rem;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.research-item:hover {
    transform: translateY(-2px);
    box-shadow: var(--shadow-lg);
}

.research-item:last-child {
    margin-bottom: 0;
}

.research-title {
    font-size: 1.4rem;
    font-weight: 600;
    color: black;
    margin-bottom: 1rem;
    line-height: 1.4;
}

.research-conference {
    font-size: 0.95rem;
    color: var(--primary-color);
    font-weight: 500;
    margin-bottom: 1rem;
    padding: 0.5rem 1rem;
    background: rgba(37, 99, 235, 0.1);
    border-radius: 6px;
    display: inline-block;
}

.research-description {
    color: dimgrey;
    margin-bottom: 1.5rem;
    line-height: 1.7;
}

.research-highlights {
    list-style: none;
    margin-bottom: 1.5rem;
    padding-left: 0;
}

.research-highlights li {
    position: relative;
    padding-left: 1.5rem;
    margin-bottom: 0.8rem;
    color: dimgrey;
    line-height: 1.6;
}

.research-highlights li:before {
    content: "▪";
    position: absolute;
    left: 0;
    color: var(--primary-color);
    font-weight: bold;
}

.research-link {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    color: var(--primary-color);
    text-decoration: none;
    font-weight: 500;
    padding: 0.5rem 1rem;
    border: 2px solid var(--primary-color);
    border-radius: 6px;
    transition: all 0.2s ease;
}

.research-link:hover {
    background: var(--primary-color);
    color: white;
    transform: translateY(-1px);
}

.status-badge {
    display: inline-block;
    padding: 0.3rem 0.8rem;
    font-size: 0.8rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    border-radius: 20px;
    margin-left: 1rem;
}

.status-ongoing {
    background: rgba(16, 185, 129, 0.1);
    color: #059669;
}

.status-published {
    background: rgba(37, 99, 235, 0.1);
    color: var(--primary-color);
}

@media (max-width: 768px) {
    .research-section {
        padding: 2rem 1rem;
    }

    .research-category {
        padding: 1.5rem;
    }

    .research-item {
        padding: 1.5rem;
    }

    .research-title {
        font-size: 1.2rem;
    }

    .category-title {
        flex-direction: column;
        align-items: flex-start;
        gap: 1rem;
    }

    .status-badge {
        margin-left: 0;
    }
}
</style>

<section class="section" style="background: var(--surface);">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">Research & Publications</h2>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <div class="research-section">
        <div class="research-grid">
            <!-- Published Research -->
            <div class="research-category">
                <h3 class="category-title">
                    <div class="category-icon">📊</div>
                    Published Research
                    <span class="status-badge status-published">Published</span>
                </h3>                
                <div class="research-item">
                    <h4 class="research-title">
                        Application of Stress Induced Piezoelectric Harvesters in the Context of Bangladesh
                    </h4>
                    <div class="research-conference">
                        ICSDTIR-2021: International Conference on Sustainable Development in Technology for 4th Industrial Revolution
                    </div>
                    <p class="research-description">
                        This research explores the potential implementation of piezoelectric energy harvesting systems in Bangladesh's infrastructure, focusing on sustainable energy solutions through mechanical stress conversion.
                    </p>
                    <a href="https://www.researchgate.net/publication/353466182_APPLICATION_OF_STRESS_INDUCED_PIEZOELECTRIC_HARVESTERS_IN_THE_CONTEXT_OF_BANGLADESH" 
                       class="research-link" target="_blank" rel="noopener noreferrer">
                        <span>📄</span>
                        View Publication
                    </a>
                </div>
            </div>
            <!-- Ongoing Research -->
            <div class="research-category">
                <h3 class="category-title">
                    <div class="category-icon">🔬</div>
                    Ongoing Research Projects
                    <span class="status-badge status-ongoing">In Progress</span>
                </h3>
                <div class="research-item">
                    <h4 class="research-title">
                        Evaluating and Optimizing Metro Construction Impacts on Heterogeneous Traffic Flow: A SUMO-Based Simulation Study of Natun Bazar, Dhaka, Bangladesh
                    </h4>
                    <p class="research-description">
                        Comprehensive traffic flow analysis using advanced simulation techniques to understand and mitigate the impact of metro construction on urban transportation systems.
                    </p>
                    <ul class="research-highlights">
                        <li>Simulate lane closure effects on traffic flow using SUMO software at key intersections</li>
                        <li>Utilize Python for dynamic control and machine learning to optimize vehicle parameters (speed, acceleration)</li>
                        <li>Develop a vehicle counter mobile application for real-time traffic data collection during surveys</li>
                        <li>Present evidence-based solutions including traffic management plans and infrastructure adjustments</li>
                    </ul>
                </div>
                <div class="research-item">
                    <h4 class="research-title">
                        Predicting Road Crash Severity using Classifier Models with Crash Hotspot Identification
                    </h4>
                    <p class="research-description">
                        Advanced data analytics approach to predict road crash severity and identify high-risk areas in Dhaka, contributing to evidence-based traffic safety policy development.
                    </p>
                    <ul class="research-highlights">
                        <li><strong>Data Integration & Preprocessing:</strong> Perform relational database merging using foreign keys, handle missing values through imputation, and conduct feature engineering</li>
                        <li><strong>Hotspot Identification:</strong> Use spatial analysis techniques (Kernel Density) to locate and visualize high-risk zones in Dhaka (2015–2021)</li>
                        <li><strong>Predictive Modeling:</strong> Train classifier models (Random Forest, XGBoost) to predict crash severity using location, time, and participant profile features</li>
                        <li><strong>Policy Development:</strong> Draft actionable recommendations based on analytical insights for urban safety improvement</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

  </div>
</section>
