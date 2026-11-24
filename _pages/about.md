---
layout: about
title: About
permalink: /
subtitle: Research Assistant | PhD Student in Computer Engineering at <a href="https://mf-bm.gazi.edu.tr/">Gazi University</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false


selected_papers: false
social: true

announcements:
  enabled: false # news is rendered in the page body below, followed by the service section

latest_posts:
  enabled: false
---
<link rel="stylesheet" href="{{ '/assets/css/site-custom.css' | relative_url | bust_file_cache }}">
<style>
h2 { text-transform: capitalize; }
:root { --global-theme-color: #402599; --global-hover-color: #1C1338; }
html[data-theme="dark"] { --global-theme-color: #402599; --global-hover-color: #1C1338; }
a, a:visited { color: var(--global-theme-color); }
a:hover { color: var(--global-hover-color); }
</style>


I am a Ph.D. student in Computer Engineering at Gazi University, researching AI-enabled network security. My Master's thesis focused on large language model-based intrusion detection in Software-Defined IoT networks.

I am always happy to connect on AI, network security, and next-generation networks.

<h2>research focus</h2>

- **LLM-based intrusion detection:** Using encoder-only, decoder-only and encoder-decoder language models to detect and classify network attacks, with a focus on generalizing across datasets and detecting previously unseen attacks.
- **Security of software-defined networks and IoT:** Detecting attacks such as DDoS in SDN and Software-Defined IoT environments with machine learning and deep learning models.
- **LLMs for security operations:** Exploring how language models can support log analysis, threat intelligence, rule generation and security analysts.

<!-- News (moved here from the layout so the service section can follow it) -->
<div style="clear: both;"></div>
<h2><a href="{{ '/news/' | relative_url }}" style="color: inherit">news</a></h2>
<div class="section-card">
{% include news.liquid limit=true %}
</div>

<!-- Reviewing and conference service -->
<h2>reviewing &amp; service</h2>
<p class="section-subtitle">Peer reviewing for journals and conferences.</p>
<div class="row service-cards">
  <div class="col-md-6">
    <div class="section-card">
      <h3>Journal Reviewer</h3>
      <ul>
        <li>Integrated Computer-Aided Engineering<span class="issn">ISSN 1069-2509 · e-ISSN 1875-8835</span></li>
        <li>Science, Engineering and Technology<span class="issn">ISSN 2744-2527</span></li>
        <li>Bilişim Teknolojileri Dergisi (Journal of Information Technologies)<span class="issn">ISSN 1307-9697 · e-ISSN 2147-0715</span></li>
        <li>İstanbul Ticaret Üniversitesi Girişimcilik Dergisi (Journal of Entrepreneurship)<span class="issn">ISSN 2536-4456 · e-ISSN 2717-7416</span></li>
      </ul>
    </div>
  </div>
  <div class="col-md-6">
    <div class="section-card">
      <h3>Conference Reviewer</h3>
      <ul>
        <li>31st European Conference on Software Process Improvement (EuroSPI 2024)</li>
      </ul>
    </div>
  </div>
</div>
