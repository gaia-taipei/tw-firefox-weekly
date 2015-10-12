[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 09/30 - 10/02

[Settings]
  - Bug 1203461 - [Settings] USB protocol can only be changed when device unplugged
    - r+ & merged
  - Bug 1145332 - [FDN] Incorrect message displayed when updating FDN contact
    - merged
  - Bug 1204420 - [Settings] remove I-S panel strings in HTML 
    - r?
  - Bug 1210679 - [Settings] remove rest panel strings in HTML and update README
    - r?
  - check Security Panels with UX (Bug 1207717)
  - file Bug 1210284 - Hide Achievements panel for 2.5
    - yzen will handle it

[Review]
  - r+, Bug 1206600 - APN Settings does not select the correct item when user cancelled the dialog
  - r+, Bug 1207435 - Port carrier switches to use web components
  - r+, Bug 1206604 - The split item is only select-able on string, but not the whole field
  - r+, Bug 1170236 - Sometimes the screen to connect to a hidden network doesn't have the OK button enabled
  - r-, Bug 1206984 - Make Debug have a lower case name
  - r-, Bug 1202422 - [New-Homescreen] Migrate app/bookmark order from verticalhome

[other]
  - port fxos-quick-settings to new addon format
  - foxbox with web console

## 09/21 - 09/25

[Settings]
   - Bug 1205588 - [Settings] Define MediaStorage using new syntax provided by Observable
     - r+&landed
   - Bug 1203461 - [Settings] USB protocol can only be changed when device unplugged
     - r?

[Search]
  - Bug 1206572 - Add activity to support Search keyword through default provider
    - r?

[Homescreen]
  - Bug 1207308 - Long pressing on the homescreen to display Homescreen Settings will show a blank settings window with only a 'Settings' header and 'Done' button.
    - r+&landed

[Review]
   - r+, Bug 1202301 - [Settings] Convert messaging switches to use web components
   - r+, Bug 1200937 - APN Settings: support reading 'mtu' field from apn database
   - r+ Bug 1202403 - Use langpack.channel for the Get More Languages link in Settings > Language
   - r+, [Bug 1206272] can not go into settings -> home screens because panels/homescreens/wallpaper isn't loaded
   - r+, Bug 118070 - [Messages] Propose a setting to disable sending the read report
   - r+/mentor, Bug 1199461 - Name for carrier / operator is not consistent
   - r+, Bug 1206597 - [RTL] split bar is not correctly aligned
   - r+, Bug 1182924 - Cannot add new multiple-types data APN
   - r+, Bug 1203038 - [Settings] use dialog service to show reset-apn-warning dialog
   - r+, Bug 1208359 - [cleanup] Remove trailing spaces and correct typos in transfer_manager.js
   - r-, Bug 1203038 - [Settings] use dialog service to show reset-apn-warning dialog
   - r-, Bug 1168185 - Sync UI

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

