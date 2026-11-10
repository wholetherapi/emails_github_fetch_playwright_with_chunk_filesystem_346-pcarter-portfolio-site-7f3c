---
layout: default
title: Projects
---

Selected projects and publications from the group.

{% for project in site.projects %}
{% include project-card.html project=project %}
{% endfor %}
