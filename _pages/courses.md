---
layout: default
permalink: /courses
title: courses
---

<br>
## Coursework
### Fall 2019
{% assign data = {{site.data.courses | where:"line2","Fall 2019"}} %}
{% include list.html%}
### Spring 2019
{% assign data = {{site.data.courses | where:"line2","Spring 2019"}} %}
{% include list.html%}
### Fall 2018
{% assign data = {{site.data.courses | where:"line2","Fall 2018"}} %}
{% include list.html%}
### Relevant Pre-Harvard Coursework
{% assign data = {{site.data.courses | where:"nonH","true"}} %}
{% include list.html%}
<br>
