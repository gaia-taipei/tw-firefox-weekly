## 11/23 - 11/27 ##

### Last Week ###

* [TV Remote Control]
    - [WIP] Bug 1215457 - [TV 2.5] Secure connection between remote control server and client
        - synced up with Eric and broke down the tasks
    - [Done] Bug 1212402 - [TV 2.5] Apply visual spec to the TV remote control app
        - got the new icon from the visual designer
        - landed on master and v2.5
    - [Done] Bug 1227808 - [TV 2.5] Change the settings of Authorized Devices in Remote Control feature to a simple object instead of a serialized string
        - wrote a patch and landed on master
    - [Done] Bug 1228415 - [TV][Remote Control] Revise l10n string for the disable remote control page
        - wrote a patch and landed on master
    - [Done] Bug 1228409 - [TV][Remote Control] Revise l10n string for the offline page
        - wrote a patch and landed on master
    - [Done] Bug 1228405 - [TV][Remote Control] The QR code should be selected by default after saving the new settings
        - wrote a patch and landed on master

* [TV Marketplace]
    - [Done] Bug 1225081 - [TV][2.5] Open, close and navigate marketplace hosted/packaged app by preview window
        - helped on reviewing the Ricky's patch
        - got tests failed on Ricky's patch
        - took over this bug
        - refactored the patch
        - re-landed on master

* [TV App Usage Metrics]
    - [Done] Bug 1221933 - [TV] FxOS TV Metrics - Track the downloadable browser app on partner's TV build
        - helped on listing the steps for partners
    - [Done] Bug 1221924 - [TV] FxOS TV Metrics - Treat the smart-home as an overlay instead of an app
        - reviewed the patch
    - [Done] Bug 1221929 - Track the last used app before turning the device off
        - reviewed the patch

* [Other Patches Review]
    - Bug 1226495 - Clean up the build-in app list on TV production build
    - Bug 1227811 - [TV] FTE layout of option menu is incorrect
    - Bug 1217765 - [TV][2.5] Permission prompt up window broken on TV

### This Week ###

* [TV Remote Control]
    - [New] Bug 1228262 - [TV 2.5] Implement secure connection on remote control client side

* [Other Patches Review]
    - Bug 1161440 - [Presentation WebAPI] trusted UI for device selection on Firefox OS

* [PTO]
    - 12/02 - 12/04

## Mozlando Plan ##

1. System Merge / Etienne Segonzac, Michael Henretty
2. FlyWeb / Douglas Sherk
3. TV Marketplace / David Almstrom, Lindsay Saunders

## 2015 Q4 Goals ##

1. TV Remote Control implementation, as measured by implementation completeness. 60%
2. TV Marketplace Workflow mentoring, as measured by implementation completeness. 20%
3. TV optimized library (a.k.a. Spatial Navigation) implementation and presentation, as measured by implementation completeness. 10%
4. TV App Usage Metrics porting, as measured by blockers burn down. 5%
5. SUPL NI implementation, as measured by implementation completeness. 5%
