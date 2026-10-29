---
---

<img src="{{ '/profile%20pic.png' | relative_url }}" alt="Oliver Fried" width="160" height="160">

Hi there!

I'm Oliver Fried. This is a home for my essays that I want to share with the world.

I'm currently a Senior Software Engineer at ZOA Suite, an insurtech startup building data solutions for insurance brokerages in Spain. I'm passionate about making AI work for us, not the other way around, and building the abstractions needed to make that happen.

Before ZOA, I built deterministic tooling for extracting insurance policy data. Earlier, I worked as a data consultant for enterprise clients in Barcelona.

---

<ul>
{% for post in site.posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> - <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: '%-d %B %Y' }}</time></li>
{% endfor %}
</ul>
