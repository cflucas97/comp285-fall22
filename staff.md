---
layout: page
title: Staff - Student Hours
description: A listing of all the course staff members.
---

## Student Hours

- Student hours schedule can be found on the [COMP 285 Calendar](https://calendar.google.com/calendar/u/0/embed?src=q28b585afss5ag6t7793nc16l4@group.calendar.google.com&ctz=America/New_York).
- Student hours will take place mostly in-person, on-campus. However, a few select office hours will be made available through [Zoom](https://ncat.zoom.us/j/9728635650).

## Professor Hours

This includes the normally "in-person" office hours of:

- Tuesday: 3:30pm - 4:30pm ET in ERIC 331.
- Thursday: 3:30pm - 4:30pm ET in ERIC 331.

Additional online-only office hours are:

- Monday: 1:00pm - 2:00pm ET
- Wednesday: 1:00pm - 2:00pm ET 
- Friday: schedule by [appointment](https://calendly.com/cflucas-ncat/office-hours-1-1)


## TA Student Hours
- Tuesday: 12:00 pm - 1:00 pm ET
- Thursday: 11:00 am - 12:00 pm ET
- Friday: 10:00 am - 11:00 am ET, 12:00 pm - 1:00 pm ET


### Regular Student Hours
TAs will open up their schedule to help students. Different TAs may have different ways of working through students (i.e., in groups or 1 at a time). If the location is getting too crowded, the TA may ask groups of students to work together and ask them to switch rooms. Students can work together while waiting for assistance during student hours.

## Staff Contact

- The best way to reach the staff is by making a private post on [Piazza](https://piazza.com/ncat/fall2022/comp285).

- You may also reach out by emailing directly at [cflucas@ncat.edu](mailto:cflucas@ncat.edu) with any questions or concerns that you do not with to post to [Piazza](https://piazza.com/ncat/fall2022/comp285).

### Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

### Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
