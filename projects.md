---
title: Projects
layout: page
permalink: /projects/
collection: projects
entries_layout: list
---

Here's a list of some projects I've done so far (some still in progress!)

{% for project in site.projects reversed %}

## [{{ project.title }}]({{ project.url }})
##### {{ project.sub_title }}

{{ project.excerpt | markdownify }}

[Read more.]({{ project.url }})

{% endfor %}
