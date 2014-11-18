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
