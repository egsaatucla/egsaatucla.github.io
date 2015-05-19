---
layout: page
title: "Officers"
---
#Current eGSA Board
{% for post in site.posts %}
{% if post.active %}
<div class="officer col-lg-6 col-md-6 col-sm-6 col-xs-12 well">
    <a href="{{ post.url | prepend: site.baseurl }}">
    	<h2 class="post-title">{{ post.title }}</h2>
    	{{ post.description }}
    	<img src="{{ site.baseurl }}/{% if post.header-img %}{{ post.header-img }}{% else %}img/officers/blank.jpg{% endif %}" alt= "{{ post.title }}" style="height:200px" class="center">
    </a>
</div>
{% endif %}
{% endfor %}

<hr>

#Past Officers
<div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
{% for post in site.posts %}
{% unless post.active %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h3 class="post-title">{{ post.title }} - {{ post.description }}
        </h3>
    </a>
{% endunless %}
{% endfor %}
</div>