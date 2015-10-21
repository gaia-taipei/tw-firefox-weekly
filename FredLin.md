[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 10/12 ~ 10/16

[Settings]
  - Bug 1182129 - [PP] Back out privacy panel
    - fix remaining conflict and landed to master
  - Bug 1169154 - [Settings] It shows a blank area instead of the timezone when manually select a city located in the current timezone
    - r+ & landed
  - Bug 1205596 - [Settings]A alert "An unknown error occurred" pops up when user enters wrong PIN 2 and then changes to new PIN
    - learn call barring and apply for the service
    - r+ & landed
  - Bug 1214507 - polish startup procedure
    - r+ & landed
  - Bug 1210668 - Convert call_barring header to gaia-header
    - landed
  - File doable bugs of Bug 1207717 (Security Settings Panels)
  - submit Settings and web component meetup at Orlando
  - Bug 1211341 - Remove bluetooth APIv1 code from Settings
    - WIP

[Review]
  - r+, Bug 1212864 (--/normal): [New-Homescreen] Remove pinch gesture
  - r+, Bug 1196680 - [settings] Hotspot panel header close icon should be grey
  - r+, Bug 1209978 - [Settings] CSS refactoring
  - r+, Bug 1212715 - [Settings] Convert call barring settings switches to use web components
  - r+, Bug 1208205 - [Metrics] Replace Settings Metrics checkboxes with 3 state radio button to match FTE
  - r+, Bug 1212905 - [New-Homescreen] Make scroll-snapping optional, disabled by default

## 2015 Q4 Goals
1. Solving Blockers and implement low storage features
2. Support Peripherals team for Bluetooth/transfer related Blockers
3. Improving settings including css maintainability, dialog, load time, addon hackability etc. (curated todo list http://bit.ly/settingsbacklog)
4. Pick up unfamilar parts related to settings ex: Wifi, APN, RIL...
5. Experiment features that make people want to use or develop FxOS


## 2015 Q3 Delivered
1. Take over and tracking gaia settings/bluetooth remaining & future works https://wiki.mozilla.org/Gaia/Settings, https://wiki.mozilla.org/Gaia/Settings
2. More user friendly settings. Triage and mentor backlog bugs to improve the usablity.
3. Improve settings/foxfooding maintainability by adapting more gaia component, module, and Dialogs.
4. Support Peripherals team and deliver more stable and user friendly Bluetooth Transfer
5. Made addon (more quick settings) and developer tool (foxbox) to improve productivity
