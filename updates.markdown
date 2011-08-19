---
title: Weekly Project Updates
layout: main
---

<div style="width: 350px; float: right; margin-top: 30px">
<img src="/images/garden.jpg" style="border: 4px solid white; width: 350px; margin-top: 0px;">

<p style="font-size: 1.0em">When I'm not working, I enjoy doing a little bit of gardening. It is a great hobby for busy people, because it only takes a few minutes a day but is still very relaxing.</p>
</div>

<div style="width: 400; height: 425px;">
<h2>Weekly Progress Reports</h2>

<p>Every Wednesday I will post an update here about the various projects I'm working on. You may want to <a href="">support my efforts</a> so that I can keep working on open source projects and educational initiatives full time.</p>
<ul>
{% for post in site.categories.updates %}
  <li>{{ post.date | date: "%Y.%m.%d" }}: <a href="{{post.url}}" style="color: #ff9640; text-decoration: none;">{{ post.title }}</a></li>
{% endfor %}
</ul>

</div>
