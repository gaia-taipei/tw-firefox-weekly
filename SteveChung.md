## This week 8/29 ~ 9/2
* Devtool:
    - [Bug 1261154](https://bugzilla.mozilla.org/show_bug.cgi?id=1261154) - Use "formatAbbreviatedBytes" utility from tree map in sidebar.
        - No progress last week.
    - [Bug 1296187](https://bugzilla.mozilla.org/show_bug.cgi?id=1296187) - Don't overlap inspector-searchinput-clear with text.
        - In review. Got some positive feedback after proposing several methods since the stlye applied to both new HTML elements and original xul element might have some unexpected results.
    - New console panel:
        - [new console issue 195](https://github.com/devtools-html/gecko-dev/issues/195) - Implement network event consle message.
            - Land the first patch for showing part of network event message. Will work with Ricky to finish this item.
* Autofill
    - Surveyed the code to figure out the paths for form data saving and the timing to trigger autofill event.
    - [Bug 1288557](https://bugzilla.mozilla.org/show_bug.cgi?id=1288557) - Replace custom exceptions dialog (passwordManagerExceptions.xul) with usage of permissions.xul
        - Landed the issue as MattN suggested, and will work on the follow up [Bug 1288558](https://bugzilla.mozilla.org/show_bug.cgi?id=1288558)
