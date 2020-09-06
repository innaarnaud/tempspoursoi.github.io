---
layout: default
title: Mon blog
---

<ul class="posts">
  {% for post in site.posts %}
    <li class="post">
      <div class="post-header">
        <h2>
            {{ post.title }}
        </h2>
        <div class="date">
          {% capture i18n_date %}
            {{ post.date | date: "%-d" }}
            {% assign m = post.date | date: "%-m" | minus: 1 %}
            {{ site.data.fr.months[m] }}
            {{ post.date | date: "%Y" }}
          {% endcapture %}
          {{i18n_date}}
        </div>
      </div>
      <div class="wrapper">
        {% if post.proverb_author and post.proverb %}
          <span class="proverb">
            <span>
              {{ post.proverb }}
            </span>
            <span class="author">
              {{post.proverb_author}}
            </span>
          </span>
        {% else %}
          {{ post.excerpt }}
        {% endif %}
      </div>
    </li>
  {% endfor %}
</ul>
