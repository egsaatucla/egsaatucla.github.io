---
layout: page
title: "Newsletter"
description: "Weekly eGSA newsletter --- Stay updated, join upcomming events."
header-img: "img/royce2.jpg"
---
#Upcoming Events
<ul>
{% for newsletter in site.categories.newsletters %}
<li>
	<a href="{{ newsletter.url | prepend: site.baseurl }}">
    	<span class="post-title text-left"><b>{{ newsletter.event-date }}, {{ newsletter.name }}</b>. {{newsletter.newsletter-description}}</span>
	</a>
</li>
{% endfor %}
</ul>
<hr>

#Staying updated with eGSA events
* <b>Weekly emails</b>: you should already receive them when are enrolled via Courseweb. If not, please contact secretary@bruinegsa.org.
* <a href="https://www.facebook.com/UCLA.eGSA?fref=ts" ><b>eGSA Facebook page</b></a>

#Regularly scheduled events
* <b>Townhall</b> (quarterly): learn about events for the upcoming quarter and provide feedback/suggestions while enjoying free food.
* <b>Engineering Social</b> (quarterly): enjoy free food and beer and meet other engineering MS/PhD students!
* <b>Volunteering</b> (monthly): join in humanitarian work for an evening and meet other like-minded engineering graduate students interested in community service.

