---
layout: page
title: Projects
permalink: /projects/
---

<p class="section-sub">> ls ~/projects/</p>

## Cybersecurity Labs & Builds

<div class="cert-card-full">
  <div class="cert-card-header">
    <div>
      <div class="cert-name-lg">Home SOC Lab (Wazuh)</div>
      <div class="cert-provider-lg">Built on a Lenovo ThinkCentre M700</div>
    </div>
    <span class="status-active">[active]</span>
  </div>
  <p>Deployed a functional SIEM to monitor home network traffic. Currently ingesting logs from Ubuntu and Windows endpoints, detecting threats and building detection rules in a real environment.</p>
  <div class="card-tags">
    <span class="tag">Wazuh</span>
    <span class="tag">SIEM</span>
    <span class="tag">Ubuntu</span>
    <span class="tag">Windows</span>
    <span class="tag">Threat Detection</span>
  </div>
  <div class="cert-verify">
    <span class="verify-label">> repo:</span>
    <a href="https://github.com/Retroflowing/SOC-Lab" target="_blank">View on GitHub</a>
  </div>
</div>

<div class="cert-card-full">
  <div class="cert-card-header">
    <div>
      <div class="cert-name-lg">Pwnagotchi Build</div>
      <div class="cert-provider-lg">Built on a Raspberry Pi Zero 2W</div>
    </div>
    <span class="status-building">[building]</span>
  </div>
  <p>Built a Pwnagotchi to learn the mechanics of WPA handshakes and deauthentication. Running on a Raspberry Pi Zero 2W with a Waveshare e-Paper display and AI-powered brain. My first ever hardware cybersecurity project — started with the guidance of my mentor Jeremy Anderson.</p>
  <div class="card-tags">
    <span class="tag">Raspberry Pi</span>
    <span class="tag">WiFi Security</span>
    <span class="tag">WPA</span>
    <span class="tag">Hardware</span>
    <span class="tag">Python</span>
  </div>
  <div class="cert-verify">
    <span class="verify-label">> repo:</span>
    <a href="https://github.com/Retroflowing/Pwnagotchi" target="_blank">View on GitHub</a>
  </div>
</div>

<div class="cert-card-full">
  <div class="cert-card-header">
    <div>
      <div class="cert-name-lg">SYN Flood DoS Attack — Incident Response Report</div>
      <div class="cert-provider-lg">Google Cybersecurity Certificate — Network Analysis Lab</div>
    </div>
    <span class="status-done">[completed]</span>
  </div>
  <p>Analyzed a real-world SYN flood denial of service attack using Wireshark TCP logs. Identified malicious traffic from IP 203.0.113.0 sending over 150 incomplete TCP handshake requests within seconds, overwhelming the web server on port 443. Produced a full incident response report documenting the attack vector, impact on business continuity, and recommendations for mitigation.</p>
  <div class="card-tags">
    <span class="tag">Wireshark</span>
    <span class="tag">TCP/IP</span>
    <span class="tag">DoS Attack</span>
    <span class="tag">Incident Response</span>
    <span class="tag">Network Analysis</span>
    <span class="tag">Google Certificate</span>
  </div>
  <div class="cert-verify">
    <span class="verify-label">> files:</span>
    <a href="/assets/projects/cybersecurity-incident-report.pdf" target="_blank">Incident Report</a>
    &nbsp;|&nbsp;
    <a href="/assets/projects/wireshark-tcp-log.pdf" target="_blank">Wireshark Log</a>
  </div>
</div>

---

## Automation & Engineering

<div class="cert-card-full">
  <div class="cert-card-header">
    <div>
      <div class="cert-name-lg">Daily Cyber News Agent</div>
      <div class="cert-provider-lg">This Site — AI Powered Pipeline</div>
    </div>
    <span class="status-active">[active]</span>
  </div>
  <p>Built a fully automated GitHub Actions pipeline that calls the Google Gemini AI API every morning to research and write a professional cybersecurity threat briefing. The post is automatically committed to this repo and deployed via Jekyll to GitHub Pages — zero manual effort required.</p>
  <div class="card-tags">
    <span class="tag">GitHub Actions</span>
    <span class="tag">Gemini AI</span>
    <span class="tag">Jekyll</span>
    <span class="tag">Python</span>
    <span class="tag">YAML</span>
    <span class="tag">Automation</span>
  </div>
  <div class="cert-verify">
    <span class="verify-label">> repo:</span>
    <a href="https://github.com/CyberJean98/CyberJean.github.io" target="_blank">View on GitHub</a>
  </div>
</div>

<div class="cert-card-full">
  <div class="cert-card-header">
    <div>
      <div class="cert-name-lg">Serverless Threat Intelligence Pipeline</div>
      <div class="cert-provider-lg">Architecture & Design Project</div>
    </div>
    <span class="status-building">[in progress]</span>
  </div>
  <p>Designing a fully automated, zero-touch pipeline that aggregates, summarizes, and publishes daily cybersecurity threat intelligence using AI and continuous integration. Built on GitHub Actions, Google Gemini 2.5 Flash API, Jekyll, and GitHub Pages.</p>
  <div class="card-tags">
    <span class="tag">GitHub Actions</span>
    <span class="tag">Python</span>
    <span class="tag">Bash</span>
    <span class="tag">YAML</span>
    <span class="tag">Gemini AI</span>
    <span class="tag">CI/CD</span>
  </div>
  <div class="cert-verify">
    <span class="verify-label">> architecture:</span>
    <span style="color: #ffffff50; font-size: 11px;">
      Automated Trigger → API Integration → Data Parsing → Version Control → Static UI
    </span>
  </div>
  <div style="margin-top: 12px;">
    <p style="color: #ffffff60; font-size: 12px; margin-bottom: 6px;">Challenges Overcome:</p>
    <ul style="color: #ffffff50; font-size: 12px; margin: 0; padding-left: 16px;">
      <li>Overcame AI formatting hallucinations using strict prompt boundaries and Python JSON-to-Markdown sanitization</li>
      <li>Resolved merge conflicts in headless runner environment using forced-update branch logic</li>
      <li>Ensured pipeline operates on Principle of Least Privilege with API keys secured via GitHub Secrets</li>
    </ul>
  </div>
</div>

---

*Documenting my journey from Worcester's kitchens to the SOC.* 🔐
