---
layout: default
title: Jesse Rogers' Portfolio
---
## Projects
Swipe to see more
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
My background is in economics and finance, and I've tutored math since 1999. I've been an avid gamer even before that (Simcity, Fallout, Civ, Total War, Skyrim, Starcraft, etc...). In 2020 I started coding as a hobby, and since then most of my free time has been spent on Codingame. I'm focused on making education more fun and interesting. My work email is <a href="mailto:rogersjj@palmbeachstate.edu">rogersjj@palmbeachstate.edu</a>. For free tutoring, visit us at <a href="https://www.palmbeachstate.edu/slc/" target="_blank">https://www.palmbeachstate.edu/slc/</a> (currently enrolled PBSC students only).
