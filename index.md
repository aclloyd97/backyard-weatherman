---
layout: default
custom_css: leaflet
custom_js: leaflet
---
<style type="text/css">
  #map {
    width:400px;
    height:550px;
    background-color: red;
  }
</style>

{% if page.custom_js %}
     {% for js_file in page.custom_js %}
     <script src='/javascript/{{ js_file }}.js' type="text/javascript"></script>
     {% endfor %}
   {% endif %}

{% if page.custom_css %}
       {% for stylesheet in page.custom_css %}
       <link rel="stylesheet" href="/css/{{ stylesheet }}.css" media="screen" type="text/css">
       {% endfor %}
   {% endif %}

### Flight through a Hurricane

The flight over, for the most part, had been smooth. Looking out the window, the clouds hung low. A crack of lightning flashed across the sky--but no thunder followed. Typically I get nervous flying through a storm but today I hadn’t. The pilot kept the airplane relatively smooth and calm, considering the impending Hurricane.

Flying from Boston, MA on I was concerned that they wouldn’t let us leave for Houston, TX.[^1] The Hurricane began formation in the Gulf of Mexico a few days prior, and as it loomed closer it became projected for Houston. My flight was one of the last to land in Houston. Wanting to evacuate the personnel as soon as possible, the airport didn’t allow luggage off of the plane. As I walked through the airport, I decided that Sunday morning, maybe Sunday afternoon, I would leave to return to College Station to be there for the first day of university classes.  

[![Flight Home](http://img.youtube.com/vi/XcU3w8aY-xk/0.jpg)](https://youtu.be/XcU3w8aY-xk)

My dad picked me up in the 2014 Honda Civic, a small car, and we drove into the storm. Rain pelted the car at the same rate that we saw on the plane. On the ground, however, the water was much scarier. Why Dad didn’t bring the truck, I’ll never know. Lighting flashed, thunder cracked, rain poured. Dad drove us slowly through, trying to be careful of the rising water. There were times that I thought we would be the idiots stuck on the highway on the news. We made it home safely, thank goodness. I went to sleep fully expecting to leave in the morning for college.

> You see, this wasn’t my first hurricane.

[![Car Ride Home](https://img.youtube.com/vi/sEUkP2Z39hE/0.jpg)](https://www.youtube.com/watch?v=sEUkP2Z39hE)

### Hurricanes

The trick about hurricanes, however, is there are a number of factors. Hurricanes are violent storms, particularly in the Caribbean, with a wind force that exceeds 74 mph; tropical storms, in comparison, is 34 mph. These storms are defined by their wind speed using the Saffir-Simpson Hurricane Wind Scale. This scale has its problems, as it does not account for other dangerous factors such as the physical size of the storm and the amount of precipitation. Hurricane Ike, for example, had the wind speed of a typical Hurricane Category 2, but the storm surge comparable to a Category 5. Hurricane Harvey was a Category 4 hurricane, with a wind speed of 130 mph.

*Map #1*
<div id="map" class="map leaflet-container" style="height: 500px; position:relative;"></div>

I woke up and looked out my window and my street was flooded, my yard was flooded. Harvey was flooding Houston. There was no way to leave as I had originally anticipated. The first night, Harvey dumped from [range or average] on Houston. Across the city, rain was covering everything from front lawns like mine to entire cities.

[![Flooded Streets](https://raw.githubusercontent.com/aclloyd97/LeafletHeatMap/master/images/IMG-20170827-WA0028.jpg)](https://youtu.be/i_ZaAlJTPFg)

There was really nothing to do over the next few days besides watch the rainfall and the water rise. My family began making plans about moving furniture onto bricks, moving books upstairs, preparing for worst case scenarios. We took photos of the encroaching stormwater to help track how much rain has passed, how much flooding was happening. After e-mailing my professors about how I was unable to leave my house except by kayak, I turned to social media like everyone else. I watched my Facebook feed, my Instagram feed, etc. Everyone I knew was sharing and posting about the storm, about the rain, about the rising water. Hurricane Harvey became the most mediated natural disaster in history.

*maybe a gallery of images*

But that seemed to be all you could do during this natural disaster, watch your front lawn, wait for the water to lower, pray /for the rain to stop, find stories of hope from a personal newsfeed. It was all anyone could talk about. The amount of rain that fell during the was monumental. After a few days, the storm left and the floodwaters drained. I drove off to College Station without another thought about the rain.

### Looking at the Hurricane in Retrospect

When presented with a data-based project for English, my thoughts then turned back to the rain, the sheer amount of it. After some searching, I found a comprehensive list of the entire rainfall for the weather event, from formation to dissipation. The data listed over 6900 sources, a different location across the nation that recorded rainfall data. Some sources, such as a local Dallas network of airports, made sense. But one data source, CoCoRaHs, contributed 6750 sets of data for the hurricane. Expansive, the data ranged from Texas to Maine. Who was this?

*Map #2*
<div id="map1" class="map leaflet-container" style="height: 500px; position:relative;"></div>

CoCoRaHS (pronounced ko-ko-rozz), stands for “Community Collaborative Rain, Hail, and Snow Network.” This non-profit network of volunteers across all fifty states place a rain gauge in their backyard, observe the collected rain data every day, and record the data in an online portal. Originating in Colorado after a deadly flood, CoCoRaHS encourages entire communities to record weather observations. The data the network supplies empower everyone from local weathermen and city utilities to large organizations like the National Weather Service and the USDA for a variety of research and informational uses.

The data recorded by backyard weathermen for this citizen science project has a huge impact. Everyone is encouraged to participate--families, schools, scientists.[^2] The data collected by individuals across the nation go into individual, daily precipitation report. From there, the organization compiles them into a Public Information Statement that can be used by the public and media. This data helps everyone from hydrologists to forecaster.

To join the organization, there are a few steps to be undertaken. After filling out a general form and purchasing a standard four inch rain gauge, the last step is a short series of free training videos to help teach proper use of rain gauges and scientific principles. Depending on which kind or precipitation found in your area, there are different presentations. One is entitled "In Depth Snow Measurement" and another is "Measuring Reference Evapotranspiration." After learning how to measure precipitation accurately and consistently, the gauge and participant are ready to go. Measuring rainfall data helps support your local weather station with scientific data to make more accurate forecasts.

If you're interested in learning more about citizen weather science, visit your local weather station for opportunities to learn more about meteorology such as:[^3]
  * Jet Stream, an online introductory textbook to meteorology
  * SKYWARN, training to become a storm spotter for severe weathermen
  * Emergency Preparedness Seminars, to become informed about local emergency preparedness situations




<hr>
{% include sharing.html %}

##### Footnotes:

[^1]: 2728 Dep BOS at 05:10 PM. Arrived in Houston from Boston at 08:25 PM. Travel time was 4 hrs 15 mins.

[^2]: http://www.upr.org/post/shower-national-weather-service-data-being-backyard-weather-observer.

[^3]: https://www.forbes.com/sites/dennismersereau/2018/07/31/8-fantastic-resources-to-learn-more-about-the-weather/#7f7c40f07dfa
