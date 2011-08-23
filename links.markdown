---
title: Weekly Project Updates
layout: main
---

<div style="width: 350px; float: right; margin-top: 45px">
<img src="/images/garden.jpg">

<p style="font-size: 1.0em">When I'm not working, I enjoy doing a little bit of gardening. It is a great hobby for busy people, because it only takes a few minutes a day but is still very relaxing.</p>
</div>

<div style="width: 400; height: 425px;">
<h2>Weekly Link Dumps</h2>

<p>Every Tuesday I post links to things I find interesting. Most of these links are collected from various online sources, but there's a good chance that several of them will come from my favorite link blog, <a href="http://chneukirchen.org/trivium/">Trivium</a>.</p>

<ul>
{% for post in site.categories.links %}
  <li>{{ post.date | date: "%Y.%m.%d" }}: <a href="{{post.url}}">{{ post.title }}</a></li>
{% endfor %}
</ul>

</div>
