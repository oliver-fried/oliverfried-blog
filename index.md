---
---

Hi there!

I'm Oliver Fried.

This is my personal website, and a home for my essays.

<ul>
{% for post in site.posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> - <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: '%-d %B %Y' }}</time></li>
{% endfor %}
</ul>
