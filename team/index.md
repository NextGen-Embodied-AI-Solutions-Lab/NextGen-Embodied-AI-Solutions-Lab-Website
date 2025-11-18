---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# Team

{% include section.html %}

## Principal Investigator

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" style="square" %}

## Team Members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and role != 'alumni'" style="square" %}

## Past Members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'alumni'" style="square" %}
