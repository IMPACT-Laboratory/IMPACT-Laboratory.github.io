---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet our team of motivated contributors that are breaking new ground in combustion and propulsion research.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

We're a small, growing team that's looking for new student members. Interested in making a difference in combustion technology through scientific discovery? Contact us using [this form](https://forms.gle/3MmBKwLqC3hhEVdH6).

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