---
layout: default
---

<!-- Hero -->
<section id="home" class="hero">
  <div>
    <h1>Hi, I'm <span class="highlight">{{ site.title }}</span></h1>
    <p style="font-size:1.4rem; margin:20px 0;">Full Stack Developer &amp; Designer</p>
    <div>
      <a href="#projects" class="btn primary">See My Projects</a>
      <a href="#contact" class="btn" style="background:#fff; color:#333;">Get In Touch</a>
    </div>
  </div>
</section>

<!-- About -->
<section id="about" class="section">
  <h2>About Me</h2>
  <p style="max-width:700px; margin:0 auto; font-size:1.15rem; text-align:center;">
    I'm a passionate developer who loves building clean, fast, and modern web experiences. 
    Currently focused on creating beautiful single-page applications and delightful user interfaces.
  </p>
</section>

<!-- Projects -->
<section id="projects" class="section">
  <h2>Featured Projects</h2>
  <div class="projects-grid">
    <div class="project-card">
      <h3>Project One</h3>
      <p>A modern web app built with Jekyll and vanilla JavaScript. Fully responsive and SPA-like navigation.</p>
      <a href="#" class="btn primary" style="font-size:0.95rem; padding:10px 20px;">View Project</a>
    </div>
    <div class="project-card">
      <h3>Project Two</h3>
      <p>Beautiful portfolio website with smooth animations and dark mode support.</p>
      <a href="#" class="btn primary" style="font-size:0.95rem; padding:10px 20px;">View Project</a>
    </div>
    <div class="project-card">
      <h3>Project Three</h3>
      <p>AI-powered tool that helps users generate stunning visuals.</p>
      <a href="#" class="btn primary" style="font-size:0.95rem; padding:10px 20px;">View Project</a>
    </div>
  </div>
</section>

<!-- Contact -->
<section id="contact" class="section">
  <h2>Let's Connect</h2>
  <p style="text-align:center; font-size:1.2rem;">
    I'm always excited to work on new projects.<br>
    Feel free to reach out!
  </p>
  <div style="text-align:center; margin-top:2rem;">
    <a href="mailto:{{ site.email }}" class="btn primary">Send me an Email</a>
  </div>
</section>
