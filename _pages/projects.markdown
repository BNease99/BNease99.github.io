---
permalink: /projects/
title: "Projects"
layout: single  # Add this line!
---

    

## My Projects

{% for project in site.projects %}
  {% include project_card.html project=project %}
{% endfor %}