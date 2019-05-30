---
layout: default
title: about
permalink: /
---


<div class="row">
  <div class="col-md-3 mt-4 ml-10">
      {% include profile.html %}
  </div>
  <div class="col-md-8 mt-4 offset-md-1">
      <h1>Hello, my name is James Roney. I'm from Santa Barbara, California, and I'm currently an undergraduate student at Harvard University. I plan on graduating in 2022 with an A.B. Computer Science and Statistics. I like thinking about computational problems in the natural sciences, especially in neuroscience and systems biology. This website is some mixture of an extended CV, a blog, and a nice little project. Enjoy!</h1>
  </div>
</div>

## Education:

{%assign data = site.data.education%}
{%include list.html%}
 
<br>
## Experience:

{%assign data = site.data.experience%}
{%include list.html%}

<br>
## Selected Honors:

{%assign data = site.data.honors%}
{%include list.html%}
