---
title: Transforming Customer Communications
layout: posts
---
{%- for solution in site.data.solutions %}
<img src="{{solution.hero}}" alt="{{solution.name}}" />
<a href="{{solution.link}}"><!-- ![{{solution.name}}]({{solution.icon}}) -->
## {{solution.name}}
<a href="{{solution.link}}">{{solution.summary}}</a>
<br /><br /><br />
{%- endfor %}

