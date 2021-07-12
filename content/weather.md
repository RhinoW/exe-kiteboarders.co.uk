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
    <div class="col-lg-8 col-sm-12 text-center align-self-center">
        <div class="video-container text-center mt-2">
            <a href="https://exmouthcoastwatch.co.uk/webcam/" target="_blank" rel="noopener noreferrer">
                Exmouth NCI Coastwatch webcam
                <i class="fa fa-video-camera ml-2" style="font-size:200%" aria-hidden="true"></i>
            </a>
        </div>
        <div class="pt-3 pb-3">
            <button type="button" class="btn btn-danger" data-toggle="modal" data-target="#seafrontWarningModal">
                <i class="fa fa-exclamation-triangle" aria-hidden="true"></i> &nbsp; 
                <strong>Seafront Warning</strong>
                &nbsp; <i class="fa fa-exclamation-triangle" aria-hidden="true"></i>
            </button>
        </div>
    </div>
</div>

<style>
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

<!-- No widget for weather station, so just show in iFrame 

l = sponsor logo
n = spot name
g = graph
c = readings at bottom
height = 395 for all
       = 315 for g,c
-->

<!-- <div class="text-danger m-3"><strong>WARNING</strong> - Currently the Seafront weather station is stuck showing S wind direction and the Duckpond station is out of order. See <strong><a href="https://exmouthcoastwatch.co.uk/weather/" target="_blank" rel="noopener noreferrer">NCI Weather Station</a></strong></div> -->

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
   * See the detailed <a href="/spot-guide/">Spot Guides</a> for more information
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

<!-- Navigation Channel warning modal -->
<div class="modal fade" id="seafrontWarningModal" tabindex="-1" role="dialog" aria-labelledby="seafrontWarningModalLabel" aria-hidden="true" data-backdrop="static">
  <div class="modal-dialog modal-lg" role="document">
    <div class="modal-content">      
      <div class="modal-body">
<div>

**The Harbour Master has received complaints from boaters and skippers of larger vessels about Kitesurfers getting too close and/or hindering vessels transiting the navigation channel.**

_(The navigation channel starts at the safe water mark out to sea and runs along the sea front and up into the estuary)._


On a busy summer day it can be intimidating for skippers trying to transit the channel when faced with a large number of kitesurfers (or a large number of any vessels for that matter) and they may have no idea of your intentions or even if you've seen them. **You may know that you're going nowhere near them, but they may not know that.**

To keep good relations please remember
* KEEP WELL CLEAR of the swimming area (between the flags)
* The seafront navigation channel is only suitable for experienced kitesurfers.
* Keep an eye out to windward so you are not surprised at a vessel sneaking up behind you.
* Kitesurfers must keep out of the way of larger and less maneuverable vessels as if they are "Restricted in their room to manoeuvre" then that trumps any "Power v Sail" or "Starboard Tack" in the right of way stakes.
* We can turn on a dime and need only a few inches of water so just be nice and give everyone a bit of room.
* Don't pass close in front of a vessel even if you think you will clear it. What if you fall or drop the kite?
* If you are passing to stern then don't cut it too close. Sure that wake looks tempting to launch off but if you cut it too close all the skipper sees is a kitesurfer hurtling directly towards them.
* **How about signal that you've seen a vessel with a friendly wave then take a short tack or two to give them plenty of room - it's the nice thing to do.**

Please see the [spot guide](/spot-guide/seafront/) and [code of conduct](http://localhost:1234/code-of-conduct/) for more details <LINK>
</div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-success mx-auto" data-dismiss="modal">OK, I will play nice - show me the Weather!</button>        
      </div>
    </div>
  </div>
</div>

<!-- Show warning on page load but just once  -->
<script>
    window.addEventListener("DOMContentLoaded",function() {
        const warningKey = "warnSeafrontOnce";
         if (!document.cookie.split('; ').find(row => row.startsWith(warningKey))) {            
            document.cookie = warningKey + "=true; expires=Fri, 31 Dec 9999 23:59:59 GMT; Secure";
            $('#seafrontWarningModal').modal()   
        }        
    });
</script>
