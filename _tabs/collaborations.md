---
layout: default
title: Collaborations
permalink: /collaborations/
icon: fas fa-university
order: 5
---

## Participating Institutions and Organizations:

<div class="row">
  {% for institution in site.data.institutions.institutions %}
    <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
      <div class="card h-100">
        <img src="{{ institution.image }}.jpeg" class="card-img-top" alt="{{ institution.name }}">
        <div class="card-body">
          <h5 class="card-title">
            <a href="{{ institution.url }}">{{ institution.name }}</a>
          </h5>
        </div>
      </div>
    </div>
  {% endfor %}
</div>
