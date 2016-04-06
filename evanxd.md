## 03/28 ~ 04/01 ##

### Last week
* [WebEverywhere]
  - Built the PM2.5 device with Arduino.
    - Currently, it already supported to upload PM2.5 data to SensorWeb platform.
    - http://bugzil.la/1262364 - Implement the PM2.5 station with Arduino
    - https://github.com/sensor-web/arduino-station
  - JS Station supported USB TTL.
    - The USB TTL solution is the most cheap way to setup a PM2.5 station.
    - https://github.com/sensor-web/js-station/blob/master/lib/usbttl.js
  - Provided the content for the SensorWeb sticker.
    - http://bugzil.la/1260357 - Sticker for business card and station box
  - Filed bugs for automation test for SensorWeb website.
    - http://bugzil.la/1260691 - [meta] Automation test for SensorWeb
      - http://bugzil.la/1260692 - Build a robot to check that SensorWeb is alive
  - Weekly meeting
    - https://public.etherpad-mozilla.org/p/sensorebweb#lineNumber=79

### This week
* [WebEverywhere]
  - Implement the user management function.
    - Bug 1255712 - Implement the login feature
  - Refactor the data schema of DB and REST APIs.
  - Build the Chinese version of the landing page.
    - It helps Taiwanese understand SensorWeb and PM2.5 projects.
    - http://sensorweb.io/tw
