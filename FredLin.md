[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 10/129~ 10/23

[Settings]
  - Bug 1207471 - reorganized shims in alphabet order
    - r+ & landed
  - Bug 1190041 - use normal button for Firefox Account
    - landed
  - Bug 1211341 - Remove bluetooth APIv1 code from Settings
    - fixed all tests, the performance gain is ignorable, so not tracing it during 2.5
  - Bug 1216435 - remove RootPanelHandler from startup.js
    - WIP, raptor shows positive result
  - Arrange a pre-orlando meeting with UX at 11/3 for settings related discussion

[Review]
  - r+, Bug 1206471 - Settings app's "Cellular & Data" screen lets me toggle "Data Connection" and "Data Roaming" settings even when I have no SIM inserted
  - r+, Bug 1214533 - Move History and Cokie button down in Browsing Privacy panel
  - r+, Bug 1193910 - check for updates : nothing happens
  - r+, Bug 1216400 - Convert settings call sub-panels to use gaia-switch
  - r+, Bug 1202974 - [Settings] Convert call settings switches to use web components
    - learn & tested call related functions like FDN, call baring, call forwarding
  - r+, Bug 1014442 - [Settings] refactor Find My Device panel with AMD pattern
  - r+, Bug 1020699 - Follow-up to 908300: remove auto-resizing from font_size_utils.js once apps use Header Web Component

## 2015 Q4 Goals
1. Solving Blockers and implement &lt;to be decided&gt; features, as measured by implementation completeness.
2. Support Peripherals team for Bluetooth/transfer related Blockers, as measured by blocker burn down and days of blocker turnarounds.
3. Improving settings including css maintainability, dialog, load time, addon hackability etc. (curated todo list http://bit.ly/settingsbacklog), as measured by # of issues addressed (eng plan or implementation).
4. Pick up unfamilar parts related to settings ex: Wifi, APN, RIL..., as measured by # of parts handled (like bug addressedd)
5. Experiment features that make people want to use or develop FxOS, as measured by featured raised and planning detail/implementation progress.


## 2015 Q3 Delivered
1. Take over and tracking gaia settings/bluetooth remaining & future works https://wiki.mozilla.org/Gaia/Settings, https://wiki.mozilla.org/Gaia/Settings
2. More user friendly settings. Triage and mentor backlog bugs to improve the usablity.
3. Improve settings/foxfooding maintainability by adapting more gaia component, module, and Dialogs.
4. Support Peripherals team and deliver more stable and user friendly Bluetooth Transfer
5. Made addon (more quick settings) and developer tool (foxbox) to improve productivity
