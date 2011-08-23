---
title: All Essays
layout: main
---

<div style="width: 350px; float: right; margin-top: 45px">
<img src="/images/octopus_kite.jpg">

<p style="font-size: 1.0em">This is the best kite in the world. I bought it in People's Square, Shanghai. It takes two people about 20 minutes to reel it in whenever there is a good wind.</p>
</div>

<div style="width: 400; height: 425px;">
<h2>Essays by Gregory Brown</h2>

<p>You'll find a new essay here each Wednesday. If you enjoy reading my articles, you might want to <a href="/support.html">support my efforts</a> so that I can keep writing great stuff for you.</p>

<ul>
{% for post in site.categories.essays %}
  <li>{{ post.date | date: "%Y.%m.%d" }}: <a href="{{post.url}}">{{ post.title }}</a></li>
{% endfor %}
</ul>

</div>
