# 04/04 - 04/14

- [Video Control]
  - Bug 1346432 - Regression Firefox hides all video frames but still plays audio without a way to disable it (sometimes)
    - landed
  - Bug 1352879 - Seeking in video is interrupted by focus changes on the page
    - flagged as WONTFIX since all <input type="range"> behave the same for long
  - Bug 1352686 - Video doesn't play normally when I try to scroll the page
    - review cancelled by Gijs. We're still seeking for other better approaches
    - minor issue, but will carry on this if get free time
  - Bug 1270983 - Intermittent browser_contextmenu.js | Test timed out | Found a tab after previous test timed out: subtst_contextmenu.html -
    - ni?jaws

- [Form Autofill]
  - Bug 1329628 - Address phishing danger concerns about [Form Autofill]
    - on hold
  - Bug 1340483 - Add a chrome-only API to preview the text to be auto-filled in an <input>
    - r+heycam
    - r?baku, need a separate DOM peer to review .webidl


### Autofill Planning ###

- Q2
  - Dropdown menu
    - Notify add-on for preview
    - Phishing layout
  - Highlight
    - Preview API for <input>
    - Preview API for <select>
