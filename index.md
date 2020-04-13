---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: default
---

### World

The graphs of [COVID-19](https://en.wikipedia.org/wiki/Coronavirus_disease_2019) cases for the whole world are shown below. The information of cumulative cases and new cases per day is displayed.


The details for other continents and individual countries can be found on their respective sub-pages:&nbsp;
{%- for page in site.pages -%}

{%- if page.title -%}
    {%- if page.title == "Africa" -%}
        <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
    {%- else -%}
        , <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
    {%- endif -%}
{%- endif -%}

{%- endfor -%} .

{% include world_details.bokeh %}


<br><br>
Contributions of individual countries with most cases in the world.

{% include world_stacks.bokeh %}