---
layout: page
title: Results
lang: en
permalink: /en/results/
navigation_weight: 5

---

<div class="row">
  <div class="col s12 m12 l12">
    <div class = "card-panel">
      <h2>Scientific Publications</h2>
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
    <h2>Talks</h2>
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

