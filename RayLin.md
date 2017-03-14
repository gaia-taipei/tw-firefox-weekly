# 02/27 - 03/10

- [Video Control]
  - Bug 1319653 - Intermittent toolkit/content/tests/widgets/test_videocontrols_audio_direction.html
    - 7 day MA from Orange Factory's report is now nearly down to 0
  - Bug 1339269 - Video/Audio controls don't layout correctly, if size is initially 0
    - aurora-approval+ and uplifted to 53
  - For invalid visual refresh bugs:
    - spec updated to align with current implementation, no new regression was filed by SV so far


- [Form Autofill]
  - Bug 1340468 - Notify formautofill add-on of which item is being hovered in the suggestion dropdown
    - review cancelled
    - r?MattN again
  - Bug 1329628 - Address phishing danger concerns about [Form Autofill]
    - update spec info
    - a workable WIP patch attached
  - Bug 1344630 - Display parsed value in the corresponding column instead of showing JSON string
    - r+seanlee and landed
  - Bug 1325538 - Add mochitest for form autofill feature
    - look into Steve's patch and try to carry on the bug with it.


### Autofill Planning ###

- Q1 
  - Dropdown menu
    - New binding for Form Autofill
    - Two-columns styling

- Q2
  - Dropdown menu
    - Notify add-on for preview
    - Phishing layout
