## This week 1/3 ~ 1/6
* Autofill
    - [Bug 1300989](https://bugzilla.mozilla.org/show_bug.cgi?id=1300989) - Fill the selected autofill profile when an autocomplete entry is chosen
        - feedback canceled since we decided not to create additional API and simply leverage the existing idl.
    - [Bug 1300992](https://bugzilla.mozilla.org/show_bug.cgi?id=1300992) -  Fill the autocomplete result with real profile by using profile storage API
        - r?. Gave a complete patch including the test for review.
* Devtool:
    - [Bug 1324334](https://bugzilla.mozilla.org/show_bug.cgi?id=1324334) - Migrate Chart.jsm to js and remove xul components in the chart
        - Landed. And filed another follow up bug 1328812 for migrating the html element into React conponent since it's not must have.
