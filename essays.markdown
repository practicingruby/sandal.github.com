---
title: All Essays
layout: main
---

<div style="width: 350px; float: right; margin-top: 30px">
<img src="/images/octopus_kite.jpg" style="border: 4px solid white; width: 350px; margin-top: 0px;">

<p style="font-size: 1.0em">This is the best kite in the world. I bought it in People's Square, Shanghai. It takes two people about 20 minutes to reel it in whenever there is a good wind.</p>
</div>

<div style="width: 450; height: 450px;">
<h2>Essays by Gregory Brown</h2>

{% for post in site.categories.essays %}
  <p> ~ <a href="{{post.url}}" style="color: #fefef2; text-decoration: none;">{{ post.title }}</a></p>
{% endfor %}
</div>
