## This week 1/3 ~ 1/6
* Autofill
    - [Bug 1330567](https://bugzilla.mozilla.org/show_bug.cgi?id=1330567) - Fallback to form history if form autofill pref is disabled
        - f?. The timing for fallback mechanism might change that parent will be responsible for all the state changes and fire a state change event to child.
    - [Bug 1300992](https://bugzilla.mozilla.org/show_bug.cgi?id=1300992) -  Fill the autocomplete result with real profile by using profile storage API
        - r?. Patch updated and still in review.
* Devtool:
    - [Bug 1317646](https://bugzilla.mozilla.org/show_bug.cgi?id=1317646) - Netmonitor: move code for formatting request timings and content sizes to format-utils.js
        - Landed. Introduce a small refactoring for the const value and utils function.
