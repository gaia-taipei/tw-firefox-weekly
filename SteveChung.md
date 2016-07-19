## This week 7/11 ~ 7/15
* Firefox front-end:
  - Devtool
    - Joined the daily stand up meeting.
    - (Resolved)[Bug 1283522](https://bugzilla.mozilla.org/show_bug.cgi?id=1283522) - Reps: support -0 grip in number rep => Patch reviewed and merged in central.
    - (R+)[Bug 1285530](https://bugzilla.mozilla.org/show_bug.cgi?id=1285530) - Reps: Off by one error in grip-array max length => Patch reviewed but need to rebased on another ongoing patch that might need to change test.
    - (ni?)[Bug 1284855](https://bugzilla.mozilla.org/show_bug.cgi?id=1284855) -  Reps: match spacing and brace placement in nested objects/arrays => Need more infor to the owner to clarify some questions.

## Last week 7/4 ~ 7/8
* SensorWeb:
  - Experiment about using github page as staging server with [subcomponent](https://github.com/sensor-web/sensorweb-frontend/tree/a3f3f51698590bee9340d8d7c8c9bf65a83654ca)
  
* Firefox front-end:
  - Quick glance for QX issues: [Bug 1270272](https://bugzilla.mozilla.org/show_bug.cgi?id=1270272) - Holding area for future QX clusters / work
    - [Bug 1271768](https://bugzilla.mozilla.org/show_bug.cgi?id=1271768) - [QX cluster] Consider updating default videocontrols
      - Not much we could do. Maybe only the video control visual refresh?
      - [Bug 1271765](https://bugzilla.mozilla.org/show_bug.cgi?id=1271765) - Visual refresh of media controls
    - [Bug 1271782](https://bugzilla.mozilla.org/show_bug.cgi?id=1271782) - [QX cluster] Consider improvements to the find-bar
      - [Bug 259640](https://bugzilla.mozilla.org/show_bug.cgi?id=259640) - Find Toolbar's highlight mode should show matches next to or on top of scrollbar => Looks like a good feature, but it may need further ux support.
    - [Bug 1271779](https://bugzilla.mozilla.org/show_bug.cgi?id=1271779) - [QX cluster] Consider improvements to in-content preferences
      - [Bug 752197](https://bugzilla.mozilla.org/show_bug.cgi?id=752197) - Make all prefs dialogs windows in-content => Some dialogs in advanced page need to be moved to in-content style, but all of them might need further communication for UX spec.
  - Devtool
    - [Bug 1283522](https://bugzilla.mozilla.org/show_bug.cgi?id=1283522) - Reps: support -0 grip in number rep => Study & submit a simple patch for first feedback.
