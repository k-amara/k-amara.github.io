---
layout: page
permalink: /blog/
title: Blog
description: Latest blog posts and articles
nav: true
---

<div class="blog-posts">
  <div class="table-responsive">
    <table class="table table-sm table-borderless">
    {% assign posts = site.posts | sort: 'date' | reverse %}
    {% for post in posts %}
      {% if post.show %}
        {% include post.html %}
      {% endif %}
    {% endfor %}
    </table>
  </div>
</div>

