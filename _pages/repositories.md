---
layout: page
permalink: /repositories/
title: Software
description: A collection of my open-source scientific software projects and contributions.
nav: true
nav_order: 4
---

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
