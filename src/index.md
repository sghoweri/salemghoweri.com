---
layout: layouts/home.njk
templateEngineOverride: njk,md
# tags:
#   - nav
navtitle: Home
# permalink: /
---

<div class="o-grid o-grid--flex o-grid--matrix o-bolt-grid--lg">
  <div class="o-grid__item u-width-12/12 u-width-12/12@sm u-width-5/12@md">
    {% include "_resume-center.md" %}
  </div>

  <div class="o-grid__item u-width-12/12 u-width-6/12@sm u-width-3/12@md u-order-neg-1@md">
    {% include "_resume-left.md" %}
  </div>


  <div class="o-grid__item u-width-12/12 u-width-4/12@md">
    {% include "_resume-right.md" %}
  </div>
</div>













<hr>







<!-- <hr> -->

<!-- ## Blog (Coming Soon) -->
<!-- <h1>Latest 3 Posts</h1> -->

<!-- {% set postslist = collections.posts %} -->
<!-- {% include "postslist.njk" %} -->

<!-- <p>More posts can be found in <a href="{{ '/posts/' | url }}">the archive</a>.</p> -->
