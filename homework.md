---
layout: page
title: Homework
description: Detailed homework information.
nav_order: 2
---

## General Homework Information

Homeworks will be assigned \~weekly. See the schedule for specific dates. In general homework will be released after lecture on Tuesday and due the following Thursday or vice-versa.

Generally, the homework will be due *at 1:59pm* (right before lecture begins). They will include both conceptual and coding components. *The lowest homework will be dropped from your grade*; however, an earnest attempt must be made on each homework assignemnt. An unsubmitted, blank, or haphazard solution is not eligible to be dropped.

See our [Homework Policy]({{ "/policies/#homework-policy"| relative_url }}) for more detail.

## Homework Assignments

{% assign homework = site.homework %}
{% for assignment in homework %}
{{ assignment }}
{% endfor %}