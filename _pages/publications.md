---
layout: page
permalink: /publications/
title: Publications
description: Publications and projects. You can also find most up-to-date entries for my latest publications on the Google Scholar page.
nav: true
---

<div class="publications-page">
  <div class="publications-header">
    <h1 class="publications-title">Selected Publications</h1>
    <a href="/publications/" class="see-all-link">SEE ALL PUBLICATIONS ></a>
  </div>
  
  <div class="publications">
    <div class="table-responsive">
      <table class="table table-sm table-borderless">
      {% assign publications = site.publications | sort: 'date' | reverse %}
      {% for publi in publications %}
        {% if publi.show %}
          {% include publication.html %}
        {% endif %}
      {% endfor %}
      </table>
    </div>
  </div>
</div>
