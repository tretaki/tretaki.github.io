---
title: Europe
permalink: /europe/
layout: default
---

### Europe
Cumulative cases and cases per day for {{ page.title }}. You can display the data for individual countries [here]({{ site.url }}/europe-countries/).

{% include europe_details.bokeh %}

<br><br>
Per capita data and contributions of individual countries with most cases in {{ page.title }}.

{% include europe_stacks.bokeh %}