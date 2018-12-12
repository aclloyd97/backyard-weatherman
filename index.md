---
layout: default
custom_css: leaflet
custom_js: leaflet

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
---
What the hell will this paper be about: a thesis.

### Flight through a Hurricane

Flight 2720 is a straight shot to Houston, about four hours and fifteen minutes. On a normal summer evening, the clouds would hang low and the sunset would beam colorful rays through the window as you landed quietly at Hobby International Airport.

With this flight, a crack of lightning flashed across the sky, but no thunder followed. My flight had been calm, up to this final push. On occasion, I get nervous flying through a storm, but today’s pilots kept the plane sailing smoothly through the sky despite the ruckus immediately around us. This ruckus was just beginning to hit Houston--Hurricane Harvey.

Originally, I was slightly concerned about flying from Boston, Massachusetts, to Houston, Texas because of the impending weather. Harvey began formation in the Gulf of Mexico just a few days prior and loomed closer as it’s path shifted, now projecting onto Houston. Now, it was here.

Anxious for the safety of the personnel and passengers, the airport sought to evacuate everyone as quickly as possible, not even taking my luggage off of the plane. As I walked through the airport, I decided that Sunday morning, maybe Sunday afternoon, I would leave to return to College Station to be there for the first day of university classes.

[![Flight Home](http://img.youtube.com/vi/XcU3w8aY-xk/0.jpg)](https://youtu.be/XcU3w8aY-xk)

Exiting the building, my dad brought the small Honda Civic instead of the tall Ford “Built Tough” Truck. Rain pelted the car as we drove off into the storm. We only technically live thirty minutes from the airport, but we had to drive very carefully with the rising waters.

Lighting flashed, thunder cracked, rain poured. Why Dad didn’t bring the truck, I’ll never know. We were the only ones on the road. I could almost imagine the car stuck at the top of Beltway 8,  water encircling us, with the news helicopter flying above us, pointing their spotlight, broadcasting that there were another set of idiots trying to drive around town during a hurricane.

Despite my worries, we made it home safely. Once inside, I decided to stick to my original plan to head to College Station, unless something drastic changed. I had experienced hurricanes and flooding before. In my neighborhood, we were built with good drainage systems and retention ponds. I felt confident I could wake up in the morning and the roads clear to drive, as I had experienced with previous severe weather.

[![Car Ride Home](https://img.youtube.com/vi/sEUkP2Z39hE/0.jpg)](https://www.youtube.com/watch?v=sEUkP2Z39hE)

### Hurricanes

The trick about hurricanes, however, is there are a number of factors. Hurricanes are violent storms, particularly in the Caribbean, with a wind force that exceeds 74 mph; tropical storms, in comparison, is 34 mph. These storms are defined by their wind speed using the Saffir-Simpson Hurricane Wind Scale. This scale has its problems, as it does not account for other dangerous factors such as the physical size of the storm and the amount of precipitation. Hurricane Ike, for example, had the wind speed of a typical Hurricane Category 2, but the storm surge comparable to a Category 5. Hurricane Harvey was a Category 4 hurricane, with a wind speed of 130 mph.

*Map #1*
<div id="map1" class="map leaflet-container" style="width: 700px; height: 400px; position: relative;"></div>
<script src="https://cdn.jsdelivr.net/gh/aclloyd97/LeafletHeatMap/index.html"></script>

I woke up and looked out my window and my street was flooded, my yard was flooded. Harvey was flooding Houston. There was no way to leave as I had originally anticipated. The first night, Harvey dumped from [range or average] on Houston. Across the city, rain was covering everything from front lawns like mine to entire cities.

[![Flooded Streets](https://raw.githubusercontent.com/aclloyd97/LeafletHeatMap/master/images/IMG-20170827-WA0028.jpg)](https://youtu.be/i_ZaAlJTPFg)

There was really nothing to do over the next few days besides watch the rainfall and the water rise. My family began making plans about moving furniture onto bricks, moving books upstairs, preparing for worst case scenarios. We took photos of the encroaching stormwater to help track how much rain has passed, how much flooding was happening. After e-mailing my professors about how I was unable to leave my house except by kayak, I turned to social media like everyone else. I watched my Facebook feed, my Instagram feed, etc. Everyone I knew was sharing and posting about the storm, about the rain, about the rising water. Hurricane Harvey became the most mediated natural disaster in history.

*maybe a gallery of images*

But that seemed to be all you could do during this natural disaster, watch your front lawn, wait for the water to lower, pray /for the rain to stop, find stories of hope from a personal newsfeed. It was all anyone could talk about. The amount of rain that fell during the was monumental. After a few days, the storm left and the floodwaters drained. I drove off to College Station without another thought about the rain.

### Looking at the Hurricane in Retrospect

When presented with a data-based project for English, my thoughts then turned back to the rain, the sheer amount of it. After some searching, I found a comprehensive list of the entire rainfall for the weather event, from formation to dissipation. The data listed over 6900 sources, a different location across the nation that recorded rainfall data. Some sources, such as a local Dallas network of airports, made sense. But one data source, CoCoRaHs, contributed 6750 sets of data for the hurricane. Expansive, the data ranged from Texas to Maine. Who was this?

*Map #2*
<div id="map2" class="map leaflet-container" style="width: 700px; height: 400px; position: relative;"></div>
<script src="https://cdn.jsdelivr.net/gh/aclloyd97/LeafletHeatMap/index.html"></script>

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

---
<body>

<div id="map1" class="map"></div>

<br>

<div id="map2" class="map"></div> <!--map 2 locations-->

<br>

<!---SCRIPTS-->
<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.3.4/leaflet.js"></script>
<script src="https://cdn.jsdelivr.net/gh/mourner/simpleheat/simpleheat.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/Harvinator/Leaflet.heat@patch-1/src/HeatLayer.min.js"></script>

    <!--DATASETS-->
        <!--August 26-->
            <script src="LeafletHeatMap/data/usa/du_0826.js"></script>         <!--var usaPoints_0826-->
            <script src="LeafletHeatMap/data/texas/dt_0826.js"></script>       <!--var texasPoints_0826-->
            <script src="LeafletHeatMap/data/landfall/dl_0826.js"></script>    <!--var landfallPoints_0826-->
        <!--Total Rainfall-->
            <script src="LeafletHeatMap/data/usa/du_total.js"></script>        <!--var usaPoints_total-->
            <script src="LeafletHeatMap/data/texas/dt_total.js"></script>      <!--var texasPoints_total-->
            <script src="LeafletHeatMap/data/landfall/dl_total.js"></script>   <!--var landfallPoints_total-->
        <!--Other-->
            <script src="LeafletHeatMap/data/flight_path.js"></script>         <!--var flight_boston-->

<!--MAPS-->
<script> //Map 1 = August 26 and Flight
    var map1 = L.map('map1', {center: [37, -97], zoom: 4}); // [Lat, Lng], Magn
        // Texas Center: [31.5, -100], 6
        // USA   Center: [37, -97], 4

    var controls = L.control.layers().addTo(map1);

    var tiles1 = L.tileLayer('http://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}.png', {
        attribution: '&copy; <a href="http://osm.org/copyright">OpenStreetMap</a> contributors, &copy; <a href= "https://cato.com/attributions">CARTO</a>'
    }).addTo(map1);
        //https://tile.thunderforest.com/landscape/{z}/{x}/{y}.png?apikey=<insert-your-apikey-here>

    var hurricaneIcon = L.icon({
          iconUrl: 'hurricane-icon.png',

          iconSize:     [50, 48], // size of the icon
          //shadowSize:   [50, 64], // size of the shadow
          iconAnchor:   [25, 25], // point of the icon which will correspond to marker's location
          shadowAnchor: [4, 62],  // the same for the shadow
          popupAnchor:  [0, 0] // point from which the popup should open relative to the iconAnchor
          });

    var airplaneIcon = L.icon({
          iconUrl: 'airplane.png',

          iconSize:     [50, 50], // size of the icon
          //shadowSize:   [50, 64], // size of the shadow
          iconAnchor:   [50, 50], // point of the icon which will correspond to marker's location
          shadowAnchor: [4, 62],  // the same for the shadow
          popupAnchor:  [0, 0] // point from which the popup should open relative to the iconAnchor
          });


    // Copy and paste this line, changing the variable name (totalHeatLayer) and the input to the heatLayer
    // function (addressPoints) to add additional heat layers (keep track of the variable name, you'll need
    // it to add map controls)

    var usaHeat = L.heatLayer(usaPoints_0826, {
          max: 1.0,
          gradient: {
              0.1: "white",
              0.2: "lightsteelblue",
              0.3: "lightblue",
              0.4: "powderblue",
              0.5: "skyblue",
              0.6: "cornflowerblue",
              0.7: "dodgerblue",
              0.8: "blue" ,
              0.9: "mediumblue",
              1.0: "navy"}
              //https://www.w3schools.com/colors/colors_groups.asp
          }).addTo(map1);

    var landfall = L.polyline(landfallPoints_0826, {color: "red"}).addTo(map1); //Tool Tip
      //marker.bindTooltip("my tooltip text").openTooltip();
      L.marker ([29.1, -97.5], {icon:hurricaneIcon}).bindPopup("Hurricane Harvey<br>August 26</br>").addTo(map1)

    var flight_boston = L.polyline(flightPoints, {color: "green"}).bindPopup("Flight 2728's path<br>from Boston to Houston</br>").addTo(map1);
      //flightPoints.forEach(function(point){new L.marker([point[0],point[1]]).bindPopup(point[3]).addTo(map1);})
      L.marker ([36.16, -86.78], {icon:airplaneIcon}).bindPopup("Flight Path<br>August 26</br>").addTo(map1)   //"Nashville, Tennessee"

    controls.addOverlay(usaHeat,"Heat Layer");
    controls.addOverlay(landfall, "Hurricane Harvey path");
    controls.addOverlay(flight_boston, "Fligt 2728");

</script>
<script> //Map 2 = Hurricane Totals and Sources as a Layer
  var map2 = L.map('map2', { center: [31.5, -100], zoom: 6}); // [Lat, Lng], Magn
      // Texas Center: [31.5, -100], 6
      // USA   Center: [37, -97], 4

  var controls = L.control.layers().addTo(map2);

  var tiles = L.tileLayer('http://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}.png', {
      attribution: '&copy; <a href="http://osm.org/copyright">OpenStreetMap</a> contributors, &copy; <a href= "https://cato.com/attributions">CARTO</a>'
  }).addTo(map2);

  var hurricaneIcon = L.icon({
        iconUrl: 'hurricane-icon.png',

        iconSize:     [50, 48], // size of the icon
        //shadowSize:   [50, 64], // size of the shadow
        iconAnchor:   [25, 25], // point of the icon which will correspond to marker's location
        shadowAnchor: [4, 62],  // the same for the shadow
        popupAnchor:  [0, 0] // point from which the popup should open relative to the iconAnchor
        });

  // Copy and paste this line, changing the variable name (totalHeatLayer) and the input to the heatLayer
  // function (addressPoints) to add additional heat layers (keep track of the variable name, you'll need
  // it to add map controls)

/*  var dataSources = L.marker({
    addressPoints2.forEach(function(point){
        new L.marker([point[0],point[1]]).bindPopup(Source).addTo(map1);
        })
  addressPoints2.forEach(function(point){
            //new L.marker([point[0],point[1]]).bindPopup(point[0]+", "+point[1]).addTo(map1);
*/
  var texasHeat = L.heatLayer(usaPoints_total, {
        max: 1.0,
        gradient: {
            0.1: "white",
            0.2: "lightsteelblue",
            0.3: "lightblue",
            0.4: "powderblue",
            0.5: "skyblue",
            0.6: "cornflowerblue",
            0.7: "dodgerblue",
            0.8: "blue" ,
            0.9: "mediumblue",
            1.0: "navy"}
            //https://www.w3schools.com/colors/colors_groups.asp
        }).addTo(map2);

  var landfall = L.polyline(landfallPoints_total, {color: "red"}).bindTooltip("Hurricane Harvey's<br>storm path</br>").addTo(map2); //Tool Tip

  controls.addOverlay(heat,"Heat Layer");
  controls.addOverlay(landfall, "Hurricane Harvey path");

  //addressPoints2.forEach(function(point){
            //new L.marker([point[0],point[1]]).bindPopup(point[0]+", "+point[1]).addTo(map1);
          //})
</script>
<!--<script> //Play my Video
var ppbutton = document.getElementById("vidbutton");
ppbutton.addEventListener("click", playPause);

myVideo = document.getElementById("flight_vid");
function playPause() {
    if (myVideo.paused) {
        myVideo.play();
        ppbutton.innerHTML = "Pause";
        }
    else  {
        myVideo.pause();
        ppbutton.innerHTML = "Play";

</script>-->
</body>
---
