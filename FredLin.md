[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 11/02 ~ 11/06

[Settings]
  - gather current settings in-planning list from UX/engineering perspective https://public.etherpad-mozilla.org/p/settings
  - triage settings bug lists
    - reduce bugs number from 1403 -> 1242
    - increase backlogs from 128 -> 162
  - Bug 1217717 - disable the Airplane mode interaction before the wifi panel is ready
    - r+ & landed
  - Bug 1144426 - [Settings][Call Barring] Entering the wrong passcode in Call Barring results in ambiguous error message
    - r+ & landed
  - Bug 1220515 - blur get more languages link after click
    - r+ & landed
  - Bug 1220046 - unobserve airplanemode when uninit,
    - r+ & landed
  - Discuss settings requirements with UX
  - Bug 1211341 - Remove bluetooth APIv1 code from Settings

[Bluetooth]
  - Bug 1211342 - Remove bluetooth APIv1 code from Bluetooth
    - r?

[immediate action in Selection menu]
  - Bug 1206572 - Add activity to support Search keyword through default provider
    - merged
  - support immediate actions on selection menu
    - PR, need fix gij tests

- update https://wiki.mozilla.org/Gaia/Shared/Components state

[Review]
  - r+, Bug 1218705 - [Settings] The descriptions of "Data Connection" and "Data Roaming" should be illustrated more precisely
  - r+, Bug 1220978 - migrate Bluetooth to use NotificationHelper
  - r+, Bug 808141 - Wi-Fi shows "offline" whereas it should be "Not connected"
  - r+, Bug 1220532 - the accessible-app-icon aria string is incorrect
  - r-, Bug 1219306 - Disable lockscreen related settings when NO_LOCK_SCREEN is 1

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
