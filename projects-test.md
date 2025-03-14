---
title: "Projects"
permalink: /projects/
layout: page
---

Here are some of my projects:

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})

**{{ project.date | date: "%B %Y" }}**

{{ project.description }}

[View Project]({{ project.link }})

---
{% endfor %}
