---
title: Accidents Map
layout: accident-map
# see _layouts/map.html for layout
# see accident-map.html for content
permalink: /accident-map.html
---

# {{ page.title }}

<div id="accident-map" class="mb-2">
{% include_relative accident-map.html %}
<!-- map content is inserted via JS into div below -->
<div id="map" class="mt-2"></div>
</div>
