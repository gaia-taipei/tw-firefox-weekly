## This week 8/22 ~ 8/26
* Devtool:
    - [Bug 1261154](https://bugzilla.mozilla.org/show_bug.cgi?id=1261154) - Use "formatAbbreviatedBytes" utility from tree map in sidebar.
        - F+ after long discussion that we should apply decimal base prefixes in the CLDR.
    - [Bug 1295390](https://bugzilla.mozilla.org/show_bug.cgi?id=1295390) - Don't hold search result after clearing inspector-searchbox by inspector-searchinput-clear.
        - Landed
    - [Bug 1296187](https://bugzilla.mozilla.org/show_bug.cgi?id=1296187) - Don't overlap inspector-searchinput-clear with text.
        - Review canceled because of a small regression, need rebase since the layout refactored.
    - New box model view is somehow pended because it's not top priority yet. Devtool team prefer to finish 2 ongoning panels(console/debugger) first:
        - [new console issue 195](https://github.com/devtools-html/gecko-dev/issues/195) - Implement network event consle message.
            - Raised some questions and created a WIP for some early feedbacks.
* Autofill
    - Had a meeting with MattN and he will create some follow up bugs for autofill prerequisite.
    - Surveyed the code to figure out the paths for form data saving and the timing to trigger autofill event.
