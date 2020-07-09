---
title: "Weather"
description: "Weather forecast and conditions for kite-surfing in Exmouth (Duck Pond and Seafront)"
---

## Weather Dashboard

{{< windguru-forecast-exmouth-seafront >}}

<!-- TODO - some explanation of springs/neaps, high/low tides and what it means for us -->

<div class="row">
<div class="col-lg-4 col-sm-12 text-center">
    {{< tide-times-exmouth >}}
</div>
<div class="col-lg-8 col-sm-12 text-center">

<style>
  .video-container {
    overflow: hidden;
    position: relative;
    width:100%;
}
.video-container::after {
    padding-top: 56.25%;
    display: block;
    content: '';
}
.video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
.windguru-container {
    overflow: hidden;
    position: relative;
    width:100%;
}
.windguru-container iframe {    
    top: 0;
    left: 0;
    width: 100%;
    height: 280px;
}
</style>

<div class="video-container text-center">
    <iframe src="https://relay.viewcam.co.uk/nciexmouth/embed.html" frameborder="0" allowfullscreen=""></iframe>    
</div>

<caption><em style="font-size:70%">Webcam by <a href="https://www.exmouthcoastwatch.co.uk/" target="_blank">Exmouth NCI Coastwatch</a></em></caption>

</div>

</div>

<!-- No widget for weather station, so just show in iFrame 

l = sponsor logo
n = spot name
g = graph
c = readings at bottom
height = 395 for all
       = 315 for g,c
-->

<p class="mb-0"><strong>Seafront - live wind</strong></p>
<div class="windguru-container text-center">
<iframe src="https://www.windguru.cz/wglive-iframe.php?s=2395&wj=knots&tj=c&m=3&gsize=200&msize=200&show=g,c" frameborder="0"></iframe>
</div>
<p  class="mb-0"><strong>Duckpond - live wind</strong></p>
<div class="windguru-container text-center">
<iframe src="https://www.windguru.cz/wglive-iframe.php?s=1882&wj=knots&tj=c&m=3&gsize=200&msize=200&show=g,c" frameborder="0"></iframe>
<caption><em style="font-size:70%">Charts by <a href="https://www.windguru.cz/47887" target="_blank">Windguru</a> and weather stations sponsored by <a href="https://www.edgewatersports.com/" target="_blank">EDGE Watersports</a></em></caption>
</div>
    

<hr>

## Forecast
* There are two spots in Exmouth - the [Sea Front and Duck Pond](/spot-guide/). The wind and tide conditions dictate which will be best at any particular time.
* In general the
      * [Duck Pond](/spot-guide/duck-pond/) is better around High Tide with winds coming from the north.
      * [Sea Front](/spot-guide/seafront/) is better around Low Tide  with winds coming from the south.
   * See the detailed <a href="/spot-guides/">Spot Guides</a> for more information
* [EDGE Watersports](https://www.edgewatersports.com/live-conditions/) - regularly  update a <strong>"Daily Report"</strong> and where and when is likely to be best depending on conditions and tide. Great for picking up not only when its good but also WHY so you can better understand weather (also on [Facebook](https://www.facebook.com/edgewatersports) )
* [Tide Times](https://www.tidetimes.org.uk/exmouth-dock-tide-times)   
* [Windguru - Exmouth](https://www.windguru.cz/47887)
* [XC Weather](https://www.xcweather.co.uk/) - broader overview of the wind (actual and forecast) over the UK.
* [Magic Seaweed](https://magicseaweed.com/Exmouth-Surf-Report/164/)
* [Met Office - surface pressure charts](https://www.metoffice.gov.uk/weather/maps-and-charts/surface-pressure/)
* [Met Office - Insore Waters, Lyme Regis to Lands End (#8)](https://www.metoffice.gov.uk/weather/specialist-forecasts/coast-and-sea/inshore-waters-forecast#area8)

<hr>

## Other

* [Exmouth NCI Weather Station](https://exmouthcoastwatch.co.uk/weather/) - under-reads if the wind has any North in it so check the Duckpond one above too. Can be offline and showing old data at times so check the error at the top - if it's showing red and "4 hours since last update". Click on the dials to see a history.

* [Interactive Webcam](http://www.exmouthcam.co.uk/webcam/)
