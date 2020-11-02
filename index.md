---
layout: indexroot
---

<div class="home">
  <br>
  <br>
  <div class = "row">
    <div class = "col s12 m12 l12">
      <div class = "card-panel">
        <div class = "valign-wrapper">
          <div class = "col s12 m3 l3 center">
            <div>
              <img src="{{ site.url }}/img/KRYPTOMONITOR_LOGO_RGB.svg" alt="" class="circle responsive-img hoverable">
            </div>
            <div style = 'padding: 5px 0px'></div>
          </div>
          <div class = "col s12 m9 l9">
            <p>
              <h1>
                KRYPTOMONITOR
              </h1>
              <h2>
                <ul>
                  {% for lang in site.data.languages %}
                    <li>
                    	<a href="{{ site.url }}/{{ lang.code }}">{{ lang.label }}</a>
                    </li>
                  {% endfor %}
                </ul>
              </h2>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
