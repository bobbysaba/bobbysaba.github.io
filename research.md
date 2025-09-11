---
# Jekyll front matter
layout: default
title: "Research"
description: "Explore my research projects, publications, and contributions to severe weather and atmospheric sciences"
permalink: /research/
---

<div class="container">
    <h1 class="page-title">Research</h1>
    
    <!-- Research Overview -->
    <div class="hero-description text-center" style="margin-bottom: 3rem;">
        <p>My research focuses on severe weather phenomena, particularly supercell thunderstorms, tornado genesis, and storm-scale processes in the U.S. I integrate high-resolution simulations with novel observational techniques, such as Doppler wind lidar, to advance understanding of tornadic convection and improve forecasting capabilities.</p>
    </div>
    
    <!-- Research Areas -->
    <h2 class="section-title">Research Areas</h2>
    <div class="cards-grid">
        <div class="card">
            <h3><i class="fas fa-cloud-sun-rain"></i> Supercell Dynamics and Environments</h3>
            <p>Investigating the environmental factors influencing right-moving supercells, including inflow layer characteristics and wind shear effects, using composite observations from Doppler wind lidar and field campaigns.</p>
            <div class="card-meta">
                <strong>Key Contributions:</strong> NSF/VORTEX-funded field observations • <strong>Collaborations:</strong> NSSL/NOAA
            </div>
        </div>
        
        <div class="card">
            <h3><i class="fas fa-eye"></i> Remote Sensing and Observations</h3>
            <p>Developing and applying mobile Doppler wind lidar strategies to collect real-time data on supercell and QLCS environments, enabling novel insights into tornado formation and storm evolution.</p>
            <div class="card-meta">
                <strong>Key Tools:</strong> NSSL Mobile Lidar • <strong>Impact:</strong> Real-time data ingestion frameworks
            </div>
        </div>
        
        <div class="card">
            <h3><i class="fas fa-laptop-code"></i> High-Resolution Storm Simulations</h3>
            <p>Utilizing numerical models like CM1 to examine tornadic convection processes in Southeast U.S. environments, focusing on storm-scale interactions and backing wind effects on supercell evolution.</p>
            <div class="card-meta">
                <strong>Key Simulations:</strong> Dissertation research • <strong>Funding:</strong> NSF Grants
            </div>
        </div>
        
        <div class="card">
            <h3><i class="fas fa-chart-line"></i> Tornado Intensity Classification</h3>
            <p>Analyzing historical and modern tornado rating systems, including verification of NWS damage paths, to propose improvements for more accurate intensity assessments.</p>
            <div class="card-meta">
                <strong>Key Outputs:</strong> Capstone and conference presentations • <strong>Awards:</strong> 1st Place Undergraduate Oral
            </div>
        </div>
    </div>
    
    <!-- Current Projects -->
    <h2 class="section-title">Current Projects</h2>
    
    <div class="about-section">
        <div class="cv-item">
            <h4><i class="fas fa-project-diagram"></i> Examining Tornadic Convection in Southeast U.S. Environments</h4>
            <div class="cv-meta">PhD Dissertation • Expected 2028 • NSF-Funded</div>
            <p>This project uses high-resolution simulations to analyze storm-scale processes in tornadic convection, focusing on environmental influences in the Southeast U.S. Collaborative work with NSSL scientists integrates modeling with field observations.</p>
            <p><strong>Team:</strong> OU/NSSL/NOAA collaborators</p>
        </div>
        
        <div class="cv-item">
            <h4><i class="fas fa-microscope"></i> Doppler Wind Lidar Observations of Supercell Environments</h4>
            <div class="cv-meta">MS Thesis • Completed Nov 2024 • VORTEX-SE Field Campaign</div>
            <p>Exploring right-moving supercell environments through novel lidar observations. Includes designing scanning strategies and briefing field teams on weather conditions to support operational decisions.</p>
            <p><strong>Partners:</strong> NSSL, Cooperative Institute for Severe Weather</p>
        </div>
        
        <div class="cv-item">
            <h4><i class="fas fa-database"></i> NSSL Real-Time Data Ingestion and Situational Awareness</h4>
            <div class="cv-meta">Ongoing • 2023-Present • Python/Crontab Development</div>
            <p>Building frameworks for ingesting and quality-controlling lidar, surface, and radiosonde data in real-time. Utilizes MQTT and SFTP to overcome IP challenges and disseminate data to forecasters for public safety.</p>
            <p><strong>Applications:</strong> Field campaigns, high-stakes operations</p>
        </div>
    </div>
    
    <!-- Publications -->
    <h2 class="section-title">Selected Publications</h2>
    
    <div class="about-section">
        <!-- Publication entries based on CV -->
        <div class="cv-item">
            <h4>Examining Right-Moving Supercell Environments in the Great Plains with Composite Doppler Wind Lidar Observations</h4>
            <div class="cv-meta">
                <strong>Authors:</strong> R.A. Saba, M.C. Coniglio, J.G. Gebauer, T.M. Bell, E.N. Smith, S. Waugh<br>
                <strong>Venue:</strong> Monthly Weather Review (Submitted, in review)<br>
                <strong>Status:</strong> <span class="highlight">Under Review</span>
            </div>
            <p>This study composites lidar observations to reveal key environmental features supporting right-moving supercells in the Great Plains, advancing understanding of inflow dynamics.</p>
            <p><strong>Impact:</strong> Supports VORTEX-SE field efforts</p>
        </div>
        
        <div class="cv-item">
            <h4>The Effects of Backing Wind and Effective Inflow Layer Depth on Supercell Evolution</h4>
            <div class="cv-meta">
                <strong>Authors:</strong> R.A. Saba, M.A. Satrio, T.J. Pardun, M.D. Flournoy, M.C. Coniglio, J.C. Snyder<br>
                <strong>Venue:</strong> In progress<br>
                <strong>Type:</strong> Journal Article
            </div>
            <p>Analyzes how backing winds and inflow depth influence supercell and tornado-like vortices using CM1 simulations, with implications for Southeast U.S. forecasting.</p>
            <p><strong>Impact:</strong> Builds on dissertation research</p>
        </div>
    </div>
    
    <!-- Research Tools and Resources -->
    <h2 class="section-title">Research Tools & Resources</h2>
    <div class="cards-grid">
        <div class="card">
            <h3><i class="fab fa-github"></i> Open Source Projects</h3>
            <p>NSSL Lidar Data Ingestion Framework - Python-based real-time QC and dissemination tool for field observations</p>
            <p>Real-Time Situational Awareness Visualizer - MQTT-enabled dashboard for storm data</p>
            <div class="card-meta">
                <a href="https://github.com/yourusername" target="_blank" class="btn btn-outline btn-sm">
                    <i class="fab fa-github"></i> View on GitHub
                </a>
            </div>
        </div>
        
        <div class="card">
            <h3><i class="fas fa-database"></i> Datasets</h3>
            <p>VORTEX-SE Lidar Composites - Field observations from supercell environments (ongoing collection)</p>
            <p>Tornado Damage Path Verifications - NWS-integrated dataset for intensity classification</p>
            <div class="card-meta">
                Available for research use under NOAA guidelines
            </div>
        </div>
        
        <div class="card">
            <h3><i class="fas fa-graduation-cap"></i> Educational Materials</h3>
            <p>Interactive tutorials on lidar scanning strategies</p>
            <p>Field briefing templates for severe weather operations</p>
            <div class="card-meta">
                Used in OU Meteorology courses and NSSL training
            </div>
        </div>
    </div>
    
    <!-- Collaboration Opportunities -->
    <div class="hero-section" style="margin-top: 3rem;">
        <div class="hero-content">
            <h2>Interested in Collaboration?</h2>
            <p>I'm always looking for opportunities to collaborate with fellow researchers, NOAA partners, and students on severe weather projects. Whether you're interested in field campaigns, simulations, or funding opportunities like VORTEX, I'd love to hear from you.</p>
            <div class="cta-buttons">
                <a href="{{ '/contact/' | relative_url }}" class="btn btn-primary">
                    <i class="fas fa-envelope"></i> Contact Me
                </a>
                <a href="{{ '/assets/files/research-statement.pdf' | relative_url }}" class="btn btn-outline" target="_blank">
                    <i class="fas fa-file-pdf"></i> Research Statement
                </a>
            </div>
        </div>
    </div>
</div>

<!-- Additional custom styles for research page -->
<style>
.btn-sm {
    padding: 0.5rem 1rem;
    font-size: 0.9rem;
}

.highlight {
    background: linear-gradient(120deg, #e74c3c 0%, #e74c3c 100%);
    color: white;
    padding: 2px 6px;
    border-radius: 4px;
    font-weight: 600;
}

/* Style for publication links and metadata */
.cv-item strong {
    color: var(--primary-color);
}

.cv-item p:last-of-type {
    font-style: italic;
    color: var(--text-light);
}
</style>