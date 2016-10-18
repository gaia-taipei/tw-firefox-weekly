## This week 10/11 ~ 10/14
* Devtool:
    - [Bug 1308697](https://bugzilla.mozilla.org/show_bug.cgi?id=1308697) - Implement UI for performance statistics
        - Discuss with Honza about the possible way to start the refactoring for performance statistic view. Will start bug 1308425 first.
* Autofill
    - [Bug 1300988](https://bugzilla.mozilla.org/show_bug.cgi?id=1300988) - Implement an API in the content process to fill a form with a specific form autofill profile using @autocomplete
        - R+ with some small nits that need to be addressed.
    - [Bug 1300989](https://bugzilla.mozilla.org/show_bug.cgi?id=1300989) - Fill the selected autofill profile when an autocomplete entry is chosen
        - Investigate the proper way to connect with the autofill drop down menu and call the API created in Bug 1300988.
