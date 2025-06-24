---
permalink: /
title: "Researcher and Lecturer in Artificial Intelligence"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me

I mostly work on applying machine learning to combinatorial optimisation,
usually to constraint satisfaction problems.  My [PhD
thesis](https://etheses.whiterose.ac.uk/id/eprint/34581/) from the University of
York was completed on the topic of learning to select SAT encodings for linear
constraints.

I have extensive teaching experience, both at university level, most recently
co-teaching a Masters-level module in [AI Problem Solving with
Search]({{'/teaching/2025-sem2-aips' | relative_url}}), and previously at high
school level teaching mathematics to students from the age of 11 up to 19,
including A-level Maths and Further Maths.

### Most Recent Publications ( [see all ...]({{ '/publications/' | relative_url }}) )
{% assign pubs = site.publications | sort: 'date' | reverse %}
{% for pub in pubs limit:2 %}
* [{{pub.title}}]({{ pub.url | relative_url }})
{% endfor %}

### Most Recent Posts ( [see all ...]({{ '/year-archive/' | relative_url }}) )
{% assign sorted_posts = site.posts | sort: 'date' | reverse %}
{% for post in sorted_posts limit:2 %}
* [{{post.title}}]({{ post.url | relative_url }})
{% endfor %}

