---
layout: page
title: Über uns
---

{% for member in site.data.members %}

<figure class="align-center">
	<img src="/assets/images/{{ member.image }}" alt=""/>

	<figcaption>{{ member.name }}</figcaption>
</figure>
{% endfor %}

