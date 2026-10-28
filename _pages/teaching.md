---
layout: page
permalink: /Teaching/
title: Teaching
description: Course materials, schedules, and resources for classes taught.
nav: true
nav_order: 6
calendar: true
---
<style>
h2 { text-transform: capitalize; }
:root { --global-theme-color: #402599; --global-hover-color: #1C1338; }
html[data-theme="dark"] { --global-theme-color: #402599; --global-hover-color: #1C1338; }
a, a:visited { color: var(--global-theme-color); }
a:hover { color: var(--global-hover-color); }
</style>
This page displays a collection of courses with detailed schedules, materials, and resources. You can organize your courses by years, terms, or topics.

{% include calendar.liquid calendar_id='test@gmail.com' timezone='Asia/Shanghai' %}

{% include courses.liquid %}
