---
layout: page
title: "Newsletters"
description: "Weekly eGSA newsletter --- Stay updated, join upcomming events!"
header-img: "img/royce2.jpg"
---
#Weekly Newsletters
<ul>
{% for newsletter in site.categories.newsletters %}
<li>
	<a href="{{ newsletter.url | prepend: site.baseurl }}">
    	<span class="post-title text-left"><b>{{ newsletter.newsletter-date }}, {{ newsletter.name }}</b>. {{newsletter.newsletter-description}}</span>
	</a>
</li>
{% endfor %}
</ul>
<hr>

