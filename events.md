---
layout: default
title: Nos prochains événements
noborder: true
image: mlle_violette_2020.jpeg
---
<div class="block">
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
          <span>
            {{ post.excerpt }}
          </span>
          <span>
            <img src="/assets/images/{{post.logo}}" />
          </span>
        </div>
      </li>
    {% endfor %}
  </ul>
</div>