---
title: My Eigth Post
layout: singlepost
permalink: /:title.html
---
<img src="/images/photo-1486688680290-be46662593bd.jpg">
<p><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in. Eligendi, deserunt, <!--more-->blanditiis est quisquam doloribus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in. Eligendi, deserunt, blanditiis est quisquam doloribus.</p>

<div class="clearfix">
{% if page.previous.url %}
	<div class="col_half tleft"><a href="{{page.previous.url}}" data-animate="tada" class="button button-border button-xlarge nobottommargin"><i class="icon-line-arrow-left"></i><span>Previous Post</span></a> 
	</div>
{% endif %}
{% if page.next.url %}
	<div class="col_half col_last tright">
		<a href="{{page.next.url}}" data-scrollto="#section-pricing" class="button button-border button-xlarge nobottommargin">Next Post<span><i class="icon-line-arrow-right"></i></span></a>
	</div>
{% endif %}
</div>
<div class="fb-comments" data-href="http://elevatika.com/my-first-post" data-numposts="5"></div>