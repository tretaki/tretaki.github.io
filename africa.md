---
title: Africa
permalink: /africa/
layout: default
---
### Africa
Cumulative cases and cases per day for {{ page.title }}. You can display the data for individual countries [here]({{ site.url }}/africa-countries/).

{% include africa_details.bokeh %}

<br><br>
Per capita data and contributions of individual countries with most cases in {{ page.title }}.

{% include africa_stacks.bokeh %}