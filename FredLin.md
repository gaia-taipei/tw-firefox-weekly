[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 11/30 ~ 12/04

General
 - Bug 1223725 - apply preset eslint rules
   - in review
 - Bug 1205650 - [feature] support immediate actions on selection menu
   - f?

Settings
- Bug 1163205 - remove the focus when user open an external link
  - r+ & landed
- Bug 1228276 - move showFormatedSize to a separate module
  - r+ & landed
- Bug 1229239 - Storage.umsMasterSettingChanged function is not exist in media_storage.js
  - r+ & landed
- Bug 1221876 - Intermittent root_settings_test.js | check root panel settings common tests airplane mode enable airplane mode
  - r+ & landed
- Bug 1229263 - move getSupportedNetworkInfo into module
  - WIP
- Bugs 1201 -> 1183


[Review]
  - r+, Bug 1227295 - Unable to modify password after entering an incorrect password for a WiFi network
  - r+, Bug 1210673 - use dialog service to show media storage dialogs
  - r+, Bug 1179425 - Time remaining to full charge is not displayed in battery settings
  - r+, Bug 1014440 - [Settings] refactor Firefox Accounts panel with AMD pattern

## 2015 Q4 Goals
1. Solving Blockers and implement &lt;to be decided&gt; features, as measured by implementation completeness.
  - Blockers
    - Bug 1194045 - USB protocol can only be changed while USB storage is disabled.
    - Bug 1203461 - USB protocol can only be changed when device unplugged
    - Bug 1145332 - [FDN] Incorrect message displayed when updating FDN contact
    - Bug 1145332 - [Settings]A alert "An unknown error occurred" pops up when user enters wrong PIN 2 and then changes to new PIN2
    - Bug 1216075 - there is no version information in Add-on description screen.
    - Bug 1217717 - disable the Airplane mode interaction before the wifi panel is ready
    - Bug 1220046 - [Settings] In Settings view, the "Airplane mode" item is displayed wrongly as toggled off, but actually it is on
2. Support Peripherals team for Bluetooth/transfer related Blockers, as measured by blocker burn down and days of blocker turnarounds.
  - Bug 1211341 - Remove bluetooth APIv1 code from Settings
  - Bug 1211342 - Remove bluetooth APIv1 code from Bluetooth
  - Bug 1211357 - Remove bluetooth APIv1 code from System
  - Bug 1222484 - Pairing doesn't work with enter key
3. Improving settings including css maintainability, dialog, load time, addon hackability etc. (curated todo list http://bit.ly/settingsbacklog), as measured by # of issues addressed (eng plan or implementation).
  - Bug 1214507 - polish startup procedure
  - [2.5] With landing Bug 1216435 & Bug 1218271, Settings decrease ~200ms loadtime (2.8s->2.6s)
  - With landing Bug 1228252, 1228265 & 1228276, Settings decrease ~300ms loadtime (2.6s->2.3s)
  - Bug 1205588 - [Settings] Define MediaStorage using new syntax provided by Observable
  - Bug 1214951 - addon plus button UX is inconsistent with home screens
  - Bug 1203473 - [Settings] Define AppStorage using new syntax provided by Observable
  - Bug 1182129 - [PP] Back out privacy panel
  - conclude [settings change for 2.5](https://groups.google.com/forum/#!searchin/mozilla.dev.fxos/settings$20change/mozilla.dev.fxos/q1zqwKFAIps/eE7oeWbQAAAJ)
4. Pick up unfamilar parts related to settings ex: Wifi, APN, RIL..., as measured by # of parts handled (like bug addressedd)
  - [Call Barring] Bug 1205596 - [Settings]A alert "An unknown error occurred" pops up when user enters wrong PIN 2 and then changes to new PIN
  - learning through review & tests
    - r+ [Messaging] Bug 1202301 - Convert messaging switches to use web components
    - r+ [APN Settings] Bug 1200937 - support reading 'mtu' field from apn database
    - r+ [Call Barring] Bug 1212715 - [Settings] Convert call barring settings switches to use web components
    - r+ [FDN] Bug 1216400 - Convert settings call sub-panels to use gaia-switch
    - r+ [Call Forwarding] Bug 1202974 - [Settings] Convert call settings switches to use web web components
5. Experiment features that make people want to use or develop FxOS, as measured by featured raised and planning detail/implementation progress.
   - release [postcss-bidirection](https://github.com/gasolin/postcss-bidirection) for web developer to adopt our LTR/RTL syntax
   - [propose new preprocessor syntax and use 3rd party implementation ](https://groups.google.com/forum/#!searchin/mozilla.dev.fxos/propose/mozilla.dev.fxos/pJpzClI-5R8/28-PngIFAwAJ)
   - [start discussion of using node instead of xpcshell](https://groups.google.com/forum/#!topic/mozilla.dev.fxos/RS7YVDb9SHE)

## 2015 Q3 Delivered
1. Take over and tracking gaia settings/bluetooth remaining & future works https://wiki.mozilla.org/Gaia/Settings, https://wiki.mozilla.org/Gaia/Settings
2. More user friendly settings. Triage and mentor backlog bugs to improve the usablity.
3. Improve settings/foxfooding maintainability by adapting more gaia component, module, and Dialogs.
4. Support Peripherals team and deliver more stable and user friendly Bluetooth Transfer
5. Made addon (more quick settings) and developer tool (foxbox) to improve productivity
