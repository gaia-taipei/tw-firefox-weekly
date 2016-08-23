## This week 8/15 ~ 8/19
* Devtool:
    - [Bug 1253323](https://bugzilla.mozilla.org/show_bug.cgi?id=1253323) - Fix direction of heap-tree-number in RTL.
        - Landed
    - [Bug 1261154](https://bugzilla.mozilla.org/show_bug.cgi?id=1261154) - Use "formatAbbreviatedBytes" utility from tree map in sidebar.
        - Still arguing about the localization issue with binary/decimal size unit.
    - [Bug 1295390](https://bugzilla.mozilla.org/show_bug.cgi?id=1295390) - Don't hold search result after clearing inspector-searchbox by inspector-searchinput-clear.
        - R+, only some small nits and need rebase
    - [Bug 1253327](https://bugzilla.mozilla.org/show_bug.cgi?id=1253327) - Fix direction of children-pointer in RTL.
        - Landed
    - [Bug 1294464](https://bugzilla.mozilla.org/show_bug.cgi?id=1294464) - Don't overlap inspector-search and eyedropper, pane-toggle
        - Landed
    - [Bug 1296187](https://bugzilla.mozilla.org/show_bug.cgi?id=1296187) - Don't overlap inspector-searchinput-clear with text.
        - In review
    - After some quick study with all the accessible items, we decided to start from box model views with de-xul and componentization with React.
* Autofill
    - Had some discussion with Luke and read the latest UX spec.
