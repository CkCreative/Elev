---
title: My Second Post
layout: singlepost
permalink: /:title.html

---
<h1>This is a beautiful heading IMO</h1>
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in. Eligendi, deserunt, blanditiis est quisquam doloribus.<!--more-->


<div class="clearfix">
{% if page.previous.url %}
	<div class="col_half tleft"><a href="{{page.previous.url}}" data-animate="tada" class="button button-border button-xlarge nobottommargin"><i class="icon-line-arrow-left"></i>{{page.previous.title}}</a> 
	</div>
{% endif %}
{% if page.next.url %}
	<div class="col_half col_last tright">
		<a href="{{page.next.url}}" data-scrollto="#section-pricing" class="button button-border button-xlarge nobottommargin">{{page.next.title}}<i class="icon-line-arrow-right"></i></a>
	</div>
{% endif %}
</div>