## 08/24 ~ 08/28 ##
### This Week ###
  - Help others to pick up things
### Last Week ###
  - prepare materials for handing over tasks.
  - sharing my previous experiences to the one who take over my tasks.
    - all items are done
    - the ownership of folders had transferred to Sean Lee
    - all files are downloaded to Rex and Luke's NB
  - Help others to pick up things
  - Help to keep gij TV green.
    - [Bug 1199150](http://bugzil.la/1199150) Fix marionette test GijTV failure

## 08/17 ~ 08/21 ##
### This Week ###
  - prepare materials for handing over tasks.
  - sharing my previous experiences to the one who take over my tasks.
### Last Week ###
  - prepare materials for handing over tasks.
  - finish handing over:
    - Presentation API to Rex Lee and YiFan
    - Vaani to Kevin Chen
      - [Bug 1194601](http://bugzil.la/1194601) IAC for Vaani to update of music player widget and send commands
      - (WIP patch made for Kevin)

## 08/10 ~ 08/14 ##
### This Week ###
  - prepare materials for handing over tasks.
### Last Week ###
  - Custom command
    - discuss with Kelly Davis on schema.org things.
      - He accepts the current thought as a shorten roadmap for music controlling
      - Wiki had updated

## 08/03 ~ 08/07 ##
### This Week ###
  - Custom command
    - discuss with Kelly Davis on schema.org things.
    - discuss with Ben Francis on JSON-LD
### Last Week ###
  - Custom command
    - redesign custom command
    - IAC protocol design
    - https://wiki.mozilla.org/Firefox_OS/Vaani/Music
  - Create test patch of presentation API for Sean Lin

## 07/27 ~ 07/31 ##
### This Week ###
  - Custom command
    - discuss with Kelly Davis on schema.org things.
    - finish the IAC detail design
### Last Week ###
  - Custom command
    - study schema.org and redesign each property correctly
    - https://wiki.mozilla.org/Firefox_OS/Vaani/Music
  - Mozilla hacks post
    - finished

## 07/20 ~ 07/24 ##
### This Week ###
  - Custom command
    - study schema.org and redesign each property correctly
    - define data structure based on schema.org to fulfill the requirement of music.
  - Mozilla hacks post
    - finish it.
### Last Week ###
  - Custom command
    - propose our design to them at 7/23.
    - https://wiki.mozilla.org/Firefox_OS/Vaani/Custom_Command
    - We will work on music [Bug 1172881](http://bugzil.la/1172881) and [Bug 1178273](http://bugzil.la/1178273)
  - Mozilla hacks post
    - almost finished
    - preview can be found at tech of mozilla.

## 07/13 ~ 07/17 ##
### This Week ###
  - Custom command
    - rebase the prototype code
    - prepare material for team to team discussion
  - Write a post for mozilla hacks

### Last Week ###
  - custom command
    - discuss with other devs of Vaani
      - https://groups.google.com/a/mozilla.com/forum/#!topic/fxos-vaani/4i5KVaUUSZY
      - team to team discussion will be made at 10AM of 7/23
    - update wiki: https://wiki.mozilla.org/Firefox_OS/Vaani/Custom_Command
  - [Bug 1183570](http://bugzil.la/1183570) [Browser]When user taps 'Share' and 'Cancel', share activity picker should animate out from the bottom.
    - A visual regression from my previous patch. Closing animations are gone.
  - [Bug 1182189](http://bugizl.la/1182189) Accessibility Regression in Utility tray exclusive visibility.
    - Hierarchy Manager is bound with focus manager. We should create another module handle focus and let hierarchy manager to handle aria-hidden.
    - transfer to Luke

## 07/06 ~ 07/10 ##
### This Week ###
  - custom command
    - write a slide and discuss with other devs of Vaani
    - update wiki

### Last Week  ###
  - prototype of custom command
    - based on Vaani and Web Activities to mock the behavior of custom command
      - Vaani: https://github.com/john-hu/vaani/tree/custom-command
      - Gaia: https://github.com/john-hu/gaia/tree/vaani-test-case
      - It works well based on the design of [wiki](https://wiki.mozilla.org/Firefox_OS/Vaani/Custom_Command) and activity.
  - explain system merge plain
    - https://wiki.mozilla.org/User:Johnhu/System_Merge

## 06/30 ~ 07/02 ##
### This Week  ###
  - prototype of custom command
    - based on Vaani and Web Activities to mock the behavior of custom command
      - Vaani: https://github.com/nullaus/fxos-voice-commands
  - explain system merge plain
    - https://wiki.mozilla.org/User:Johnhu/System_Merge

### Last Week ###
  - [Bug 1178689](http://bugzil.la/1178689) [gijtv] intermittent TEST-UNEXPECTED-FAIL | tv_apps/tv-epg/test/marionette/tv_epg_test.js
    - This looks like a media stream issue. Follow-up had filed at bug 1178725
  - Discuss Custom Command
    - [https://wiki.mozilla.org/Firefox_OS/Vaani/Custom_Command](https://wiki.mozilla.org/Firefox_OS/Vaani/Custom_Command)
  - File bugs for system merge: [meta bug 1147250](http://bugzil.la/1147250)
  - 2 Firefox OS add-on:
    - kill all active apps with one button
    - disable context menu at 3rd party apps

## 05/18 ~ 05/22 ##
### This Week ###
  - Review other's patch
  - [Bug 1167517](http://bugzil.la/1167517) browser context menu cannot open second time in flame but it works well in b2g-desktop
  - writing document for MDN

### Last Week ###
  - [Bug 1164353](http://bugzil.la/1164353) migrate browser context menu to use smart-modal-dialog
    - regression found, rework two times.
  - [Bug 1165801](http://bugzil.la/1165801) support icon in smart-modal-dialog
  - [Bug 1166673](http://bugzil.la/1166673) smart-modal-dialog.open() may need a reflow to have correct animation
  - [Bug 1167117](http://bugzil.la/1167117) [building block] smart-modal-dialog should line all buttons as one line

## 05/11 ~ 05/15 ##
### This Week ###
  - Gij-tv
  - Update smart-system to use latest smart-modal-dialog
    - We can benefit from these updating issue for merge works.
    - [Bug 1164353](http://bugzil.la/1164353) migrate browser context menu to use smart-modal-dialog

### Last Week ###
  - Contributor support:
    - [Bug 1162428](http://bugzil.la/1162428) search bar that shows up in apps does not work, ui gets stuck in it
      - This is confirmed as an invalid bug
  - Gij-tv
    - [Bug 1163460](http://bugzil.la/1163460) add more options to marionette loader to support tests not under apps/ folder
      - let marionette loader support tv folder.
    - [Bug 1164742](http://bugzil.la/1164742) gij-tv alternative: host all tests in tv-tests app
      - We have a patch to run all tv app's integration tests within phone build, which smart-system is excluded.
    - [Bug 1165160](http://bugzil.la/1165160) [Stingray] Marionette sendKeys method fails at dashboard app test
      - marionette test runs too fast so that the testing app is not the top-most UI and focus manager blocks the keyboard event for these case.
      - I had turned off the auto-recovery mechanism by default and partner can still turn it on through custom-settings.js
  - a lot of reviews

## 05/04 ~ 05/07 ##
### This Week ###
  - file integration tests bug and write it
    - app modal dialog
    - permission dialog
    - app install manager

### Last Week ###
  - [Bug 1159660](http://bugzil.la/1159660) [System][WindowManager] check activeElement before focus or blur a mozbrowser iframe
    - focus() too many times may cause performance issue.
  - [Bug 1161940](http://bugzil.la/1161940) [Stingray] Lost focus after pinning TV channel occasionally
  - [Bug 1162349](http://bugzil.la/1162349) integration tests for context menu

## 04/27 - 04/30 ##
### This Week ###
  - [Bug 1159660](http://bugzil.la/1159660) [System][WindowManager] check activeElement before focus or blur a mozbrowser iframe
    - focus() too many times may cause performance issue.
  - [Bug 1156596](http://bugzil.la/1156596) [System] Support device type in base module

### Last Week ###
  - Partner issue
    - [Bug 1148285](http://bugzil.la/1148285) Browser notification not working
      - It is gecko issue and already passed to tommy.
  - migrate BrowserContextMenu
    - [Bug 1154642](http://bugzil.la/1154642) [System] context menu doesn't focus to correct element and doesn't get focus while relaunch the app
      - discussed and r+. I will land the patch at monday of this week.

## 04/20 - 04/24 ##
### This Week ###
  - Partner issue
    - [Bug 1148285](http://bugzil.la/1148285) Browser notification not working
      - I am not sure the main problem here but phone may be also affected.
  - migrate BrowserContextMenu
    - [Bug 1154642](http://bugzil.la/1154642) [System] context menu doesn't focus to correct element and doesn't get focus while relaunch the app
      - root cause found and set r?
    - [Bug 1156596](http://bugzil.la/1156596) [System] Support device type in base module
      - find a way to start this issue if alive's patch is not landed.

### Last Week ###
  - migrate BrowserContextMenu
    - [Bug 1154642](http://bugzil.la/1154642) [System] context menu doesn't focus to correct element and doesn't get focus while relaunch the app
      - landed, but backed out
    - [Bug 1154607](http://bugzil.la/1154607) [System] make browser_context_menu as a base module
      - landed
    - [Bug 1155116](http://bugzil.la/1155116)  support keyboard event in jsmarionette
      - discuss key event with Ghislain Aus Lacroix (A-team)


## 04/13 - 04/17 ##
### This Week ###
  - migrate BrowserContextMenu
    - [Bug 1154642](http://bugzil.la/1154642) [System] context menu doesn't focus to correct element and doesn't get focus while relaunch the app
    - [Bug 1154607](http://bugzil.la/1154607) [System] make browser_context_menu as a base module

### Last Week ###
  - jshint bugs [Bug 996423](http://bugzil.la/996423)
    - [Bug 1152666](http://bugzil.la/1152666) telephony related
  - migrate BrowserContextMenu
    - [Bug 1154195](http://bugzil.la/1154195) [System] split the visual from browser_context_menu.js
    - [Bug 1154642](http://bugzil.la/1154642) [System] context menu doesn't focus to correct element and doesn't get focus while relaunch the app (reviewing)
    - file related bugs
  - Discuss enabling gij-tv
    - [Bug 1155110](http://bugzil.la/1155110) [meta] enable gij for TV

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
