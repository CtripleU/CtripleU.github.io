---
layout: default
title: "Debug Projects Sorting"
permalink: /debug-projects/
---

<h1>Debug Projects Sorting</h1>

{% assign sorted_projects = site.projects | sort: 'date' | reverse %}
<ul>
{% for project in sorted_projects %}
  <li>{{ project.date | date: "%Y-%m-%d" }} — {{ project.title }}</li>
{% endfor %}
</ul>