## 09/21 - 09/25 ##

### This Week ###
* [TV]
  - [REVIEW] Bug 1210694 - [Stingray][fling-player][TV][2.5] Require control panel funcitons

    - Play
    - Pause
    - Update the time bar as video progress

  - [WIP] Bug 1210700 - [Stingray][fling-player][TV][2.5] Fling player control panel should hide and show based on user's key input

    - Hide automatically
    - Show when user presses remote control's key

  - [WIP] Bug 1210702 - [Stingray][fling-player][TV][2.5]The Fling player visual spec implementation

  - [FIXED] Bug 1202361 - [Stingray][fling-player][TV][2.5] (TV side) TV to receive video casted from Fennec

     - Complete basic handling video casting request from remote
     - Work with the latest Presentation API

  - [FIXED] Bug 1210316 - [Stingray] Button icons on the Fling player control panel

     - Add the Fling player'ss button icons into the smart icons

### Last Week ###
* [TV]
  - Bug 1202361 - [Stingray]Cast video to TV (receiver side)

    - Work on UI

    - Add play, pause, backward and forward funtions

    - Handle user's key input

* [FIXED] Bug 1205118 - [gatt] GijTV is mostly perma-failing
    - Skip the failed GijTV tests may be cause by the test environment first.
      Open a follow-up Bug 1207453 - [gatt] GijTV tests fail due to test environment issue
      to track root cause.
