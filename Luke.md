## 09/14 - 09/18 ##

### Last Week ###

* [TV remote control]
    - [WIP] Bug 1203045 - [TV 2.5] Dispatch input messages via mozInputMethod API in server side
        - software keyboard on TV can be used with remote control page at the same time now
        - traced a Gecko error message but finally found that it's a long-standing issue that may not need to be addressed in this bug
    - [WIP] Bug 1197772 - [TV 2.5] Implement a client-side page for TV remote control prototyping
        - modified several behaviors based on demo case
    - Spec discussion with UX

* [SUPL NI]
    - [Done] Bug 1195602 - [GPS] Support SUPL NI case in Gaia
        - the gaia-try on v2.2r has been fixed but one of the unit tests were still failed
        - helped identify the root cause (bug 1204859)
        - landed on v2.2r
        - answered partner's questions via mail

* [Other]
    - Reviewed the MDN article with Mash and Rex

### This Week ###

* [TV remote control]
    - [New] Bug 1205939 - (TV_RemoteControl_TVSide) [TV][2.5][meta][TV side] Remote Control
        - follow up spec and break down tasks

* [Metrics]
    - [New] Bug 1204759 - Back port app usage metrics to TV System
