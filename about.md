---
layout: page
title: About Us
description: Learn about our team's history, mission, and the passionate team that makes it all happen.
permalink: /about/
---

## Our Mission

We are a *FIRST* {{ site.site.program }} team dedicated to inspiring students in science, technology, engineering, art, and math (STEAM) through hands-on robotics experience. We believe in **Gracious Professionalism** and **Coopertition** - the core values that make *FIRST* unique.

## Team History

{% assign history = site.data.team_history %}
{% if history %}
{% include components/timeline.html events=history %}
{% else %}

Our team has been founded upon the basis to be fierce, yet supportive and together. We want to win, but it will never be our priority over supporting other teams.

Since our founding, we've grown from a handful of students meeting after school to a thriving program with multiple subteams, dedicated mentors, and a track record of goofiness and support at competitions.

{% endif %}

## Our Team

### Current Members

<div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6 my-8">
{% for member in site.data.team %}
{% include components/team-member-card.html member=member %}
{% endfor %}
</div>

### Mentors

<div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6 my-8">
{% for mentor in site.data.mentors %}
{% include components/team-member-card.html member=mentor %}
{% endfor %}
</div>

## What We Do

### Build Season
During build season, we design, build, and program a functional robot in just a few weeks. This intense time frame teaches us priority and how to manage the subteams.

### Competition Season
We compete at local meets with other nearby teams, competitions, qualifiers, and hopefully soon, championships. These events are not just about winning - they're about learning, working together with other teams, and having fun.

### Outreach
We're committed to giving back to our community. We participate in food drives, mentor younger teams, and demonstrate robotics at local events to inspire the next generation of engineers.

## Join Our Team {#join}

Interested in joining our team? We welcome students of all skill levels! Whether you're interested in building, programming, design, marketing, or outreach - there's a place for you. Even if you just want to try it out for a week or two, come swing by!

**Requirements:**
- Be a student in grades 8-12
- Commit to attending team meetings regularly
- Have a passion for learning and teamwork


**No prior experience necessary!** We'll teach you everything you need to know.

[Contact us](/contact/) to learn more about joining the team.
