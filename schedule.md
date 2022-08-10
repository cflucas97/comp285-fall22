---
layout: page
title: Meeting Times
description: The weekly event schedule.
---

## Weekly Schedule

For the latest details, see our [Course Calendar](https://calendar.google.com/calendar/u/0/embed?src=q28b585afss5ag6t7793nc16l4@group.calendar.google.com&ctz=America/New_York)

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
