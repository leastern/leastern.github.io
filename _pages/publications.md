---
layout: archive
title: "Publications"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br/>

<header>
<h1 class="page__title" itemprop="headline">Working Papers</h1>
</header>

{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}