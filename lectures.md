---
layout: page
title: Lectures
description: Detailed lecture information
nav_order: 1
---

## General Lecture Information

Lecture will be held in-person in Graham Hall 208. The course staff wil make an effort to make lecture recordings available. If you cannot attend lecture, it will be broadcast on [Zoom](https://ncat.zoom.us/j/9728635650). However, lectures are optimized for in-class experience.  

Recordings for the lectures will be posted here as part of the Lecture resources when available.

## Lectures

{% assign lectures = site.lectures %}
{% for lecture in lectures %}
{{ lecture }}
{% endfor %}