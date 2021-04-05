---
layout: page
title: Home
---

# History and Practice of Multimedia - Online Lecture Series

This online English language lecture series focuses on the 
History and Practice of Multimedia with an emphasis on music.
We have invited members of the HfMT multimedia department
as well as international scholars and practitioners to present
on their respective fields of specialization 
(Constantin Basica, Kerstin Evert, Teoma Naccarato, Cat Hope,
Johannes Kreidler, Randall Packer, and others).
Topics include the definition, history, and appearances of multimedia.
The lecture series will take place during the summer term, every
Wednesday at 18:30h starting on April 7.

This lecture series is part of the Hamburg Open Online University (HOOU) 
and serves as the basis for a new class within the 
Music Technology Online Repository (MUTOR).

Links to the individual events will be posted here.

# Dates (subject to change)

<table class="hpm-event-table">
<thead>
<tr>
<th>Date</th>
<th>Topics</th>
<th>Presenters</th>
<th>Event Page</th>
<th>Unit</th>
</tr>
</thead>
<tbody>
{% for post in site.posts reversed %}
<tr>
<td>{{ post.presentation-date }}
</td><td>{{ post.topic }}
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
</td><td><a href="{{ site.baseurl }}{{ post.url }}">link</a>
</td><td>
{% if post.unit %}
<a href="{{ site.baseurl }}/units/{{ post.unit }}">link</a>
{% endif %}
</td>
</tr>
{% endfor %}
</tbody>
</table>
