[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

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
    - landed
  - Bug 1088450 - Bluetooth transfer text is confusing and should be changed
    - r+ & landed
  - Bug 1149715 - [Bluetooth] Lose Access to Active Request when Clearing notifications
    - r+ & landed

* [Settings]
  - Bug 1171385 - [Settings][l10n] "Service workers" is hard-coded
    - r+ & landed
  - [experimental] Bug 1191638 - Settings app navigation need to honour History API 

* [WIP]
  - Bug 1161927 - Migrate to the new system update API and manage QA testing
        review and write tests

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
    - r+ & landed
  - bug 1088450 - improve Bluetooth transfer messages
    - ui-review?

* [Settings]
  - Clean & track ej & arthur's meaningful bugs, update to https://etherpad.mozilla.org/settings
  - rebase arthur bug 1161927 - Migrate to the new system update API and manage QA testing, will review and write tests

* [WIP]
  - bug 1185688 - [Bluetooth] Only show 'request is expired' through notification when the pendingPairing is not available

- code review
