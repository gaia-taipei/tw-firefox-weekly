# 03/13 - 03/17

- [Video Control]
  - Bug 1319653 - Intermittent toolkit/content/tests/widgets/test_videocontrols_audio_direction.html
    - RESOLVED FIXED
  - Bug 1347673 - "CC" button in video controls causes overflow (or is missing), when subtitles/text track is dynamically added
    - r+jaws
    - reftest in e10s is broken, checking out why


- [Form Autofill]
  - Bug 1340468 - Notify formautofill add-on of which item is being hovered in the suggestion dropdown
    - r?MattN
  - Bug 1329628 - Address phishing danger concerns about [Form Autofill]
    - WIP patch attached
  - Bug 1325538 - Add mochitest for form autofill feature
    - cribbed helper funtions from satchel, and discussed with Steve about how to setup the storage before testing
  - Bug 1348224 - Don't do \_adjustAcItem() if the type of item that about to attach is different from the previous item's type
    - r?adw
  - Bug 1340483 - Add a chrome-only API to preview the text to be auto-filled in an <input>
    - WIP, have made a workable patch
    - refactoring and breaking down the patch into several parts (make it easier to review)


### Autofill Planning ###

- Q1 
  - Dropdown menu
    - New binding for Form Autofill
    - Two-columns styling

- Q2
  - Dropdown menu
    - Notify add-on for preview
    - Phishing layout
