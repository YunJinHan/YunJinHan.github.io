---
layout: page
title: 

---

<div class="page-content wc-container">
	<div class="post">
		<h1>tags</h1>  
		<ul>
			{% for tag in site.tags %}
			<li><a href="{{site.baseurl}}/tag/{{ tag[0] }}">{{ tag[0] }}</a></li>
			{% endfor %}
		</ul>
	</div>
</div>