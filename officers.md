---
layout: page
title: "Officers"
---
#Current eGSA Board
{% for post in site.posts %}
{% if post.active %}
<div class="row">
	<a href="{{ post.url | prepend: site.baseurl }}">
	<div class="officer col-lg-4 col-md-4 col-sm-6 col-xs-12">
		<div class="circle small" style="background-image: url('{{ site.url }}/{% if post.header-img %}{{ post.header-img }}{% else %}img/officers/blank.jpg{% endif %}')" >
		</div>
	</div>
	<div class="officer col-lg-8 col-md-8 col-sm-6 col-xs-12">
    	<h2 class="post-title text-left">{{ post.name }}</h2>
    	<p class="text-left">{{ post.position }}</p>
	</div>
	</a>
</div>
<hr>
{% endif %}
{% endfor %}



#Past Officers
<div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
{% for post in site.posts %}
{% unless post.active %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h3 class="post-title">{{ post.name }} - {{ post.position }}</h3>
    </a>
{% endunless %}
{% endfor %}
</div>