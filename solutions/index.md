---
title: Transforming Customer Communincations
layout: home
---
{%- for solution in site.data.solutions %}<a href="{{solution.link}}"><!-- ![{{solution.name}}]({{solution.icon}}) -->
## {{solution.name}}
<a href="{{solution.link}}">{{solution.summary}}</a>
<br /><br /><br />
{%- endfor %}

