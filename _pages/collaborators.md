---
layout: page
title: collaborators
permalink: /collaborators/
description: A brief list of the people who have been part of my exciting research journey so far.
nav: true
display_categories: [Past Collaborations, Active Collaborations]
horizontal: false
---

<div class="projects">
  {% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
    {% for category in page.display_categories %}
      <h2 class="category">{{category}}</h2>
      {% assign categorized_projects = site.projects | where: "category", category %}
      {% assign sorted_projects = categorized_projects | sort: "importance" %}

      Allah is the most merciful!!
      Allah is the most merciful!!
      Allah is the most merciful!!
      Allah is the most merciful!!
      Allah is the most merciful!!
      Allah is the most merciful!!
      Allah is the most merciful!!
      Allah is the most merciful!!
      Allah is the most merciful!!


    {% endfor %}

</div>
