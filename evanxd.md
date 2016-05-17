## 05/09 ~ 05/13 ##

### Last week
* [SensorWeb]
  - Bug 1271541 - Implement the Web widget
    - Landed.
  - Fire bugs for [all Q2 goals][Q2 Goals].
    - Bug 1271206 - [meta] Implement SensorWeb for Q2
      - Bug 1271214 - [meta] Implement the new design of landing page
      - Bug 1271226 - [meta] Refactor SensorWeb back-end
      - Bug 1271227 - [meta] Refactor SensorWeb front-end
      - Bug 1271228 - [meta] Polish SensorWeb front-end
      - Bug 1271229 - [meta] Implement the PM2.5 mobile app for schools
      - Bug 1271230 - [meta] Fix blog issues 
      - Bug 1271231 - [meta] Documentation for SensorWeb project
      - Bug 1271232 - [meta] Deliver Product to Market
      - Bug 1271235 - Survey how to make a PM2.5 station with SIM card connection
  - Made a new PM2.5 station for Particle demo.

### This week
  - Start to implement the [new design][New Design] of landing page.
    - Bug 1271215 - Add the SensorWeb video on the landing page
    - Bug 1271216 - Integrate PM2.5 sensors map in the landing page
    - Bug 1271217 - Add blog article list on the landing page
      - Need to investigate how to get our blog article list through some kind of API first.
  - Refactor the back-end module
    - Bug 1271213 - Refactor the `http://api.sensorweb.io/sensors/${SENSOR_ID}` API

[New Design]: https://github.com/sensor-web/sensorweb-design/blob/master/Screens/Home.png
[Q2 Goals]: https://bugzilla.mozilla.org/show_bug.cgi?id=1271205#c1
