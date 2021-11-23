---
layout: page
title: Ergebnisse
lang: de
permalink: /de/ergebnisse/
navigation_weight: 4

---

<div class="row">
  <div class="col s12 m12 l12">
    <div class = "card-panel">
      <h2>Wissenschaftliche Publikationen</h2>
      <ul>
        {% for paper in site.data.papers %}
          <li>
              {{ paper.authors }},
              "{{ paper.title }}",
              {{ paper.details }}
          </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</div>
<div class="row">
  <div class="col s12 m12 l12">
    <div class = "card-panel">
      <h2>Vorträge</h2>
      <ul>
        {% for talk in site.data.talks %}
          <li>
              "{{ talk.title }}",
              {{ talk.details }}
          </li>
        {% endfor %}
      </ul>
       </div>
  </div>
</div>

