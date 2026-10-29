---
---

<section class="profile" aria-label="About Oliver Fried">
<div class="profile-text">
<p>Hi there!</p>
<p>I'm Oliver Fried. This is a home for my essays that I want to share with the world.</p>
<p>I'm currently a Senior Software Engineer at ZOA Suite, an insurtech startup building data solutions for insurance brokerages in Spain. I'm passionate about making AI work for us, not the other way around, and building the abstractions needed to make that happen.</p>
<p>Before ZOA, I built deterministic tooling for extracting insurance policy data. Earlier, I worked as a data consultant for enterprise clients in Barcelona.</p>
</div>
<img class="profile-photo" src="{{ '/profile%20pic.png' | relative_url }}" alt="Oliver Fried" width="160" height="160">
</section>

<h2 style="font-size: 1em;">Essays</h2>

<ul>
{% for post in site.posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a> - <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: '%-d %B %Y' }}</time></li>
{% endfor %}
</ul>
