# 01/23 - 02/10

- [Video Control]
  - Bug 1319584 - Remove right-border-radius
    - r-:jaws
  - Bug 1327097 - Video doesn't seek if page prevented mousedown event or mouseup event
    - drafting a RFE of platform feature: A "prevent" preventDefault event route for HTML anonymous content
  - Bug 1328060 - Total time is partially overlapped by mute button in some cases (video controls aren't responsive)
    - landed
  - Bug 1327238 - Ctrl+Click doesn't work in timeline in video controls and volume bar, unlike for other buttons
    - should go the same path as Bug 1327097
  - Bug 1329117 - The subtitle is displayed even if it's set to Off
    - landed by :bechen
    - aurora-approval+ and uplifted
    - beta-approval+ and uplifted
  - Bug 1332994 - The subtitle menu should highlight current enabled CC when video first loaded
    - landed
    - aurora-approval+ and uplifted
    - beta-approval+ but has conflicts while landing. need a rebased patch for beta repo
  - Bug 1333008 - Pressing the space key do nothing after clicking Play/Pause button from the media control panel
    - WIP, got feedback from :jaws
    - root cause: we could not disable focusability of HTML element by `-moz-user-focus: ignore`. ref=Bug 379939
  - Bug 1333062 - Play button breaks if I drag scrubber to the right twice
    - affected all revision of video controls, not regressed by video control refresh.
    - it's a precision problem of video length. only occurs when video length has more than three digits after decimal point. i.e. 30.093061 sec
    - will turn back to this issue if got more space in my queue
  - Bug 1319653 - Intermittent toolkit/content/tests/widgets/test_videocontrols_audio_direction.html
    - importing external CSS causing kind of race condition that makes video controls get incorrect client size in initial stage
    - asked :dholbert for help. Also, I've discussed with Astley and had a patch, but I prefer wait for :dholbert for he might have a better idea


- [Form Autofill]
  - Bug 1324631 - Support multiple column autocomplete popup rich list for form autofill feature
    - Bug 1326138 - add a new profile item \<binding\> and make rich-result-popup append item accordingly
      - r+:MattN
      - r=:adw
      - Vance has helpd to ask :adw to review via email
    - Bug 1326139 - Implement two column layout for profile item binding
      - r=MattN
    - Bug 1326141 - Make adjustHeight method adapt profile item list
      - DUPLICATE as height is already handled by CSS
    - Bug 1333682 - [Form Autofill] Prevent duplicate autocomplete search registration
      - landed, but has been asked for back out since we need to register in each frame not in each process


### Autofill Planning ###

- Q1 
  - Dropdown menu
    - New binding for Form Autofill
    - Two-columns styling
