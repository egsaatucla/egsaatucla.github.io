---
layout: page
title: "Officers"
---
<div class="row">
{% for post in site.posts %}
{% if post.active %}
	<a href="{{ post.url | prepend: site.baseurl }}">
		<div class="circle small pull-left" style="background-image: url('{{ site.url }}/{% if post.header-img %}{{ post.header-img }}{% else %}img/officers/blank.jpg{% endif %}')" >
            <br><br><br><br><br>
            <h6 class="post-title" style="text-align:center">
            {{ post.name }} - {{ post.position }}</h6>
            <!-- <h6 class="post-title" style="text-align:center">
            {{ post.position }}</h6> -->
		</div>
	</a>
{% endif %}
{% endfor %}
</div>
<hr>



<h1>Past Officers</h1>
<div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">

<h2>2021-2022:</h2>
<div class="col-lg-0 col-md-0 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2021 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h5 class="post-title">{{ post.name }} - {{ post.position }}</h5>
    </a>
{% endif %}
{% endfor %}
</div>

<h2>2020-2021:</h2>
<div class="col-lg-0 col-md-0 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2020 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h5 class="post-title">{{ post.name }} - {{ post.position }}</h5>
    </a>
{% endif %}
{% endfor %}
</div>

<h2>2019-2020:</h2>
<div class="col-lg-0 col-md-0 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2019 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h5 class="post-title">{{ post.name }} - {{ post.position }}</h5>
    </a>
{% endif %}
{% endfor %}
</div>

<h2>2018-2019:</h2>
<div class="col-lg-0 col-md-0 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2018 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h5 class="post-title">{{ post.name }} - {{ post.position }}</h5>
    </a>
{% endif %}
{% endfor %}
</div>

<h2>2017-2018:</h2>
<div class="col-lg-0 col-md-0 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2017 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h5 class="post-title">{{ post.name }} - {{ post.position }}</h5>
    </a>
{% endif %}
{% endfor %}
</div>

<h2>2016-2017:</h2>
<div class="col-lg-0 col-md-0 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2016 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h5 class="post-title">{{ post.name }} - {{ post.position }}</h5>
    </a>
{% endif %}
{% endfor %}
</div>

<h2>2015-2016:</h2>
<div class="col-lg-0 col-md-0 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2015 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h5 class="post-title">{{ post.name }} - {{ post.position }}</h5>
    </a>
{% endif %}
{% endfor %}
</div>

<h2>2014-2015:</h2>
<div class="col-lg-0 col-md-0 col-sm-0 col-xs-0">
{% for post in site.posts %}
{% if post.year == 2014 %}
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h5 class="post-title">{{ post.name }} - {{ post.position }}</h5>
    </a>
{% endif %}
{% endfor %}
</div>
