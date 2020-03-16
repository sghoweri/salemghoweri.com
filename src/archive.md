---
layout: layouts/home.njk
tags:
  - nav
navtitle: Blog (In Progress)
permalink: /posts/
templateClass: o-wrapper c-band c-band--md foo
templateEngineOverride: njk,md
---

## Blog Posts

{% set postslist = collections.posts %}

{%- include "postslist.njk" -%}
