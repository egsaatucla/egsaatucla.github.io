---
layout: page
title: "Officers"
---
<div class="row">
{% for post in site.posts %}
{% if post.active %}
	<a href="{{ post.url | prepend: site.baseurl }}">
		<div class="circle small pull-left" style="background-image: url('{{ site.url }}/{% if post.header-img %}{{ post.header-img }}{% else %}img/officers/blank.jpg{% endif %}')" >
		</div>
	</a>
{% endif %}
{% endfor %}
</div>
<hr>



#Past Officers
<div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
{% for post in site.posts %}
{% if post.officer %}
{% unless post.active %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h3 class="post-title">{{ post.name }} - {{ post.position }}</h3>
    </a>
{% endunless %}
{% endif %}
{% endfor %}
</div>