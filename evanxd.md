## 05/02 ~ 05/06 ##

### Last week
* [SensorWeb]
  - Discuss the new design of landing page with team.
    - [The design spec][New Design].
  - Investigate open map solutions for legal issue.
    - We might integrate Open Street Map on SensorWeb.
    - For the integration works, we can use OpenLayers 3 library.
  - Discuss legal issues with Legal team and Firefox Account team.
    - We might integrate Firefox Account on SensorWeb.
  - Bug 1271205 - Set Q2 goals for Project SensorWeb
    - Discuss the goals with team.
  - Prepare Maker Faire
    - Make a new air quality station with Particle Photon.
    - [A slide][SensorWeb in Maker Faire] that helps team explain SensorWeb to visitors.
    - Educate contributors.

### This week
* [SensorWeb]
  - Fire bugs for [all Q2 goals][Q2 Goals].
  - Start to implement the [new design][New Design] of landing page.
    - Bug 1271215 - Add the SensorWeb video on the landing page
    - Bug 1271216 - Integrate PM2.5 sensors map in the landing page
    - Bug 1271217 - Add blog article list on the landing page
      - Need to investigate how to get our blog article list through some kind of API first.
  - Refactor the back-end module
    - Bug 1271213 - Refactor the `http://api.sensorweb.io/sensors/${SENSOR_ID}` API
  - Make a new PM2.5 station for demo.

[New Design]: https://github.com/sensor-web/sensorweb-design/blob/master/Screens/Home.png
[SensorWeb in Maker Faire]: http://evanxd.io/sensorweb-makerfaire
[Q2 Goals]: https://bugzilla.mozilla.org/show_bug.cgi?id=1271205#c1
