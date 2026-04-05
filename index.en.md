---
layout: none
title: "Home (English)"
permalink: /index.en.html
---

<div align="center">
  <img src="{{ site.author.avatar | default: 'profile.png' }}" alt="{{ site.author.name }}" style="width:140px;border-radius:50%;margin-bottom:10px;box-shadow:0 2px 8px #ccc;">
  
  <h1 style="margin-bottom:0.2em;">{{ site.author.name }}</h1>
  <div style="font-size:1.1em;color:#666;">{{ site.author.bio }}</div>
  <div style="font-size:1em;color:#888;">{{ site.author.employer }} | {{ site.author.location }}</div>
  <div style="margin:10px 0 15px 0;">
    <a href="mailto:{{ site.author.email }}">Email</a>
    {% if site.author.googlescholar %} | <a href="{{ site.author.googlescholar }}">Google Scholar</a>{% endif %}
    {% if site.author.github %} | <a href="https://github.com/{{ site.author.github }}">GitHub</a>{% endif %}
    {% if site.author.linkedin %} | <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a>{% endif %}
  </div>
  <div style="margin-bottom:1em;">
    <a href="/index.en.html">English</a>
  </div>
</div>

<div style="max-width:700px;margin:0 auto;">
<h2>About Me</h2>
<p>{{ site.description }}</p>

<h2>Research Interests</h2>
<ul>
  <li>Operations Management</li>
  <li>Supply Chain Analytics</li>
  <li>Data-driven Decision Making</li>
</ul>

<h2>News</h2>
<ul>
  <li>Welcome to my academic homepage!</li>
  <li>Feel free to contact me for collaboration.</li>
</ul>

<h2>Selected Publications</h2>
<ul>
  <li>Coming soon...</li>
</ul>
</div>
