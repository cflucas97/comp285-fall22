---
layout: page
title: Homework
description: Detailed homework information.
nav_order: 2
---

## General Homework Information

Homeworks will be assigned \~weekly. See the schedule for specific dates. In general homework will be released after lecture on Tuesday and due the following Thursday or vice-versa.

Generally, the homework will be due *at 11:59pm* (right before lecture begins). They will include both conceptual and coding components. *The lowest homework will be dropped from your grade*; however, an earnest attempt must be made on each homework assignemnt. An unsubmitted, blank, or haphazard solution is not eligible to be dropped.

See our [Homework Policy]({{ "/policies/#homework-policy"| relative_url }}) for more detail.

## Homework Assignments

{% assign homework = site.homework %}
{% for assignment in homework %}
{{ assignment }}
{% endfor %}

## Repl.it Homework Starter Code Setup

Repl.it is an IDE that we will use to complete the coding portions of the assignments. Even if you do not plan to use repl.it for writing/developing your solutions, you will need to access the starter code here. 

First, let’s start by getting you an account and joining the right project:

1. If you don’t already have a repl.it account with your “aggies.ncat.edu” email, head over
to the repl.it [homepage](https://replit.com/~). On the top-right, click the ‘Sign Up’ and use your NCAT email
address to sign-up.
2. Complete the registration process (eg, there’s a verification email you should get)
3. Join the COMP 285 Team by following this [link](https://replit.com/teams/join/ymfokyhnvvhzduiczqurvemmuiwwtjxs-comp285-fall22).


Next, let’s get your starter code. 

- From your repl.it homepage, you should have a menu down
the left-hand side of the page (if not, maybe click the hamburger menu to open it?).
- Click
on "Teams" on the lefthand side. You should see ‘COMP 285: Analysis of Algorithms’ under ‘Education’,
as well as the ‘comp285-fall22’ Team Project. See the figure for more information.


- Click on ‘comp285-fall22’, which will take you to the Team Homepage. From there, under
‘Projects’, you should see a link to get started on the homework.
- Clicking it will give you the
starter code, as well as set you up with an online.
If the above does not work, you can also try going directly to the [project link](https://replit.com/@comp285-fall22/HW0).
- How to render a homework assignment properly in Repl.it. [Video](/assets/other/replit.mov)

