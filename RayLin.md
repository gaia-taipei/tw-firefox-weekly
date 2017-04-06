# 03/20 - 03/31

- [Video Control]
  - Bug 1347673 - "CC" button in video controls causes overflow (or is missing), when subtitles/text track is dynamically added
    - landed, uplifted to Beta
  - Bug 1350315 - Html5-video mouse does not hide when in fullscreen
    - landed, uplifted to Beta
  - Bug 1350191 - Video doesn't play normally when I change volume
    - landed, uplifted to Beta
  - Bug 1348954 - Html5-video controls do not hide when in fullscreen
    - landed, r=me
  - Bug 1346432 - Regression Firefox hides all video frames but still plays audio without a way to disable it (sometimes)
    - triaged: minor. spun off bug 1352995 for play button problem
  - Bug 1352879 - Seeking in video is interrupted by focus changes on the page
    - triaged: minor. asked :stone for idea
  - Bug 1352686 - Video doesn't play normally when I try to scroll the page
    - triaged: minor. the problem is more about DOM implementation details, seems not easy to drive this fix in front-end.



- [Form Autofill]
  - Bug 1340468 - Notify formautofill add-on of which item is being hovered in the suggestion dropdown
    - landed
  - Bug 1329628 - Address phishing danger concerns about [Form Autofill]
    - on hold
  - Bug 1348224 - Don't do \_adjustAcItem() if the type of item that about to attach is different from the previous item's type
    - landed
  - Bug 1350208 - Specify text color of selected profile item instead of inheriting from global autocomplete style
    - landed
  - Bug 1340483 - Add a chrome-only API to preview the text to be auto-filled in an <input>
    - r=:heycam


### Autofill Planning ###

- Q1 
  - Dropdown menu
    - New binding for Form Autofill
    - Two-columns styling

- Q2
  - Dropdown menu
    - Notify add-on for preview
    - Phishing layout
