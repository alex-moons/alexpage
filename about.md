---
layout: default
title: About
permalink: /about/
---

<section class="about-hero">
    <h1>About Me</h1>
    <p class="about-intro">I'm a passionate fullstack web developer dedicated to creating elegant, efficient solutions to complex problems.</p>
</section>

<section class="about-content">
    <div class="about-grid">
        <div class="about-text">
            <h2>Who I Am</h2>
            <p>
                I'm Alejandro Hernandez, a fullstack web developer with a passion for building high-quality, user-focused web applications. 
                With expertise across the entire development stack, I transform ideas into robust digital products.
            </p>
            <p>
                My journey in web development started with a curiosity about how things work on the internet. 
                Over the years, I've developed a deep understanding of both frontend and backend technologies, 
                allowing me to architect complete solutions from the ground up.
            </p>
            <p>
                I believe in writing clean, maintainable code, following best practices, and continuously learning new technologies. 
                I'm particularly passionate about user experience design, performance optimization, and building scalable systems.
            </p>
        </div>

        <div class="about-sidebar">
            <div class="about-card">
                <h3>Quick Facts</h3>
                <ul class="fact-list">
                    <li><strong>Location:</strong> Remote</li>
                    <li><strong>Experience:</strong> 5+ years</li>
                    <li><strong>Specialization:</strong> Fullstack Web Development</li>
                    <li><strong>Email:</strong> <a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
                    <li><strong>GitHub:</strong> <a href="https://github.com/{{ site.github_username }}" target="_blank">@{{ site.github_username }}</a></li>
                </ul>
            </div>
        </div>
    </div>
</section>

<section class="skills-detailed">
    <h2>Technical Skills</h2>
    
    <div class="skills-detailed-grid">
        <div class="skill-block">
            <h3>Frontend Development</h3>
            <ul>
                <li><strong>Languages:</strong> HTML, CSS, JavaScript, TypeScript</li>
                <li><strong>Frameworks:</strong> React, Vue.js, Next.js</li>
                <li><strong>Styling:</strong> SCSS, Tailwind CSS, CSS-in-JS</li>
                <li><strong>State Management:</strong> Redux, Vuex, Context API</li>
                <li><strong>Testing:</strong> Jest, React Testing Library, Cypress</li>
                <li><strong>Tools:</strong> Webpack, Vite, Babel</li>
            </ul>
        </div>

        <div class="skill-block">
            <h3>Backend Development</h3>
            <ul>
                <li><strong>Runtime:</strong> Node.js</li>
                <li><strong>Frameworks:</strong> Express, NestJS, FastAPI</li>
                <li><strong>Languages:</strong> JavaScript, TypeScript, Python</li>
                <li><strong>APIs:</strong> RESTful APIs, GraphQL, WebSockets</li>
                <li><strong>Authentication:</strong> JWT, OAuth2, Session Management</li>
                <li><strong>Testing:</strong> Mocha, Jest, PyTest</li>
            </ul>
        </div>

        <div class="skill-block">
            <h3>Databases & Data</h3>
            <ul>
                <li><strong>Relational:</strong> PostgreSQL, MySQL, MariaDB</li>
                <li><strong>NoSQL:</strong> MongoDB, Firebase, Redis</li>
                <li><strong>Data Processing:</strong> SQL, Data Visualization</li>
                <li><strong>Optimization:</strong> Indexing, Query Optimization</li>
            </ul>
        </div>

        <div class="skill-block">
            <h3>Cloud & DevOps</h3>
            <ul>
                <li><strong>Cloud Platforms:</strong> AWS, Vercel, Netlify, Heroku</li>
                <li><strong>Containerization:</strong> Docker, Docker Compose</li>
                <li><strong>CI/CD:</strong> GitHub Actions, GitLab CI, Jenkins</li>
                <li><strong>Monitoring:</strong> Logging, Performance Monitoring</li>
                <li><strong>Version Control:</strong> Git, GitHub, GitLab</li>
            </ul>
        </div>
    </div>
</section>

<section class="experience">
    <h2>What I Offer</h2>
    <div class="experience-grid">
        <div class="experience-card">
            <h3>Full-Stack Solutions</h3>
            <p>End-to-end development services from concept to deployment, handling both frontend and backend requirements.</p>
        </div>
        <div class="experience-card">
            <h3>Performance Optimization</h3>
            <p>Expertise in identifying bottlenecks and optimizing applications for speed, scalability, and efficiency.</p>
        </div>
        <div class="experience-card">
            <h3>Responsive Design</h3>
            <p>Creating beautiful, mobile-first web applications that work seamlessly across all devices and screen sizes.</p>
        </div>
        <div class="experience-card">
            <h3>Clean Architecture</h3>
            <p>Building maintainable, scalable systems with well-organized code and clear separation of concerns.</p>
        </div>
        <div class="experience-card">
            <h3>API Development</h3>
            <p>Designing and implementing robust RESTful and GraphQL APIs that power modern web applications.</p>
        </div>
        <div class="experience-card">
            <h3>Deployment & DevOps</h3>
            <p>Managing cloud infrastructure, CI/CD pipelines, and deployment workflows for reliable production systems.</p>
        </div>
    </div>
</section>

<section class="cta-section">
    <h2>Let's Collaborate</h2>
    <p>I'm always interested in discussing new projects and opportunities. Feel free to reach out!</p>
    <div class="cta-buttons">
        <a href="mailto:{{ site.email }}" class="btn btn-primary">Get In Touch</a>
        <a href="https://github.com/{{ site.github_username }}" target="_blank" class="btn btn-secondary">View My GitHub</a>
    </div>
</section>

