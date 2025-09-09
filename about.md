---
# Jekyll front matter - customize these values
layout: default
title: "About Me"
description: "Learn more about my background, journey, and interests"
permalink: /about/
---

<div class="container">
    <h1 class="page-title">About Me</h1>
    
    <!-- Main bio section with alternating image layout -->
    <div class="about-section">
        
        <!-- First section - Early Career (image on left) -->
        <div class="about-item">
            <!-- Replace 'about_1.jpg' with your actual image -->
            <!-- Recommended size: 400x300px for best results -->
            <img src="{{ '/assets/images/about_1.jpg' | relative_url }}" alt="Early career photo" class="about-image">
            <div class="about-text">
                <h3>Early Career & Education</h3>
                <p>My journey in computer science began during my undergraduate studies at State University, 
                where I first discovered my passion for artificial intelligence and machine learning. 
                What started as curiosity about how computers could "think" evolved into a deep fascination 
                with the mathematical foundations of intelligent systems.</p>
                
                <p>During my PhD at Tech Institute, I specialized in deep learning architectures under 
                the guidance of Dr. Maria Rodriguez. My dissertation on "Neural Network Optimization 
                for Real-World Applications" laid the groundwork for my current research interests and 
                established my commitment to bridging theoretical advances with practical solutions.</p>
            </div>
        </div>
        
        <!-- Second section - Research Focus (image on right) -->
        <div class="about-item">
            <!-- Replace 'about-2.jpg' with your actual image -->
            <img src="{{ '/assets/images/about_2.jpg' | relative_url }}" alt="Research laboratory" class="about-image">
            <div class="about-text">
                <h3>Research Philosophy</h3>
                <p>My research is driven by the belief that artificial intelligence should serve humanity 
                while remaining interpretable and ethical. I focus on developing algorithms that not only 
                perform well but can also explain their decision-making processes – a crucial aspect for 
                applications in healthcare, finance, and education.</p>
                
                <p>Currently, my lab investigates three main areas: explainable AI, sustainable computing, 
                and human-AI collaboration. We've published over 30 papers in top-tier venues and our work 
                has been featured in several media outlets. I'm particularly proud of our recent breakthrough 
                in energy-efficient neural networks, which could reduce AI's carbon footprint by up to 40%.</p>
            </div>
        </div>
        
        <!-- Third section - Teaching & Mentorship (image on left) -->
        <div class="about-item">
            <!-- Replace 'about-3.jpg' with your actual image -->
            <img src="{{ '/assets/images/about_3.jpg' | relative_url }}" alt="Teaching in classroom" class="about-image">
            <div class="about-text">
                <h3>Teaching & Mentorship</h3>
                <p>Teaching is not just a profession for me – it's a calling. I believe that the best way 
                to advance science is by inspiring the next generation of researchers and practitioners. 
                My teaching philosophy centers on hands-on learning, critical thinking, and fostering 
                creativity in problem-solving.</p>
                
                <p>Over the past five years, I've had the privilege of mentoring 15 PhD students, 
                8 of whom have graduated and now work in leading tech companies and academic institutions. 
                I've also supervised over 50 undergraduate research projects, many of which have resulted 
                in publications and patent applications.</p>
            </div>
        </div>
        
        <!-- Fourth section - Personal Interests (image on right) -->
        <div class="about-item">
            <!-- Replace 'about-4.jpg' with your actual image -->
            <img src="{{ '/assets/images/about_4.jpg' | relative_url }}" alt="Personal interests" class="about-image">
            <div class="about-text">
                <h3>Beyond Academia</h3>
                <p>When I'm not in the lab or classroom, you can find me exploring the outdoors. 
                Hiking and photography are my favorite ways to disconnect from technology and gain 
                fresh perspectives. I believe that spending time in nature is essential for creativity 
                and helps me approach research problems with renewed clarity.</p>
                
                <p>I'm also passionate about science communication and regularly contribute to popular 
                science blogs, explaining complex AI concepts to general audiences. Additionally, 
                I volunteer with local high schools to introduce students to computer science, 
                particularly focusing on encouraging underrepresented groups to pursue STEM careers.</p>
            </div>
        </div>
        
        <!-- Fifth section - Vision & Future (image on left) -->
        <div class="about-item">
            <!-- Replace 'about-5.jpg' with your actual image -->
            <img src="{{ '/assets/images/about_5.jpg' | relative_url }}" alt="Future vision" class="about-image">
            <div class="about-text">
                <h3>Vision for the Future</h3>
                <p>Looking ahead, I'm excited about the potential of AI to address some of humanity's 
                greatest challenges – from climate change to healthcare accessibility. My long-term 
                research goal is to develop AI systems that are not only powerful but also trustworthy, 
                fair, and environmentally sustainable.</p>
                
                <p>I envision a future where AI augments human capabilities rather than replacing them, 
                where technology serves as a force for equity and inclusion. Through continued research, 
                teaching, and collaboration, I hope to contribute to this vision and inspire others to 
                join this important mission.</p>
            </div>
        </div>
    </div>
    
    <!-- Awards and Recognition section -->
    <h2 class="section-title">Awards & Recognition</h2>
    <div class="cards-grid">
        <div class="card">
            <h3><i class="fas fa-medal"></i> Outstanding Faculty Award</h3>
            <p>Recognized for excellence in research, teaching, and service to the university community.</p>
            <div class="card-meta">University Name • 2023</div>
        </div>
        
        <div class="card">
            <h3><i class="fas fa-trophy"></i> Best Paper Award</h3>
            <p>Received best paper award at the International Conference on Machine Learning for groundbreaking research.</p>
            <div class="card-meta">ICML Conference • 2022</div>
        </div>
        
        <div class="card">
            <h3><i class="fas fa-star"></i> Early Career Researcher Award</h3>
            <p>Honored by the Association for Computing Machinery for significant contributions to the field.</p>
            <div class="card-meta">ACM • 2021</div>
        </div>
    </div>
</div>

<!-- Custom styles for about page -->
<style>
/* Additional styles specific to the about page can be added here if needed */
.about-section {
    margin-top: 2rem;
}

/* Ensure images are properly sized on all devices */
@media (max-width: 768px) {
    .about-image {
        width: 100%;
        height: auto;
        max-height: 250px;
        object-fit: cover;
    }
}
</style>