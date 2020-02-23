---
layout: default
title: Temps Pour Soi
---
# Mon blog

<ul class="posts">
  {% for post in site.posts %}
    <li class="post">
      <div class="wrapper">
        {{ post.excerpt }}
      </div>
    </li>
  {% endfor %}
</ul>
