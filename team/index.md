---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include section.html %}

{% include section.html background="images/background.jpg" dark=true %}
# PhD Students: looking for students excited to work on medical robots. Reach out to Giovanni Pittiglio with a short CV at gpittiglio@wpi.edu!

{% include list.html data="members" component="portrait" filters="role: phd" %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
