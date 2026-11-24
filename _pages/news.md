---
layout: page
title: News
permalink: /news/
---
<link rel="stylesheet" href="{{ '/assets/css/site-custom.css' | relative_url }}">
<style>
:root { --global-theme-color: #402599; --global-hover-color: #1C1338; }
html[data-theme="dark"] { --global-theme-color: #402599; --global-hover-color: #1C1338; }
a, a:visited { color: var(--global-theme-color); }
a:hover { color: var(--global-hover-color); }
</style>

{% include news.liquid %}
