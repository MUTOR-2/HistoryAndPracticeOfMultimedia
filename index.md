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

# Original Schedule

<style>
a.index-tab-link:hover {
text-decoration: underline;
}
</style>
<table class="hpm-event-table">
<thead>
<tr>
<!--<th>Date</th>-->
<th>Topics</th>
<th>Presenters</th>
<th>Event Page</th>
<th>Unit</th>
</tr>
</thead>
<tbody>
{% for post in site.posts reversed %}
{% if post.exclude == true %}
{% else %}
<tr>
<!--<td>{{ begincomment }}{{ post.presentation-date }}{{ endcomment }}
</td>--><td>{{ post.topic }}
</td><td>
{% assign npresenters = post.presenters | size %}
{% if npresenters == 1 %}
{{ post.presenters[0].name }}
{% elsif npresenters == 2 %}
{{ post.presenters[0].name }} and {{ post.presenters[1].name }}
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
</td><td><a class="index-tab-link" href="{{ site.baseurl }}{{ post.url }}">link</a>
</td><td>
{% if post.unit %}
<a class="index-tab-link" href="{{ site.baseurl }}/units/{{ post.unit }}">link</a>
{% endif %}
</td>
</tr>
{% endif %}
{% endfor %}
</tbody>
</table>
