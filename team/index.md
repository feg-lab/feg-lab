---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are an interdisciplinary and international group of undergrads, graduate students and staff.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'prospective'" %}

{%
  include section.html
  dark=true
  size=full
  title="Prospective students and postdocs"
%}

{% include list.html data="members" component="portrait" filter="role == 'prospective'" %}