---
title: Do Good Columbia
layout: default
---

<section class="hero"></section>
<section class="what-it-is"></section>

<h2>Posts</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {% for tag in post.tags %}
        <a href="{{tag.url}}">{{tag.name}}</a>
      {% endfor %}
    </li>
  {% endfor %}
</ul>

##Who it's for
 - people who want to come to river themed events
 - people who want to get active with the Do Good program

About Page

About The River

Resources
 - Book recomendations
 - Maps
 - upcoming events
 - File (pdf)
 - Video (youtube)
 - Photo

##Participant Packet

##Press Kit


Sign up for email notifications
