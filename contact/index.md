---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{%
  include button.html
  type="email"
  text="gpittiglio@wpi.edu"
  link="gpittiglio@wpi.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Lab location (3rd floor)"
  link="https://maps.app.goo.gl/PaHn1YaKtvTx4oti6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/campus_map.png"
  caption="Map of Campus"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/PracticePoint.jpg"
  caption="PracticePoint"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

