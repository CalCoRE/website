---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The CoRE Lab is composed of educational researchers, computer scientists, and design specialists dedicated to developing expressive statistical computing environments and curriculum designs for classrooms. Meet our team members below.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'alumni'" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

Our research is done in close partnership with school districts, teachers, and university researchers. We welcome inquiries from scholars, educators, and organizations interested in collaborating with us on learning sciences research and STEM design.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
