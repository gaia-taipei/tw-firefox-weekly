## This week 3/27 ~ 3/31
* Autofill
    - [Bug 990219](https://bugzilla.mozilla.org/show_bug.cgi?id=990219) - Story Breakdown - [Form Autofill] Auto-create profiles based off submitted form data
        - f+. blocked by [bug 1348193](https://bugzilla.mozilla.org/show_bug.cgi?id=1348193).
    - [Bug 1341569](https://bugzilla.mozilla.org/show_bug.cgi?id=1341569) - [Form Autofill] Collect information on how much time users spent on page with forms (w/wo form autofill)
        - Got some feedback and it is also blocked by [bug 1348193](https://bugzilla.mozilla.org/show_bug.cgi?id=1348193).
    - [Bug 1333344](https://bugzilla.mozilla.org/show_bug.cgi?id=1333344) - [Form Autofill] Telemetry metrics
        - Had a meeting with Joe and MattN, created [bug 1352330](https://bugzilla.mozilla.org/show_bug.cgi?id=1352330) for verifying heuristic accuracy.
    - [Bug 1348193](https://bugzilla.mozilla.org/show_bug.cgi?id=1348193) - [Form Autofill] Handle submit action for the formLike component that is not based on form element
        - r?, leverage the existing earlysumbit event observer instead of DOM submit event for both form and formless case.
    - [Bug 1350264](https://bugzilla.mozilla.org/show_bug.cgi?id=1350264) - Allow users to re-enable form autofill feature after all populated fields were cleared manually
        - r?, but it might need more discussion for other edge cases.
* Devtool:
    - N/A
