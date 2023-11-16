---
layout: default
title: Our Team
permalink: /people/
icon: fas fa-tags
order: 2
---

## Principal Investigator(s):

<div class="row">
  {% for person in site.data.people.principal_investigators %}
    <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
      <div class="card h-100">
        <img src="{{ person.image }}.jpeg" class="card-img-top" alt="{{ person.name }}">
        <div class="card-body">
          <h5 class="card-title">
            <a href="{{ person.url }}">{{ person.name }}</a>
          </h5>
          <p class="card-text">{{ person.title }}</p>
          <p class="card-text">{{ person.institution }}</p>
        </div>
      </div>
    </div>
  {% endfor %}
</div>

## Key Personnel:

<div class="row">
  {% for person in site.data.people.key_personnel %}
    <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
      <div class="card h-100">
        <img src="{{ person.image }}.jpeg" class="card-img-top" alt="{{ person.name }}">
        <div class="card-body">
          <h5 class="card-title">
            <a href="{{ person.url }}">{{ person.name }}</a>
          </h5>
          <p class="card-text">{{ person.title }}</p>
          <p class="card-text">{{ person.institution }}</p>
        </div>
      </div>
    </div>
  {% endfor %}
</div>
