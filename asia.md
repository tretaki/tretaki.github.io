---
title: Asia
permalink: /asia/
layout: default
---
### Asia
Cumulative cases and cases per day for {{ page.title }}. You can display the data for individual countries [here]({{ site.url }}/asia-countries/).

{% include asia_details.bokeh %}

<br><br>
Per capita data and contributions of individual countries with most cases in {{ page.title }}.

{% include asia_stacks.bokeh %}