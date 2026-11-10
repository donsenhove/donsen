<!DOCTYPE html>  <html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Donsen Hove | IT Professional</title>  
    <style>  
        /* CSS Styling */  
        :root {  
            --bg-color: #0f172a;  
            --text-color: #e2e8f0;  
            --primary-color: #38bdf8;  
            --secondary-color: #1e293b;  
            --accent-color: #818cf8;  
        }  * {  
        margin: 0;  
        padding: 0;  
        box-sizing: border-box;  
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;  
    }  

    body {  
        background-color: var(--bg-color);  
        color: var(--text-color);  
        line-height: 1.6;  
    }  

    /* Navigation */  
    nav {  
        display: flex;  
        justify-content: space-between;  
        align-items: center;  
        padding: 20px 50px;  
        background-color: rgba(15, 23, 42, 0.95);  
        position: sticky;  
        top: 0;  
        z-index: 100;  
        border-bottom: 1px solid var(--secondary-color);  
    }  

    nav h1 {  
        color: var(--primary-color);  
        font-size: 1.5rem;  
    }  

    nav ul {  
        display: flex;  
        list-style: none;  
        gap: 20px;  
    }  

    nav a {  
        color: var(--text-color);  
        text-decoration: none;  
        transition: color 0.3s;  
    }  

    nav a:hover {  
        color: var(--primary-color);  
    }  

    /* Hero Section */  
    .hero {  
        height: 80vh;  
        display: flex;  
        flex-direction: column;  
        justify-content: center;  
        align-items: center;  
        text-align: center;  
        padding: 0 20px;  
        background: radial-gradient(circle at center, #1e293b 0%, #0f172a 100%);  
    }  

    .hero h2 {  
        font-size: 3rem;  
        margin-bottom: 10px;  
        color: #ffffff;  
    }  

    .hero p {  
        font-size: 1.2rem;  
        max-width: 600px;  
        margin-bottom: 30px;  
        color: var(--accent-color);  
    }  

    .btn {  
        display: inline-block;  
        padding: 12px 24px;  
        background-color: var(--primary-color);  
        color: #0f172a;  
        text-decoration: none;  
        border-radius: 5px;  
        font-weight: bold;  
        transition: transform 0.2s, background-color 0.2s;  
        margin: 5px;  
    }  

    .btn:hover {  
        background-color: var(--accent-color);  
        transform: translateY(-3px);  
    }  

    .btn-outline {  
        background-color: transparent;  
        color: var(--primary-color);  
        border: 2px solid var(--primary-color);  
    }  

    .btn-outline:hover {  
        background-color: var(--primary-color);  
        color: #0f172a;  
    }  

    /* Sections */  
    section {  
        padding: 80px 20px;  
        max-width: 1000px;  
        margin: 0 auto;  
    }  

    h3 {  
        font-size: 2rem;  
        margin-bottom: 40px;  
        color: #ffffff;  
        border-bottom: 2px solid var(--primary-color);  
        display: inline-block;  
        padding-bottom: 5px;  
    }  

    /* Skills */  
    .skills-grid {  
        display: flex;  
        flex-wrap: wrap;  
        gap: 10px;  
    }  

    .skill-tag {  
        background-color: var(--secondary-color);  
        padding: 8px 15px;  
        border-radius: 20px;  
        font-size: 0.9rem;  
        border: 1px solid #334155;  
        transition: border-color 0.3s;  
    }  

    .skill-tag:hover {  
        border-color: var(--primary-color);  
    }  

    /* Projects */  
    .project-card {  
        background-color: var(--secondary-color);  
        padding: 25px;  
        border-radius: 10px;  
        margin-bottom: 20px;  
        border-left: 4px solid var(--primary-color);  
        transition: transform 0.3s;  
    }  

    .project-card:hover {  
        transform: translateX(10px);  
    }  

    .project-card h4 {  
        color: #ffffff;  
        margin-bottom: 10px;  
        font-size: 1.3rem;  
    }  

    /* Experience */  
    .exp-item {  
        margin-bottom: 30px;  
        padding-left: 20px;  
        border-left: 2px solid #334155;  
        position: relative;  
    }  

    .exp-item::before {  
        content: '';  
        position: absolute;  
        left: -6px;  
        top: 5px;  
        width: 10px;  
        height: 10px;  
        background-color: var(--primary-color);  
        border-radius: 50%;  
    }  

    .exp-item h4 {  
        font-size: 1.2rem;  
        color: #ffffff;  
    }  

    .exp-item .company {  
        color: var(--primary-color);  
        font-weight: bold;  
    }  

    .exp-item .date {  
        font-size: 0.9rem;  
        color: #94a3b8;  
        margin-bottom: 10px;  
        display: block;  
    }  

    /* Education & Certs */  
    .edu-item {  
        margin-bottom: 20px;  
    }  

    .edu-item h4 {  
        color: #ffffff;  
    }  

    /* Footer */  
    footer {  
        text-align: center;  
        padding: 40px 20px;  
        background-color: var(--secondary-color);  
        border-top: 1px solid #334155;  
    }  

    footer a {  
        color: var(--primary-color);  
        text-decoration: none;  
    }  

    /* Mobile */  
    @media (max-width: 768px) {  
        nav {  
            flex-direction: column;  
            gap: 15px;  
        }  
        .hero h2 {  
            font-size: 2rem;  
        }  
    }  
</style>

</head>  
<body>  <!-- Navigation -->  
<nav>  
    <h1>Donsen Hove</h1>  
    <ul>  
        <li><a href="#about">About</a></li>  
        <li><a href="#skills">Skills</a></li>  
        <li><a href="#projects">Projects</a></li>  
        <li><a href="#experience">Experience</a></li>  
        <li><a href="#education">Education</a></li>  
    </ul>  
</nav>  

<!-- Hero Section -->  
<div class="hero" id="about">  
    <h2>IT Professional & System Administrator</h2>  
    <p>Specializing in Cloud Technologies, Cybersecurity, and Technical Support. Dedicated to securing networks, optimizing system performance, and delivering top-tier IT solutions.</p>  
    <div>  
        <a href="mailto:hovedonsen@gmail.com" class="btn">Contact Me</a>  
        <a href="https://www.linkedin.com/in/donsen-hove-770829267" target="_blank" class="btn btn-outline">LinkedIn Profile</a>  
    </div>  
</div>  

<!-- Skills Section -->  
<section id="skills">  
    <h3>Technical Skills</h3>  
    <div class="skills-grid">  
        <span class="skill-tag">Windows 11 & Server</span>  
        <span class="skill-tag">AWS & Azure</span>  
        <span class="skill-tag">Advanced Linux</span>  
        <span class="skill-tag">Cisco Networking</span>  
        <span class="skill-tag">Ethical Hacking</span>  
        <span class="skill-tag">Penetration Testing</span>  
        <span class="skill-tag">Firewalls & VPNs</span>  
        <span class="skill-tag">Group Policy Management</span>  
        <span class="skill-tag">Python Scripting</span>  
        <span class="skill-tag">Database Analysis</span>  
        <span class="skill-tag">Hardware Troubleshooting</span>  
        <span class="skill-tag">Security Operations</span>  
    </div>  
</section>  

<!-- Projects Section -->  
<section id="projects">  
    <h3>Key Projects</h3>  
      
    <div class="project-card">  
        <h4>Promised Land File Server & AWS Cloud Integration</h4>  
        <p>Deployed a secure file server integrated with AWS EC2 instances for remote cloud access. Configured firewalls, applied system updates, and managed Group Policies (GPOs) to enforce user read/write access rights and security permissions.</p>  
    </div>  

    <div class="project-card">  
        <h4>Cybersecurity & Ethical Hacking Lab (Metasploitable)</h4>  
        <p>Conducted penetration testing and ethical hacking exercises in a controlled Metasploitable lab environment. Utilized VPNs and various penetration testing tools to identify vulnerabilities, exploit systems, and simulate real-world cyberattacks.</p>  
    </div>  
</section>  

<!-- Experience Section -->  
<section id="experience">  
    <h3>Professional Experience</h3>  

    <div class="exp-item">  
        <h4>Auditor</h4>  
        <span class="company">Bloom/Springboard (contracted by FamilySearch.org)</span>  
        <span class="date">2024 – 2025 | Remote</span>  
        <ul>  
            <li>Consistently exceeded daily targets by over 90% and met all monthly goals.</li>  
            <li>Led mid-week team meetings to reinforce work policies and target achievement.</li>  
            <li>Maintained 80%+ quality and quantity standards set by the team lead.</li>  
        </ul>  
    </div>  

    <div class="exp-item">  
        <h4>Technical Support Engineer</h4>  
        <span class="company">Tech Innov | Harare, Zimbabwe</span>  
        <span class="date">2023 – 2024</span>  
        <ul>  
            <li>Provided technical support to 100+ customers weekly via phone, email, and remote sessions.</li>  
            <li>Troubleshot hardware and software issues, delivering timely solutions.</li>  
            <li>Installed, configured, and maintained computer systems and network equipment for 50+ customers monthly.</li>  
            <li>Drove process improvements that increased efficiency by 20%.</li>  
        </ul>  
    </div>  
</section>  

<!-- Education Section -->  
<section id="education">  
    <h3>Education & Certifications</h3>  

    <div class="edu-item">  
        <h4>Bachelor of Applied Science in Information Technology — System Administration</h4>  
        <p>Ensign College | Expected Graduation: 2026</p>  
    </div>  

    <div class="edu-item">  
        <h4>Certificate — Technical Support Engineer</h4>  
        <p>Ensign College, Harare, Zimbabwe</p>  
    </div>  

    <div class="edu-item">  
        <h4>TestOut Client Pro</h4>  
        <p>Issued: June 2024 | Validated skills in Windows 11 installation, Group Policy, network connectivity, and system recovery.</p>  
    </div>  
      
    <div class="edu-item">  
        <h4>AWS Cloud Practitioner</h4>  
    </div>  
      
    <div class="edu-item">  
        <h4>Cisco Networking Fundamentals</h4>  
    </div>  
</section>  

<!-- Footer -->  
<footer>  
    <p>&copy; 2024 Donsen Hove. Built with passion for IT.</p>  
    <p>  
        <a href="mailto:hovedonsen@gmail.com">hovedonsen@gmail.com</a> |   
        <a href="https://www.linkedin.com/in/donsen-hove-770829267" target="_blank">LinkedIn</a>  
    </p>  
</footer>

</body>  
</html>
