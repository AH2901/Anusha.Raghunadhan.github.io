---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/hero-bg.jpg
  actions:
    - label: "<i class='fas fa-code-branch'></i> View Projects"
      url: "#projects"
    - label: "<i class='fas fa-envelope'></i> Contact"
      url: "#contact"

excerpt: "9+ Years of .NET & React Architecture. <br /> Building seamless enterprise solutions in Vancouver."

feature_row:
  - image_path: /assets/images/dotnet-icon.png
    alt: ".NET Core"
    title: "Backend Architecture"
    excerpt: "Robust distributed systems and microservices built with .NET 8."
  - image_path: /assets/images/react-icon.png
    alt: "React"
    title: "Modern Frontend"
    excerpt: "Highly interactive SPAs and SPFx components using React & TypeScript."
  - image_path: /assets/images/azure-icon.png
    alt: "Cloud"
    title: "Cloud & DevOps"
    excerpt: "Automated CI/CD workflows and Azure cloud infrastructure."
---

{% include feature_row %}

<section id="projects" style="padding-top: 50px;">
  {% include feature_row id="feature_row_projects" %}
</section>

<div class="project-filters">
  <button class="btn btn--primary" onclick="filterProjects('all')">All</button>
  <button class="btn btn--info" onclick="filterProjects('dotnet')">.NET</button>
  <button class="btn btn--info" onclick="filterProjects('react')">React</button>
</div>

<div id="project-grid" style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 20px; margin-top: 20px;">
  <div class="project-item dotnet">
    <h4>Enterprise API</h4>
    <p>Architecture for global data sync.</p>
  </div>
  <div class="project-item react">
    <h4>SPFx Dashboard</h4>
    <p>Real-time analytics in M365.</p>
  </div>
</div>

<script>
function filterProjects(tech) {
  const items = document.querySelectorAll('.project-item');
  items.forEach(item => {
    if (tech === 'all' || item.classList.contains(tech)) {
      item.style.display = 'block';
    } else {
      item.style.display = 'none';
    }
  });
}
</script>

