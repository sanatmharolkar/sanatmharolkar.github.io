---
title: All Things Robotics
layout: landing
description: A blog for my projects, as well as some thoughts on what's going on in the world of robotics.
image: assets/images/all-things-robotics/banner.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Sed amet aliquam</h2>
		</header>
		<p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis magna sed nunc rhoncus condimentum sem. In efficitur ligula tate urna. Maecenas massa vel lacinia pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis libero. Nullam et orci eu lorem consequat tincidunt vivamus et sagittis magna sed nunc rhoncus condimentum sem. In efficitur ligula tate urna.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	{% for post in site.categories.all-things-robotics %}
		<section>
			<a href="{{ post.url }}" class="image">
				<img src="{{ post.featured_img }}" alt="" data-position="top center" />
			</a>
			<div class="content">
				<div class="inner">
					<header class="major">
						<h3>{{ post.title }}</h3>
					</header>
					<p>{{ post.excerpt }}</p>
					<ul class="actions">
						<li><a href="{{ post.url }}" class="button">Read more</a></li>
					</ul>
				</div>
			</div>
		</section>
	{% endfor %}
</section>

</div>
