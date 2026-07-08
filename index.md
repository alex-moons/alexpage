---
layout: default
title: Home
---

<section class="hero">
    <div class="hero-content">
        <h1 class="hero-title">Hi, I'm <span class="highlight">Alejandro</span></h1>
        <p class="hero-subtitle">Fullstack Web Developer | Building elegant solutions with modern technologies</p>
        <p class="hero-description">
            I specialize in creating responsive, performant web applications using frontend frameworks, backend systems, 
            and cloud technologies. Passionate about clean code, user experience, and continuous learning.
        </p>
        <div class="hero-cta">
            <a href="#featured-projects" class="btn btn-primary">View My Work</a>
            <a href="{{/alexpage/about | relative_url }}" class="btn btn-secondary">Learn About Me</a>
        </div>
    </div>
</section>

<section id="featured-projects" class="featured-projects">
    <div class="section-header">
        <h2>Featured Projects</h2>
        <p class="section-subtitle">A selection of my recent work</p>
    </div>
    
    <div class="projects-grid">
        <div class="project-card">
            <div class="project-header">
                <h3>E-Commerce Platform</h3>
                <span class="project-date">2025</span>
            </div>
            <p class="project-description">
                Full-featured e-commerce application with product catalog, shopping cart, and payment integration. 
                Built with React, Node.js, MongoDB, and Stripe.
            </p>
            <div class="project-tech">
                <span class="tech-tag">React</span>
                <span class="tech-tag">Node.js</span>
                <span class="tech-tag">MongoDB</span>
                <span class="tech-tag">Stripe API</span>
            </div>
            <div class="project-links">
                <a href="https://github.com/alex-moons" target="_blank" class="project-link">View Code →</a>
            </div>
        </div>

        <div class="project-card">
            <div class="project-header">
                <h3>Task Management App</h3>
                <span class="project-date">2025</span>
            </div>
            <p class="project-description">
                Collaborative task management tool with real-time updates, user authentication, and task scheduling. 
                Deployed on cloud infrastructure with responsive design.
            </p>
            <div class="project-tech">
                <span class="tech-tag">Vue.js</span>
                <span class="tech-tag">Express</span>
                <span class="tech-tag">PostgreSQL</span>
                <span class="tech-tag">WebSocket</span>
            </div>
            <div class="project-links">
                <a href="https://github.com/alex-moons" target="_blank" class="project-link">View Code →</a>
            </div>
        </div>

        <div class="project-card">
            <div class="project-header">
                <h3>Analytics Dashboard</h3>
                <span class="project-date">2025</span>
            </div>
            <p class="project-description">
                Data visualization dashboard with interactive charts and real-time data processing. 
                Features filtering, exporting, and custom report generation.
            </p>
            <div class="project-tech">
                <span class="tech-tag">TypeScript</span>
                <span class="tech-tag">D3.js</span>
                <span class="tech-tag">Python</span>
                <span class="tech-tag">AWS</span>
            </div>
            <div class="project-links">
                <a href="https://github.com/alex-moons" target="_blank" class="project-link">View Code →</a>
            </div>
        </div>
    </div>

    <div class="projects-footer">
        <a href="/projects" class="btn btn-secondary">See All Projects</a>
    </div>
</section>

<section class="skills-preview">
    <div class="section-header">
        <h2>Skills & Technologies</h2>
        <p class="section-subtitle">Tools and technologies I work with</p>
    </div>
    
    <div class="skills-grid">
        <div class="skill-category">
            <h4>Frontend</h4>
            <div class="skill-list">
                <span class="skill">JavaScript/TypeScript</span>
                <span class="skill">React</span>
                <span class="skill">Vue.js</span>
                <span class="skill">HTML/CSS/SCSS</span>
            </div>
        </div>
        <div class="skill-category">
            <h4>Backend</h4>
            <div class="skill-list">
                <span class="skill">Node.js</span>
                <span class="skill">Express</span>
                <span class="skill">Python</span>
                <span class="skill">RESTful APIs</span>
            </div>
        </div>
        <div class="skill-category">
            <h4>Database & Tools</h4>
            <div class="skill-list">
                <span class="skill">MongoDB</span>
                <span class="skill">PostgreSQL</span>
                <span class="skill">Git</span>
                <span class="skill">Docker</span>
            </div>
        </div>
        <div class="skill-category">
            <h4>Cloud & DevOps</h4>
            <div class="skill-list">
                <span class="skill">AWS</span>
                <span class="skill">Vercel</span>
                <span class="skill">CI/CD</span>
                <span class="skill">Linux</span>
            </div>
        </div>
    </div>
</section>

<section class="cta-section">
    <h2>Ready to work together?</h2>
    <p>Let's build something amazing. Get in touch to discuss your next project.</p>
    <a href="mailto:{{ site.email }}" class="btn btn-primary">Send Me an Email</a>
</section>
