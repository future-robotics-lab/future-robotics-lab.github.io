---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}


{% include section.html background="images/background.jpg" dark=true %}
# PhD Students
{% include list.html data="members" component="portrait" filters="role: phd" %}

{% include section.html %}
# Master Students
{% include list.html data="members" component="portrait" filters="role: msc" %}

{% include section.html background="images/background.jpg" dark=true %}
# Undergraduate Students
{% include list.html data="members" component="portrait" filters="role: ug" %}

{% include section.html background="images/background.jpg" dark=false %}

<details>
  <summary style="cursor: pointer; list-style: none; outline: none; text-align: center;">
    <h1>Alumni</h1> 
    <p style="font-size: 1.1rem; color: gray; margin-top: -10px; text-align: center;">(Click to expand)</p>
  </summary>

  <div style="margin-top: 20px;">
    {% include list.html data="members" component="portrait" filters="role: alumni" %}
  </div>
</details>



{% include section.html %}
We are looking for WPI students to join our lab for exciting research in medical robotics, software and devices. Fill out the [application form](https://wpi.qualtrics.com/jfe/form/SV_40jUQ0KpXpH6kHs) and we will reach out.



{% include carousel.html width="1000px" height="600px" images="/images/gatherings/christmass_24.jpg,/images/posts/Spring25_team.jpg,/images/posts/Summer25_adam.jpg,/images/gatherings/Watatic_09_27_25.JPEG" captions="FuTURE Lab Dinner Dec 11th 2024,FuTURE Lab Team Spring 2025,Welcome EERE Summer Program Student - Adam Hueil,FuTURE Lab Hike Sept 27th 2025" %}



