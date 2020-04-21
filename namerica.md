---
title: North America
permalink: /namerica/
layout: default
---
### North America
Cumulative cases and cases per day for {{ page.title }}. You can display the data for individual countries [here]({{ site.url }}/namerica-countries/).

{% include namerica_details.bokeh %}

<br><br>
Per capita data and contributions of individual countries with most cases in {{ page.title }}.

{% include namerica_stacks.bokeh %}