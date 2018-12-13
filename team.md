---
layout: single
title: "About the Team"
gallery:
  - title: "Thiago Gomes"
    image_path: "/assets/images/thiago.jpg"
    caption: "Thiago Gomes"
  - title: "Niklas Hemlin"
    image_path: "/assets/images/niklas.jpg"
  - title: "David French"
    image_path: "/assets/images/david.jpg"
  - title: "Ari Perelman"
    image_path: "/assets/images/ari.jpg"
  - title: "Mikhail Markine"
    image_path: "/assets/images/mikhail.jpg"

---

## Members

{% for team_member in site.team_members %}
  <h2>{{ team_member.name }}</h2>
  <p>{{ team_member.content | markdownify }}</p>
{% endfor %}

{% include gallery id="gallery" %}
