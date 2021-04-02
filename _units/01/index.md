---
###
# unit information: 
# Fill out with relevant information for this unit
###
title: Unit Title
number: 1
short_description: Short description--one or two sentences
summary: Summary description--150 words or so
authors: 
- First Author
- Second Author
topics: [Topic 1, Topic 2]
test_questions:
- Question 1
- Question 2

references:
 lamport78:
  authors:
   - firstname: L.
     lastname: Lamport
  title: 'Time, Clocks, and the Ordering of Events in a Distributed System'
  publication: 'Communications of the ACM, 21(7): 558-565'
  year: 1978
  doi: 10.1145/359545.359563

###
# page layout:
# don't change
###
layout: unit
citations: ""
mathjax: true
---

{% include unit_preamble.md %}

# Introduction

Your unit goes here.
See the [example unit]({{ site.baseurl }}/example-unit.html) for formatting
guidelines. Remember, time doesn't exist
{% include cite ref='lamport78' %}.

{% include unit_postamble.md %}
