---
layout: default
title: Past workshops
parent: Workshops
has_children: true
nav_order: 5
---
<h1>List of past workshops</h1>
{%- assign children_list = site.pages | where: "parent", "Past workshops" -%}
{% include toc_nav.html nav=children_list %}