---
title: Layered Map
layout: map
# see _layouts/map.html for layout
# see layered-map.html for content
permalink: /layered-map.html
# see below file for the actual map components
custom-foot: js/layeredmap-js.html
---

# {{ page.title }}

<div id="layered" class="mb-2">
{% include_relative layered-map.html %}
<!-- map content is inserted via JS into div below -->
<div id="map" class="mt-2"></div>
</div>