[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 10/26~ 10/30

With landing Bug 1216435 & Bug 1218271, Settings decrease ~200ms loadtime (2.8s->2.6s).

[Settings]
  - checking Settings blockers
  - Bug 1214951 - addon plus button UX is inconsistent with home screens
    - r+ & landed
  - Bug 1216075 - [Add-ons]there is no version information in Add-on description screen
    - r+ & landed
  - Bug 1218271 - panel specific styles should be defined in app.css or separated css
    - r+ & landed
  - Bug 1216435 - remove RootPanelHandler from startup.js
    - r+ & landed
  - Bug 1213763 - Rename permission options to align with firefox desktop
    - r+ & landed
  Bug 1219563 - blue the 'get more addons' & 'get more homescreens' link after click
    - r+ & landed
  - Bug 1144426 - [Settings][Call Barring] Entering the wrong passcode in Call Barring results in ambiguous error message
    - WIP
  - Bug 1188082 - [Flame][Settings] Switch gets stuck in the disabled mode during turned on/off when we leave settings immediately
    - identify issue

[Review]
  - r+, Bug 1215654 - [Metrics] Metrics may not be recorded when level set to enhanced
  - r+, Bug 1172349 - [Settings] Convert remaining switches to use gaia-switch component
  - r+, Bug 1217734 - Deleted duplicate home screens can be selected
  - r+, Bug 1215654 - [Metrics] Metrics may not be recorded when level set to enhanced
  - r+, Bug 1215546 - Fixes add-on list after installation
  - r+, Bug 1217730 - Duplicated home screens shown as separate home screens
  - r+, Bug 1217741 - using content_scripts that will be included in manifest by default instead of fetching manifest.json
  - r+, Bug 1218723 - [RTL][Settings]The parenthesis in "Data Settings" view are displayed incorrectly


## 2015 Q4 Goals
1. Solving Blockers and implement &lt;to be decided&gt; features, as measured by implementation completeness.
  - Bug 1194045 - USB protocol can only be changed while USB storage is disabled.
  - Bug 1203461 - USB protocol can only be changed when device unplugged
  - Bug 1145332 - [FDN] Incorrect message displayed when updating FDN contact
  - Bug 1145332 - [Settings]A alert "An unknown error occurred" pops up when user enters wrong PIN 2 and then changes to new PIN2
  - Bug 1216075 - there is no version information in Add-on description screen.
  - Bug 1217717 - Turn off airplane mode from settings, the wifi will be toggled on/off alternately
2. Support Peripherals team for Bluetooth/transfer related Blockers, as measured by blocker burn down and days of blocker turnarounds.
3. Improving settings including css maintainability, dialog, load time, addon hackability etc. (curated todo list http://bit.ly/settingsbacklog), as measured by # of issues addressed (eng plan or implementation).
  - Bug 1214507 - polish startup procedure
  - With landing Bug 1216435 & Bug 1218271, Settings decrease ~200ms loadtime (2.8s->2.6s)
  - Bug 1205588 - [Settings] Define MediaStorage using new syntax provided by Observable
  - Bug 1214951 - addon plus button UX is inconsistent with home screens
  - Bug 1203473 - [Settings] Define AppStorage using new syntax provided by Observable
  - Bug 1182129 - [PP] Back out privacy panel
4. Pick up unfamilar parts related to settings ex: Wifi, APN, RIL..., as measured by # of parts handled (like bug addressedd)
  - [Call Barring] Bug 1205596 - [Settings]A alert "An unknown error occurred" pops up when user enters wrong PIN 2 and then changes to new PIN
  - learning through review & tests
    - r+ [Messaging] Bug 1202301 - Convert messaging switches to use web components
    - r+ [APN Settings] Bug 1200937 - support reading 'mtu' field from apn database
    - r+ [Call Barring] Bug 1212715 - [Settings] Convert call barring settings switches to use web components
    - r+ [FDN] Bug 1216400 - Convert settings call sub-panels to use gaia-switch
    - r+ [Call Forwarding] Bug 1202974 - [Settings] Convert call settings switches to use web web components
5. Experiment features that make people want to use or develop FxOS, as measured by featured raised and planning detail/implementation progress.


## 2015 Q3 Delivered
1. Take over and tracking gaia settings/bluetooth remaining & future works https://wiki.mozilla.org/Gaia/Settings, https://wiki.mozilla.org/Gaia/Settings
2. More user friendly settings. Triage and mentor backlog bugs to improve the usablity.
3. Improve settings/foxfooding maintainability by adapting more gaia component, module, and Dialogs.
4. Support Peripherals team and deliver more stable and user friendly Bluetooth Transfer
5. Made addon (more quick settings) and developer tool (foxbox) to improve productivity
