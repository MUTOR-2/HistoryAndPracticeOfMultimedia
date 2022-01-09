---
layout: page
title: Home
---

# History and Practice of Multimedia - Online Lecture Series

Welcome to the MUTOR series on the History and Practice of Multimedia! 
The materials collected here were originally presented as a 12-part
online lecture series in 2021. In the "Units" section of this site,
you will find the text and 
supporting media for each talk, as well as recordings of the talks
themselves. 

This lecture series is part of the Hamburg Open Online University (HOOU) 
and serves as the basis for a new class within the 
Music Technology Online Repository (MUTOR).

# Contents

<style>
a.index-tab-link:hover {
text-decoration: underline;
}
</style>
<table class="hpm-event-table">
<thead>
<tr>
<!--<th>Date</th>-->
<th>Unit</th>
<th>Title</th>
<th>Presenter(s)</th>
<!-- <th>Event Page</th> -->
<!-- <th>Unit</th> -->
</tr>
</thead>
<tbody>
{% for post in site.posts reversed %}
{% if post.exclude == true %}
{% else %}
<tr>
<td>
{% if post.unit %}
<a class="index-tab-link" href="{{ site.baseurl }}/units/{{ post.unit }}">{{ post.unit }}</a>
{% endif %}
</td>
<td><a class="index-tab-link" href="{{ site.baseurl }}/units/{{ post.unit }}">{{ post.topic }}</a></td>
<td>
{% assign npresenters = post.presenters | size %}

{% if npresenters == 1 %}
{% if post.presenters[0].website %}
<a class="index-tab-link" href="{{ post.presenters[0].website }}">{{ post.presenters[0].name }}</a>
{% else %}
{{ post.presenters[0].name }}
{% endif %}

{% elsif npresenters == 2 %}
{% if post.presenters[0].website %}
<a class="index-tab-link" href="{{ post.presenters[0].website }}">{{ post.presenters[0].name }}</a>
{% else %}
{{ post.presenters[0].name }}
{% endif %}
and
{% if post.presenters[1].website %}
<a class="index-tab-link" href="{{ post.presenters[1].website }}">{{ post.presenters[1].name }}</a>
{% else %}
{{ post.presenters[1].name }}
{% endif %}
{% else %}
{{ post.presenters[0].name }}
{%- for p in post.presenters offset: 1 -%}
{%- if forloop.last -%}
and {{ p.name }}
{%- else -%}
, {{ p.name }}
{% endif %}
{% endfor %}
{% endif %}
</td>
</tr>
{% endif %}
{% endfor %}
</tbody>
</table>
