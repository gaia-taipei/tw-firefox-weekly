## This week 9/5 ~ 9/7(OOO 9/8 ~ 9/16)
* Devtool:
    - [Bug 1261154](https://bugzilla.mozilla.org/show_bug.cgi?id=1261154) - Use "formatAbbreviatedBytes" utility from tree map in sidebar.
        - No progress, postpone this issue since it's low priority one.
    - [Bug 1296187](https://bugzilla.mozilla.org/show_bug.cgi?id=1296187) - Don't overlap inspector-searchinput-clear with text.
        - Landed. Will create a follow up for it.
* Autofill
    - Surveyed the code to figure out the paths for form data saving and the timing to trigger autofill event.
    - [Bug 1288558](https://bugzilla.mozilla.org/show_bug.cgi?id=1288558) - Merge passwordManagerCommon.js into passwordManager.js
        - Landed, we'll address some small fixings in bug 1301248
