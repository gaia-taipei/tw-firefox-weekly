# [W30] 07/24 - 07/28

## Zerda

* Improve basic home screen UI
* Refactory MainActivity for fragment management logic
* Modify UrlInputFragment to match our requirement
* Impement basic Url bar UI for Zerda
* change status bar color in run-time

## Android Fennec

* Review patches for Photon

* [Bug 1379552](https://bugzilla.mozilla.org/show_bug.cgi?id=1379552) - Title URL should be faded out in tail 
    - Looing for root cause

* [Bug 1271998](https://bugzilla.mozilla.org/show_bug.cgi?id=1271998) - Proposal: Scrollable URL in URL bar
    - Working in progress

* [Bug 1325030](https://bugzilla.mozilla.org/show_bug.cgi?id=1325030) - Input field is covered by Soft-Keyboard
    - Looking for root cause, likely found another similar bug.

* [Bug 1314983](https://bugzilla.mozilla.org/show_bug.cgi?id=1314983) - Synced Devices folder is not displayed
    - Java implementation ready, Waiting for UX confirmation.

* [Bug 1324762](https://bugzilla.mozilla.org/show_bug.cgi?id=1324726) - A clickable list item in History looks disabled
    - Java implementation ready, Waiting for UX confirmation.

* [Bug 1310899](https://bugzilla.mozilla.org/show_bug.cgi?id=1310899) - To add close button to Video Player
    - Java implementation ready. Waiting for UX confirmation.

* [Bug 1318822](https://bugzilla.mozilla.org/show_bug.cgi?id=1318822) -  Search suggestions does not respect language setting
    - Found root cause, haven't find a proper way to fix it

* [Bug 1314835](https://bugzilla.mozilla.org/show_bug.cgi?id=1314835) - TelemetryJSONFilePingStore.lockAndReadJSONFromFile exception
    - Patch(to get more debug message) merged. Waiting for incoming crash report.

