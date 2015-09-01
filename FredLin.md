[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 08/24 ~ 08/28

* [Settings]
  - go through foxfood issues and identify good first bugs
  - Bug 1161927 - [Settings] Migrate settings app to use new system update API 
    - WIP, fix unit tests (38 -> 23 fail)
    - will postpone it until fixing most of blockers
  - Bug 1194045 - [Flame][settings]USB protocol can only be changed while USB storage is disabled
    - WIP, discuss UI spec with harly & have HTML mock

* [Bluetooth]
  - Bug 1197711 callscreen bt receiver icon
    - 2.5+, r?
  - Bug 1197735 - [Bluetooth]Share contact via bluetooth, the blank view is shown
    - 2.5+, r+ & landed

* [WoT]
  - WoT discussion & [proposal](https://docs.google.com/a/mozilla.com/presentation/d/1HNGaxYBc8bP6Ok-rn9G4CYijg8OTgmPiqs3tMr3PaNQ/edit?usp=sharing)

* code review
  * r+, Bug 1172349 [Settings] Convert remaining switches to use gaia-switch component
  * r+, Bug 1196645 - [Settings] Show old API add-ons as "disabled" or better "obsolete"
  * r+, Bug 994691 - [Bluetooth] Confirmation icon too small and text should be center aligned

## 08/17 ~ 08/21

* [Settings]
  - Bug 1166495 - [Settings][Screen lock] Passcode lock screen transition animation flows in the wrong direction
    - 2.5+, r+ & landed

* [Bluetooth]
  - Bug 1191104 - [Bluetooth] Enable bluetooth pop-up appears briefly after sharing from gallery in landscape
    - 2.5+, r+ & landed
  - Bug 1175955 - passive pairing not work when fresh flash
    - 2.5+, r+ & landed

* Identify issue
  - Bug 1150823 - [Flame][Settings]The "Find My Device" login page does not update timely.
  - bug 1179177 [Flame][Settings] It shows SIM 1 as default in FTE, but SIM 2 is the default in Settings.
    - test and recategorize to FTU

* code review
  - r-, Bug 1180666 - Manage Homescreens
  - r+ [Bug 1160992] [Notifications]When the cell phone service goes out, the data traffic option in Notification is not available

* WIP
  - Bug 1161927 new system update API
    - learn how to test system update
  - Aggregate Settings goals & tasks for 2.5 https://wiki.mozilla.org/Gaia/Settings#v2.5_Roadmap

## 08/10 ~ 08/14

* Bug 1194036 - [keyboard] syntaxs fix to generate jsdoc ghpage
  - landed

* [WIP]
  - Bug 1166495 - [Settings][Screen lock] Passcode lock screen transition animation flows in the wrong direction
    - add passcodeHelper and fix tests, set r?
  - Bug 1161927 - system update API tests fix
    - rebase and fixing tests

* code review
  - Bug 1170464 - [SMS] fix remain jsdoc error
  - Bug 1190548 - Implement explanations inside of gaia-switch

* PTO 1.5 days

## 08/03 ~ 08/07

Fix and Review Settings/BT related issues.

* [Bluetooth]
  - Bug 1183496 NFC BT adapter not found
    - 2.5+, landed
  - Bug 1088450 - Bluetooth transfer text is confusing and should be changed
    - r+ & landed
  - Bug 1149715 - [Bluetooth] Lose Access to Active Request when Clearing notifications
    - 2.5+, r+ & landed

* [Settings]
  - Bug 1171385 - [Settings][l10n] "Service workers" is hard-coded
    - r+ & landed
  - [experimental] Bug 1191638 - Settings app navigation need to honour History API 

* [WIP]
  - Bug 1161927 - Migrate to the new system update API and manage QA testing
    - review and write tests

- code review
 
## 07/27 ~ 07/31

Triage and Review Settings/BT related issues.

* [Bluetooth]
  - Identify bug 1187250 - BT `, +more` is gecko issue
  - bug 1187834 - [RTL][Bluetooth]With device language in Arabic, the Parentheses of the device name display abnormally in Bluetooth page
    - r+ & landed
  - bug 1187836 - [RTL][Bluetooth]With device language in Arabic, the Parentheses of the device name displays abnormal in "Paired devices" or "Devices in the Area"
    - r+ & landed
  - [Bluetooth] If user accepts pair request through notification, they receive a pop up saying the request is expired
    - 2.5+, r+ & landed
  - bug 1088450 - improve Bluetooth transfer messages
    - ui-review?

* [Settings]
  - Clean & track ej & arthur's meaningful bugs, update to https://etherpad.mozilla.org/settings
  - rebase arthur bug 1161927 - Migrate to the new system update API and manage QA testing, will review and write tests

* [WIP]
  - bug 1185688 - [Bluetooth] Only show 'request is expired' through notification when the pendingPairing is not available

- code review
