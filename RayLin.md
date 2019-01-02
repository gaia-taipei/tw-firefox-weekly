# 04/17 - 05/12

- [Video Control]
  - Bug 1352686 - Video doesn't play normally when I try to scroll the page
    - r-jaws
    - WIP, try to fix in DOM
  - Bug 1270983 - Intermittent browser_contextmenu.js | Test timed out | Found a tab after previous test timed out: subtst_contextmenu.html -
    - landed
  - Bug 1325591 - Videos are not displayed correctly with high contrast themes
    - re-landed, as media query in content process has been fixed
  - Bug 1346432 - Regression Firefox hides all video frames but still plays audio without a way to disable it (sometimes)
    - landed
  - Bug 1352724 - Seeking in video unexpectedly starts the playback, and video controls don't display current time
    - r?jaws
  - Bug 1359815 - Spinning loading UI is not used when resuming video element's video decoder takes longer than 250ms
    - landed, r=me
  - Bug 1362146 - html5 audio player controls not present
    - got feedback from Jared, will back to this once got free time

- [Form Autofill]
  - Bug 1329628 - Address phishing danger concerns about \[Form Autofill\]
    - on hold
  - Bug 1340483 - Add a chrome-only API to preview the text to be auto-filled in an \<input\>
    - landed
  - Bug 1340488 - Add a chrome-only API to preview the option to be auto-selected in a \<select\>
    - landed
  - Bug 1361244 - \[Form Autofill\] Add a new pseudo class for preview which highlight and change text color of form elements.
    - landed
  - Bug 1300996 - Show a preview of what would be filled when a form autofill autocomplete result is highlighted
    - WIP
    - part1, r+adw
    - part2, r?MattN


### Autofill Planning ###

- Q2
  - Dropdown menu
    - Notify add-on for preview
    - Phishing layout
  - Preview
    - Preview API for <input>
    - Preview API for <select>
    - Integration preview & highlight
