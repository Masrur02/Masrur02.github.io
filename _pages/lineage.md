---
layout: page
permalink: /lineage/
title: Academic Lineage
nav: true
nav_order: 3
---
<div class="lineage">

<p>
I once attended a talk by Professor Dinesh Manocha and later explored his website, where I discovered his academic lineage.
This sparked my curiosity to trace my own. I asked my academic supervisor, Professor Lantao Liu, and was able to trace my lineage
back to Rodney Brooks. Out of curiosity and respect, I emailed Professor Rodney Brooks to say hello as one of my academic ancestors.
To my surprise, he kindly replied and mentioned that his academic brother, Jitendra Malik, had also traced their shared lineage.
Following this chain of mentorship and scholarship, I discovered that Galileo Galilei appears as my great-20th academic grandfather.
</p>

<hr>

<ol>
{% for person in site.data.lineage.lineage %}
  <li>{{ person }}</li>
{% endfor %}
</ol>

</div>
