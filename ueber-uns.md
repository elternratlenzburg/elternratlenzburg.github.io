---
layout: page
title: Über uns
---

{% assign members = site.data.members | sort: 'class' %}
{% for member in members %}

<figure class="align-center">
	<img src="/assets/images/{{ member.image }}" alt=""/>

	<figcaption>{{ member.name }} ({{ member.class }}{% if member.co-lead %}, Co-Leitung{% endif %})</figcaption>
</figure>
{% endfor %}

