## 04/07 - 04/10 ##
### This Week ###
  - jshint bugs [Bug 996423](http://bugzil.la/996423)
    - [Bug 1152666](http://bugzil.la/1152666) telephony related
  - clear review queue
  - explore other possible changes before bug 1094759 landed.
### Last Week ###
  - Prepare the dependency of each module
  - Wrapping each module
    - [Bug 1152198](http://bugzil.la/1152198) Migrate Lockscreen to BaseModule model
      - blocked by [Bug 1094759](http://bugzil.la/1094759), system bootstrap by alive.
  - jshint bugs [Bug 996423](http://bugzil.la/996423)
    - [Bug 1152665](http://bugzil.la/1152665) download manager (landed)
    - [Bug 1152671](http://bugzil.la/1152671) value selectors (landed)
    - [Bug 1152666](http://bugzil.la/1152666) telephony related

## 03/30 - 04/02 ##
### Last Week ###
  - Prepare change items in smart system app
    - http://goo.gl/cTzFJU
  - Discuss on how to merge
  - [Bug 1150423](http://bugzil.la/1150423) - [System] expose device type to system app

### This Week ###
  - Prepare the dependency of each module
  - File bugs for wrapping each module

## 03/23 - 03/27 ##
### Last Week ###
  - Prepare change items in smart system app
    - Read the patch one by one to finish the slides
      - http://goo.gl/cTzFJU
  - Read W3C WAI-ARIA specs
 
### This Week ###
  - Prepare change items in smart system app
    - http://goo.gl/cTzFJU
  - Discuss on how to merge
 
## 03/16 - 03/20 ##
### Last Week ###
  -[Bug 1141887](http://bugzil.la/1141887) - [Stingray] apply focus manager to app window related UIs
    - land the patch
  - Prepare change items in smart system app
    - http://goo.gl/cTzFJU

### This Week ###
  - Prepare change items in smart system app
    - Read the patch one by one to finish the slides
      - http://goo.gl/cTzFJU

## 03/09 - 03/13 ##
### Last Week ###
  - [Bug 1136591](http://bugzil.la/1136591) - [Meta][Stingray] expose isVisible and focus API for all modules of smart system app
    - Review and Land other patches
  - [Bug 1141887](http://bugzil.la/1141887) - [Stingray] apply focus manager to app window related UIs
    - Implementing, Testing and Reviewing

### This Week ###
  -[Bug 1141887](http://bugzil.la/1141887) - [Stingray] apply focus manager to app window related UIs
    - land the patch
  - Prepare change items in smart system app
  - Read W3C spec: WAI-ARIA 1.0 User Agent Implementation Guide

## 03/02 - 03/06 ##
### Last Week ###
* Focus Fallback [Meta Bug](http://bugzil.la/stingray-focus-fallback)
  - [Bug 1136590](http://bugzil.la/1136590) - [Stingray] focus fallback algorithm
  - [Bug 1139314](http://bugzil.la/1139314) - [Stingray] focus fallback algorithm v2 
  - [Bug 1136591](http://bugzil.la/1136591) - [Meta][Stingray] expose isVisible and focus API for all modules of smart system app
    - [Bug 1136603](http://bugzil.la/1136603) - [Stingray] expose isVisible and focus API for sleep_menu
    - [Bug 1136606](http://bugzil.la/1136606) - [Stingray] expose isVisible and focus API for permission_manager
    - [Bug 1136618](http://bugzil.la/1136618) - [Stingray] expose isVisible and focus API for trusted ui
### This Week ###
  - [Bug 1136591](http://bugzil.la/1136591) - [Meta][Stingray] expose isVisible and focus API for all modules of smart system app
    - Review and Land other patches
  - Prepare change items in smart system app
  - Read W3C spec: WAI-ARIA 1.0 User Agent Implementation Guide

## 02/24 - 02/26 ##
### Last Week ###
* Focus Fallback Analysis
  https://docs.google.com/a/mozilla.com/spreadsheets/d/1VCSfKJ5raw2jS_lILThMKidI4lvxueCZkPJaLPisPeM/edit?pli=1

### This Week ###
* Focus Fallback [Meta Bug](http://bugzil.la/stingray-focus-fallback)
  - [Bug 1136590](http://bugzil.la/1136590) - [Stingray] focus fallback algorithm
  - [Bug 1136591](http://bugzil.la/1136591) - [Meta][Stingray] expose isVisible and focus API for all modules of smart system app

## 02/16 - 02/17 ##
* PTO

## 1/26 ~ 2/6 ##
### Last 2 Week ###
* Fling Player/Sender
  - [Bug 1123183](http://bugzil.la/1123183) - [Stingray] Receiver app for video sharing
  - [Bug 1125059](http://bugzil.la/1125059) - [Stingray] Sender app for video sharing
  - [Bug 1126667](http://bugzil.la/1126667) - [Stingray][demo] handle default remote screen at phone's system
  - [Bug 1127749](http://bugzil.la/1127749) - [Stingray][demo] fling-player should show itself while app is opened.
  - [Bug 1127755](http://bugzil.la/1127755) - [Stingray][demo] apply building blocks to fling-sender
  - [Bug 1127745](http://bugzil.la/1127745) - [Stingray][demo] fling-sender doesn't listen the click event of start button
  - [Bug 1128384](http://bugzil.la/1128384) - [Stingray][demo] fling only supports string format message and shouldn't use addEventListener
  - [Bug 1128438](http://bugzil.la/1128438) - [Stingray][demo] add close button to fling sender app for testing
  - [Bug 1128437](http://bugzil.la/1128437) - [Stingray][demo] handle session close in fling-player

* Partner Blocker
  - [Bug 1123300](http://bugzil.la/1123300) - [Stingray] cannot display context menu with some decks
  - [Bug 1124599](http://bugzil.la/1124599) - [Stingray] improve the search-bar text animation
  - [Bug 1125780](http://bugzil.la/1125780) - [Stingray] Parent app cannot get focus after inline activity child finished
  - [Bug 1129807](http://bugzil.la/1129807) - [Stingray][demo] hide and release video while visibility is hidden
  - [Bug 1130251](http://bugzil.la/1130251) - [Stingray][Home] unexpected movement of Card List
* Smart Screen
  - [Bug 1127657](http://bugzil.la/1127657) - [Stingray] Promotion list background image mismatches with focused button

### This Week ###
* Stingray Demo bugs
* Partner Questions:
  - How to terminate inline app from parent

## 1/19 - 1/23 ##
### Last Week ###
* [Partner Blocker]
  - [Bug 1123177](http://bugzil.la/1123177) - [Stingray] jshint failure in tv smart-system (ETA: 1/23)
  - [Bug 1105650](http://bugzil.la/1105650) - [Stingray] Apply visual of button on app-deck list (r+, but gaia tree closed, ETA: 1/16)
  - [Bug 1119713](http://bugzil.la/1119713) - [Stingray] KeyNavigationAdapter should handle both keydown and keyup event (ET
A: 1/23)
  - [Bug 1122360](http://bugzil.la/1122360) - [Stingray][smart-system] search app cannot be launched
  - [Bug 1122460](http://bugzil.la/1122460) - [Stingray] when some foreground app crashed, homescreen is launched (should be landing app)
    - not land to master, already tested at partner's device.
* Others
  - [Bug 1114869](http://bugzil.la/1114869) - [Stingray][System] error occurred while landing app is missing
  - Discuss protocol of fling player and fling sender:
    - [Bug 1123183](http://bugzil.la/1123183) - [Stingray] Receiver app for video sharing

### This Week ###
* Fling Player/Sender
  - [Bug 1123183](http://bugzil.la/1123183) - [Stingray] Receiver app for video sharing
  - [Bug 1125059](http://bugzil.la/1125059) - [Stingray] Sender app for video sharing
* Partner Blocker
  - [Bug 1123300](http://bugzil.la/1123300) - [Stingray] cannot display context menu with some decks
  - [Bug 1124599](http://bugzil.la/1124599) - [Stingray] improve the search-bar text animation

## 1/12 - 1/16 ##
### Last Week ###
* [Partner Blocker]
  - [Bug 1118641](http://bugzil.la/1118641) - [Stingray][Home] the app name in card will be moved to top-right slightly when we focus it (r+ but not landed, ETA: 1/16)
  - [Bug 1105650](http://bugzil.la/1105650) - [Stingray] Apply visual of button on app-deck list (steal from dwi2, WIP got, ETA: 1/16)
* Other Bugs:
  - [Bug 1119748](http://bugzil.la/1119748) - [Stingray] use keydown to change the focus (r+, but not landed)
  - [Bug 1120342](http://bugzil.la/1120342) - [Stingray] build failed because of jshint error- missing semicolon

### This Week ###
* [Partner Blocker]
  - [Bug 1123177](http://bugzil.la/1123177) - [Stingray] jshint failure in tv smart-system (ETA: 1/23)
  - [Bug 1105650](http://bugzil.la/1105650) - [Stingray] Apply visual of button on app-deck list (r+, but gaia tree closed, ETA: 1/16)
  - [Bug 1119713](http://bugzil.la/1119713) - [Stingray] KeyNavigationAdapter should handle both keydown and keyup event (ETA: 1/23)
  - [Bug 1122360](http://bugzil.la/1122360) - [Stingray][smart-system] search app cannot be launched

## 1/5 - 1/9 ##
### Last Week ###
* [hash launch]
  - [Bug 1113495](http://bugzil.la/1113495) - [Stingray][Smart-system] Accept specified URL from home on opening app (landed)
  - [Bug 1113499](http://bugzil.la/1113499) - [Stingray][Smart-home] Open app with specified hash/URL (landed)
* [Partner's Requirements]
  - [Bug 1115350](http://bugzil.la/1115350) - [Stingray] no wallpaper is necessary for smart-home (fixed)
  - [Bug 1100892](http://bugzil.la/1100892) - [Stingray] bootup with transparency background (fixed)
  - [Bug 1115351](http://bugzil.la/1115351) - [Stingray][Home] video element is hidden by overlayed home (fixed)
* [Search Bar]
  - [Bug 1115273](http://bugzil.la/1115273) - [Stingray][smart-home/smart-system] Implement opening search bar (landed)
* [Partner Meeting and Offline Supporting]
  - Dashboard
  - Home
  - App start-up dialog
    -[Bug 1119655](http://bugzil.la/1119655) - [Stingray] show a dialog while opening some apps (fixed)

### This Week ###
* [Partner Blocker]
  - [Bug 1118641](http://bugzil.la/1118641) - [Stingray][Home] the app name in card will be moved to top-right slightly when we focus it (r+ but not landed, ETA: 1/16)
  - [Bug 1105650](http://bugzil.la/1105650) - [Stingray] Apply visual of button on app-deck list (steal from dwi2, WIP got, ETA: 1/16)
* Other Bugs:
  - [Bug 1119748](http://bugzil.la/1119748) - [Stingray] use keydown to change the focus (r+, but not landed)
  - [Bug 1120342](http://bugzil.la/1120342) - [Stingray] build failed because of jshint error- missing semicolon

----------
## 12/15 - 12/19 ##
### Last Week ###
* [Interactive Notifications]
  - Meta Bug: [Bug 1109493](http://bugzil.la/1109493)
    - [Bug 1111416](http://bugzil.la/1111416) - [Stingray] tv build unable to copy web components in tv_shared) (landed)
  - reviewing:
    - [Bug 1110652](http://bugzil.la/1110652) - [Stingray] use interactive notification to show desktop-notification
    - [Bug 1111414](http://bugzil.la/1111414) - [Stingray] create UI for and apply visual to interactive notification
* [Home as Overlay]
  - [Bug 1107950] - [Stingray][System] homescreen app is shown as overlay on top of an alive app while press home. (reviewing)
### This Week ###
* [Interactive Notifications]
  - Meta Bug: [Bug 1109493](http://bugzil.la/1109493)
    - rebase and land code
  - [Bug 1114397] - [Stingray] Use keyboard to move the focus between notification buttons
* Bug:
  - [Bug 1114399] - [Stingray][Home] settings button group isn't collapsed consistently while losting focus

----------
## 12/08 - 12/12 ##
### Last Week ###
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1101371](http://bugzil.la/110371) - [Stingray][home] apply visual spec to card list
  - Rebased and Land the Code
    - [Bug 1105576](http://bugzil.la/1105576) - [Stingray][home] update visual of smart home to meet visual spec v2
    - [Bug 1101373](http://bugzil.la/1101373) - [Stingray][home] apply visual spec to filter (footer
    - [Bug 1101369](http://bugzil.la/1101369) - [Stingray][home] apply visual to information block
### This Week ###
* [Interactive Notifications]
  - Meta Bug: [Bug 1109493](http://bugzil.la/1109493)
    - [Bug 1111416](http://bugzil.la/1111416) - [Stingray] tv build unable to copy web components in tv_shared)
    - [Bug 1110652](http://bugzil.la/1110652) - [Stingray] use interactive notification to show desktop-notification

----------
## 12/01 - 12/05 ##
### Last Week ###
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1101373](http://bugzil.la/1101373) - [Stingray][home] apply visual spec to filter (footer)
    - [Bug 1105576](http://bugzil.la/1105576) - [Stingray][home] update visual of smart home to meet visual spec v2
* [Landing app]
  - [Bug 1107976](http://bugzil.la/1107976) - [Stingray][System] handle app to landing app opening.
    - landing app will be only deck in the past. But if we want to support normal app as landing app, it may be opened in app deck.
* Discussions
  - TV testing environment
    - discuss with Alex and have a WIP patch which only works at Ubuntu box
    - [Bug 1107759](http://bugzil.la/1107759) - Support resizing b2g desktop window
  - IAC
    - discuss with Ehsan
      - He will work on a XHR server for service worker in the future. ETA is still undefined.

### This Week ###
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1101371](http://bugzil.la/1101371) - Support resizing b2g desktop window
* discuss and work on notifications
----------

## 11/24 - 11/28 ##

update skipped
----------

## 11/17 - 11/21 ##

### Last Week ###
* [TV Settings]
  - Meta Bug: [Bug 1067793](http://bugzil.la/1067793)
    - [Bug 1093529](http://bugzil.la/1093529) - [Stingray] link home app to settings app
      - landed
    - [Bug 1093530](http://bugzil.la/1093530) - [Stingray][System] make inline activity be transparent in background
      - landed
    - [Bug 1094069](http://bugzil.la/1094069) - [Stingray][Settings] implement option menu
      - landed
    - [Bug 1100282](http://bugzil.la/1100282) - [Stingray][System] only allow smart-settings app to handle configure activity
      - landed
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1102142](http://bugzil.la/1102142) - [Stingray][home] create circle-button and use it in Home's search button
      - reviewing

### This Week ###
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1102153](http://bugzil.la/1102153) - [Stingray][home] create button-group and apply to settings button in home app
    - [Bug 1101369](http://bugzil.la/1101369) - [Stingray][home] apply visual to information block
    - [Bug 1101373](http://bugzil.la/1101373) - [Stingray][home] apply visual spec to filter (footer)
    - [Bug 1101371](http://bugzil.la/1101371) - [Stingray][home] apply visual spec to card list
  - maybe file a bug to add web component support in tv_shared folder
----------

## 11/10 - 11/14 ##

### Last Week ###
* [TV Setting]
  - Meta Bug: [Bug 1067793](http://bugzil.la/1067793)
    - [Bug 1092934](http://bugzil.la/1092934) - [Stingray] Create settings app for changing landing app
      - landed
    - [Bug 1093436](http://bugzil.la/1093436) - [Stingray][Home] move libraries to tv-shared folder
      - landed
    - [Bug 1093529](http://bugzil.la/1093529) - [Stingray] link home app to settings app
      - reviewing
    - [Bug 1093534](http://bugzil.la/1093534) - [Stingray][Settings] add settings list to settings app
      - landed

### This Week ###
* Partner Meeting
  - https://wiki.mozilla.org/FirefoxOS/Stingray/SmartScreen/
  - https://docs.google.com/a/mozilla.com/spreadsheets/d/19BPa6GCxPPoLZxy_r1tJSPG4JZVUCbpSKwSXYjJ5Jbg/edit#gid=0

------------

## 11/03 - 11/07 ##

### Last Week ###
* Prepare materials for the discussion with partners
  - https://wiki.mozilla.org/FirefoxOS/Stingray/SmartScreen/

* Replying partners' emails
  - Card UI

* [TV Setting]
  - [Bug 1067793](http://bugzil.la/1067793) - [Stingray] Customization on the default landing card/deck
    - add a standalone settings app and modify system app to support special UI for it.

### This Week ###
* [TV Setting]
  - Meta Bug: [Bug 1067793](http://bugzil.la/1067793)
    - [Bug 1092934](http://bugzil.la/1092934) - [Stingray] Create settings app for changing landing app
    - [Bug 1093436](http://bugzil.la/1093436) - [Stingray][Home] move libraries to tv-shared folder
    - [Bug 1093529](http://bugzil.la/1093529) - [Stingray] link home app to settings app
    - [Bug 1093534](http://bugzil.la/1093534) - [Stingray][Settings] add settings list to settings app

------------

## 10/27 - 10/31 ##

### Last Week ###
* [TV System]
  - [Bug 1090808](http://bugzil.la/1090808) - [Stingray] lazy load smart-system's modules
    - no significant improvement at flame device.
    - patch can be found at:
      - https://github.com/huchengtw-moz/gaia/tree/bug-1098080-lazy-load-pr
  - [Bug 1090810](http://bugzil.la/1090810) - [Stingray] add SettingsCache to smart system
    - PR ready and waiting for review result.
    - https://github.com/mozilla-b2g/gaia/pull/25641
  - [Bug 1090806](http://bugzil.la/1090806) - [Stingray] remove useless file from smart-system
    - touch_forwarder, secure_*, and system_dialog* had been removed
    - landed.
  - [Bug 1090822](http://bugzil.la/1090822) - [Stingray] trusted_ui in smart system should lock screen in default mode. 
    - landed.
  - A SettingsCache with async_storage backend gives the most improvement.
    - https://github.com/huchengtw-moz/gaia/tree/bug-1090810-local-storage
    - It uses async_storage instead of local storage and the branch name is a typo.
  - The overall performance report can be found at:
    - https://docs.google.com/a/mozilla.com/spreadsheets/d/19BPa6GCxPPoLZxy_r1tJSPG4JZVUCbpSKwSXYjJ5Jbg/edit#gid=0

### This Week ###

* Prepare materials for the discussion with partners
  - https://wiki.mozilla.org/FirefoxOS/Stingray/SmartScreen/

* Replying partners' emails
  - Card UI

* [TV Setting]
  - [Bug 1067793](http://bugzil.la/1067793) - [Stingray] Customization on the default landing card/deck
    - add a standalone settings app and modify system app to support special UI for it.

## 10/20 - 10/24 ##

### Last Week ###
* [TV System]
  - Done locally, revice patch according to review's opinions
    - [Bug 1074040](http://bugzil.la/1074040) - [Stingray] Default landing deck
      - [PR](https://github.com/mozilla-b2g/gaia/pull/25247)
  - Use SettingsCache to boost up boot-up time.
    - [branch](https://github.com/huchengtw-moz/gaia/tree/bug-1074040-settings-cache)
  - Try to lazy load modules
    - https://tw-dev-eng.etherpad.mozilla.org/151

This Week

* [TV System]
  - Lazy loading files
  - check the performance

* [TV Setting]
  - [Bug 1067793](http://bugzil.la/1067793) - [Stingray] Customization on the default landing card/deck
    - add a standalone settings app and modify system app to support special UI for it.
