---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

I'm looking to hire the founding students for the lab. Come push the boundaries of propulsion and combustion technology using the link at the bottom of the page.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/ZachHeadshot.jpeg" dark=true %}

We're a small, growing team that's looking for new student members. Interested in making a difference in combustion technology through scientific discovery? Contact us using the link below.

{%
  include button.html
  type="link"
  text="Join Our Team"
  link="https://forms.gle/3MmBKwLqC3hhEVdH6"
%}

{% comment %}
{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
{% endcomment %}