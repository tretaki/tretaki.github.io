---
title: Oceania
permalink: /oceania/
layout: default
---
### Oceania
Cumulative cases and cases per day for {{ page.title }}. You can display the data for individual countries [here]({{ site.url }}/oceania-countries/).

{% include oceania_details.bokeh %}

<br><br>
Per capita data and contributions of individual countries with most cases in {{ page.title }}.

{% include oceania_stacks.bokeh %}