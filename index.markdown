---
title: The Majestic Sea Creature
layout: main
---

Hi there! I am [Gregory Brown](http://community.mendicantuniversity.org/people/sandal), and this is my personal website. If you were looking for my professional work, you should check out [Practicing Ruby](http://practicingruby.com) instead.

---

{% for post in site.categories.essays %}
### [{{ post.title }}]({{post.url}})
{% endfor %}

---

Want to share your thoughts about these essays? Feel free to [email me.](mailto:gregory.t.brown@gmail.com)
