---
title: US
permalink: /us/
layout: default
---
### United States
Cumulative cases and cases per day for {{ page.title }} (including only states data, excluding territories and other data). You can display the data for individual states [here]({{ site.url }}/us-states/).

{% include us_details.bokeh %}

<br><br>
Per capita data and contributions of individual states with most cases in {{ page.title }}.

{% include us_stacks.bokeh %}