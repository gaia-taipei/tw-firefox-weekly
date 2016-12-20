## This week 12/5 ~ 12/16
* Hawaii all hands:
    - Autofill:
        - Confirmed the prototype in [bug 1304634](https://bugzilla.mozilla.org/show_bug.cgi?id=1304634) and the timing for markAsFormfill/heuristic API. Created another [bug 1322622](https://bugzilla.mozilla.org/show_bug.cgi?id=1322622) to address the missing frame script issue and unblock other bugs.
    - Devtool:
        - Attended the meetup to understand the goal of 2017 Q1 and further plans such as moving codebase to github and shipping devtool as an independent NPM package after de-xul/de-chrome.

* Autofill
    - [Bug 1322622](https://bugzilla.mozilla.org/show_bug.cgi?id=1322622) - Make form autofill handler a frame script and load from bootstrap.js.
        - Landed. MattN wanted to addressed resource location issue with other minor fixings at the same time, so he took over the bug and the patch was reviewed by me.
    - [Bug 1304634](https://bugzilla.mozilla.org/show_bug.cgi?id=1304634) - Support populating autocomplete results from form autofill code
        - r? Patch rebased after Bug 1322622 landed and factory binding works after moving the search out of chrome process.

* Devtool:
    - [Bug 1308697](https://bugzilla.mozilla.org/show_bug.cgi?id=1308697) - Implement UI for performance statistics
        - Landed.
    - [Bug 1324334](https://bugzilla.mozilla.org/show_bug.cgi?id=1324334) - Migrate Chart.jsm to js and remove xul components in the chart
        - Will give a quick patch to move the JSM into simple object and replace xul with html element.
