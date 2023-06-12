---
layout: default
---

# Talks

{% for person in site.workshop.talks %}
<p>
<a href="mailto:{{ person.email }}">
<div class="speaker">
    <img class="headshot" src="{{ person.pic }}"/>
    <div class="details">
	<span class="name">{{ person.name }}<br>{{ person.surname }}</span>
	<span class="affiliation">{{ person.affiliation }}</span>
	<span class="title">{{ person.title }}</span>
    </div>
</div>
</a>
</p>
{% endfor %}
