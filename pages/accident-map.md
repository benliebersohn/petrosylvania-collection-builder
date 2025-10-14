---
title: Accidents Map
layout: accident-map
# see _layouts/map.html for layout
# see accident-map.html for content
permalink: /accident-map.html
# see below file for the actual map components
custom-foot: js/accident-js.html
---

# {{ page.title }}

<div id="accident-map" class="mb-2">
{% include_relative accident-map.html %}
<!-- map content is inserted via JS into div below -->
<div id="map" class="mt-2"></div>
</div>
