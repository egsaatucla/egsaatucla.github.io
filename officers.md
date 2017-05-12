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



<h1>Past Officers</h1>
<div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
<h2>2015-2016:</h2>
<div class="col-lg-0 col-md-2 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2015 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h3 class="post-title">{{ post.name }} - {{ post.position }}</h3>
    </a>
{% endif %}
{% endfor %}
</div>

<h2>2014-2015:</h2>
<div class="col-lg-0 col-md-2 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2014 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h3 class="post-title">{{ post.name }} - {{ post.position }}</h3>
    </a>
{% endif %}
{% endfor %}
</div>
