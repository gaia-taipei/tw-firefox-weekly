## This week 12/27 ~ 12/30
* Autofill
    - [Bug 1300989](https://bugzilla.mozilla.org/show_bug.cgi?id=1300989) - Fill the selected autofill profile when an autocomplete entry is chosen
        - f?. Gave a patch about adding an API to query the guid for selected index.
    - [Bug 1300992](https://bugzilla.mozilla.org/show_bug.cgi?id=1300992) -  Fill the autocomplete result with real profile by using profile storage API
        - f?. Gave a patch about adding the cross process communication for qureying the profile.
* Devtool:
    - [Bug 1324334](https://bugzilla.mozilla.org/show_bug.cgi?id=1324334) - Migrate Chart.jsm to js and remove xul components in the chart
        - r-. Not progress. Still refactoring components to React component.
