## This week 10/17 ~ 10/21
* Devtool:
    - [Bug 1308425](https://bugzilla.mozilla.org/show_bug.cgi?id=1308425) - Move Performance Statistics into its own module
        - F+ and need to rebase after Ricky's patch landed.
* Autofill
    - [Bug 1300988](https://bugzilla.mozilla.org/show_bug.cgi?id=1300988) - Implement an API in the content process to fill a form with a specific form autofill profile using @autocomplete
        - Landed.
    - [Bug 1300989](https://bugzilla.mozilla.org/show_bug.cgi?id=1300989) - Fill the selected autofill profile when an autocomplete entry is chosen
        - Left some note since it will still need landing Bug 1304634 first to confirm the solution.
    - [Bug 1300989](https://bugzilla.mozilla.org/show_bug.cgi?id=1300989) - Fill the selected autofill profile when an autocomplete entry is chosen
        - Will start the profile list dialog in preference.
