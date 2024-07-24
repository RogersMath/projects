---
layout: default
title: Jesse Rogers' Portfolio
---

## Projects

<div class="project-grid">
  {% for project in site.data.projects %}
    <div class="project-card">
      <img src="{{ project.image | relative_url }}" alt="{{ project.title }} Icon">
      <h3>{{ project.title }}</h3>
      <p>Associated Course: {{ project.course }}</p>
      <a href="{{ project.link }}" class="play-button">Play Now</a>
    </div>
  {% endfor %}
</div>

## About Me

I'm Jesse Rogers, a Learning Lab Coordinator at Palm Beach State College, as well as a Podcaster, Writer, and Indie Game Developer. I'm focused on making education more fun and interesting. My work email is [ rogersjj@palmbeachstate.edu ]. For free tutoring, visit us at [ https://www.palmbeachstate.edu/slc/ ] (currently enrolled PBSC students only).
