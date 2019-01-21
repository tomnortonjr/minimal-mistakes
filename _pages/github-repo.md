---
toc: false
title: Github Repos
permalink: /github-repos/
categories: repo
---

{% for repository in site.github.public_repositories %}
   <i class="fab fa-github-square"></i> [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

