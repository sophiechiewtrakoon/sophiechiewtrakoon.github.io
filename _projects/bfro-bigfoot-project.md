---
name: BFRO Bigfoot Visualization
tools: [Python, Altair, Vega-Lite]
image: assets/pngs/bigfoot.png  # optional thumbnail image
description: Altair visualization of BFRO sighting reports.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# BFRO Bigfoot Sightings Visualization

This project visualizes reported Bigfoot sightings using Altair and Vega-Lite.

## Interactive Chart

<vegachart 
    schema-url="{{ site.baseurl }}/assets/json/bfro_altair_plot.json"
    style="width: 100%">
</vegachart>

