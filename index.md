---
layout: home
title: ""
---

<div class="hero">
  <div class="hero-prompt">> whoami</div>
  <h1 class="hero-title">Daily <span class="green">Cyber</span> Intelligence<br>& Security Journey</h1>
  <p class="hero-sub">AI-powered threat briefings every morning. Documenting my path from the kitchen to the SOC — one project, cert, and breach at a time.</p>
  <div class="hero-status">
    <span class="status-dot green-dot"></span> Agent active &nbsp;|&nbsp;
    <span class="status-dot amber-dot"></span> Updated daily &nbsp;|&nbsp;
    <a href="https://github.com/CyberJean98/CyberJean.github.io">View on GitHub</a>
  </div>
</div>

---

## Latest Threat Intel

<p class="section-sub">> tail -f /var/log/daily-intel.log</p>

{% for post in site.posts limit:5 %}
<div class="post-card">
  <div class="post-card-meta">{{ post.date | date: "%Y-%m-%d" }}</div>
  <a class="post-card-title" href="{{ post.url }}">{{ post.title }}</a>
  <p class="post-card-excerpt">{{ post.excerpt | strip_html | truncate: 120 }}</p>
</div>
{% endfor %}

---

## Projects

<p class="section-sub">> ls ~/projects/</p>

<div class="card">
  <div class="card-header">
    <span class="card-title">Home SOC Lab (Wazuh)</span>
    <span class="status-active">[active]</span>
  </div>
  <p>SIEM deployed on a Lenovo ThinkCentre M700, ingesting logs from Ubuntu and Windows endpoints on my home network.</p>
  <div class="card-tags">
    <span class="tag">Wazuh</span>
    <span class="tag">SIEM</span>
    <span class="tag">Ubuntu</span>
  </div>
</div>

<div class="card">
  <div class="card-header">
    <span class="card-title">Pwnagotchi Build</span>
    <span class="status-building">[building]</span>
  </div>
  <p>Raspberry Pi Zero 2W learning WPA handshakes with Waveshare e-Paper display and AI-powered brain.</p>
  <div class="card-tags">
    <span class="tag">Raspberry Pi</span>
    <span class="tag">WiFi Security</span>
    <span class="tag">Python</span>
  </div>
</div>

<div class="card">
  <div class="card-header">
    <span class="card-title">This Site — AI News Agent</span>
    <span class="status-active">[active]</span>
  </div>
  <p>GitHub Actions + Gemini AI pipeline that researches and publishes daily cybersecurity briefings automatically.</p>
  <div class="card-tags">
    <span class="tag">GitHub Actions</span>
    <span class="tag">Gemini AI</span>
    <span class="tag">Jekyll</span>
  </div>
</div>

<a class="see-more" href="/projects/">View all projects ></a>

---

## Certifications

<p class="section-sub">> cat ~/certs/progress.log</p>

<div class="cert-grid">
  <div class="cert-card">
    <div class="cert-name">Google Cybersecurity</div>
    <div class="cert-provider">Google / Coursera</div>
    <span class="status-done">[completed]</span>
  </div>
  <div class="cert-card">
    <div class="cert-name">CompTIA Security+</div>
    <div class="cert-provider">CompTIA</div>
    <span class="status-building">[in progress]</span>
  </div>
  <div class="cert-card">
    <div class="cert-name">TryHackMe SOC Level 1</div>
    <div class="cert-provider">TryHackMe</div>
    <span class="status-building">[in progress]</span>
  </div>
  <div class="cert-card">
    <div class="cert-name">CompTIA Network+</div>
    <div class="cert-provider">CompTIA</div>
    <span class="status-active">[planned]</span>
  </div>
</div>

---

## About Me

<p class="section-sub">> cat ~/about.txt</p>

<div class="card">
  <p>I'm <span class="green">Jean Berrios-Marquez</span>, transitioning from lead line cook in Worcester, MA to cybersecurity professional. I'm building in public, learning every day, and documenting the journey so recruiters can see not just what I know — but how I think and what I'm capable of building.</p>
  <p>Passionate about <span class="green">threat intelligence</span>, defensive security, and proving that non-traditional paths lead to great careers in cybersecurity.</p>
  <div class="card-tags" style="margin-top:12px;">
    <a href="https://www.linkedin.com/in/jean-berrios-marquez-2617a73b2" class="tag">LinkedIn</a>
    <a href="https://github.com/CyberJean98" class="tag">GitHub</a>
  </div>
</div>

---

## Credits & Gratitude

<p class="section-sub">> cat ~/credits.txt</p>

<div class="card">
  <p class="credits-intro">This journey wouldn't be possible without the people who took the time to help, teach, and encourage me. Thank you.</p>
</div>

<div class="card">
  <div class="card-header">
    <span class="card-title">Name Here</span>
  </div>
  <p>What they helped you with or why you're grateful for them.</p>
</div>

<div class="card">
  <div class="card-header">
    <span class="card-title">Name Here</span>
  </div>
  <p>What they helped you with or why you're grateful for them.</p>
</div>

<div class="card">
  <div class="card-header">
    <span class="card-title">Claude (Anthropic AI)</span>
  </div>
  <p>For helping me build this site, debug my GitHub Actions agent, and think through problems at 1am when no one else was around.</p>
</div>

---

## Discussion

<p class="section-sub">> open https://github.com/CyberJean98/CyberJean.github.io/discussions</p>

<div class="card">
  <p>Have thoughts on today's threat intel? Questions about my projects? Drop a comment on GitHub Discussions — I read everything.</p>
  <a href="https://github.com/CyberJean98/CyberJean.github.io/discussions" class="btn">Join the Discussion ></a>
</div>
