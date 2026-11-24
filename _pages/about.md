---
layout: about
title: About
permalink: /
subtitle: PhD Student in Computer Engineering at <a href="https://mf-bm.gazi.edu.tr/">Gazi University</a>

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
<style>
h2 { text-transform: capitalize; }
:root { --global-theme-color: #402599; --global-hover-color: #1C1338; }
html[data-theme="dark"] { --global-theme-color: #402599; --global-hover-color: #1C1338; }
a, a:visited { color: var(--global-theme-color); }
a:hover { color: var(--global-hover-color); }
.service-row { margin-top: 0.5rem; margin-bottom: 1.5rem; }
.service-row h3 { font-size: 1.1rem; font-weight: 600; margin-bottom: 0.75rem; }
.service-row ul { padding-left: 1.1rem; margin-bottom: 0; }
.service-row li { margin-bottom: 0.6rem; }
.service-row .issn { display: block; font-size: 0.85rem; color: var(--global-text-color-light); }
@media (min-width: 768px) { .service-row .service-conf { border-left: 1px solid var(--global-divider-color); padding-left: 1.5rem; } }
</style>


I am a Ph.D. student in Computer Engineering at Gazi University, researching AI-enabled network security. My Master's thesis focused on large language model-based intrusion detection in Software-Defined IoT networks.

I am always happy to connect on AI, network security, and next-generation networks.

<!-- News (moved here from the layout so the service section can follow it) -->
<h2><a href="{{ '/news/' | relative_url }}" style="color: inherit">news</a></h2>
{% include news.liquid limit=true %}

<!-- Reviewing and conference service -->
<h2>reviewing &amp; service</h2>
<div class="row service-row">
  <div class="col-md-6">
    <h3>Journal Reviewer</h3>
    <ul>
      <li>Integrated Computer-Aided Engineering<span class="issn">ISSN 1069-2509 · e-ISSN 1875-8835</span></li>
      <li>Science, Engineering and Technology<span class="issn">ISSN 2744-2527</span></li>
      <li>Bilişim Teknolojileri Dergisi (Journal of Information Technologies)<span class="issn">ISSN 1307-9697 · e-ISSN 2147-0715</span></li>
      <li>İstanbul Ticaret Üniversitesi Girişimcilik Dergisi (Journal of Entrepreneurship)<span class="issn">ISSN 2536-4456 · e-ISSN 2717-7416</span></li>
    </ul>
  </div>
  <div class="col-md-6 service-conf">
    <h3>Conference Reviewer</h3>
    <ul>
      <li>31st European Conference on Software Process Improvement (EuroSPI 2024)</li>
    </ul>
  </div>
</div>
