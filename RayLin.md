# 02/13 - 02/17

- [Video Control]
  - Bug 1328060 - Total time is partially overlapped by mute button in some cases (video controls aren't responsive)
    - aurora-approval+ and uplifted
  - Bug 1328062 - Video controls twitch when I click near the end of long videos
    - VERIFIED FIXED, fixed in bug 1328060
  - Bug 1332994 - The subtitle menu should highlight current enabled CC when video first loaded
    - beta-approval+ and uplifted
  - Bug 1333008 - Pressing the space key do nothing after clicking Play/Pause button from the media control panel
    - r+jaws
    - aurora-approval+ and uplifted
  - Bug 1319653 - Intermittent toolkit/content/tests/widgets/test_videocontrols_audio_direction.html
    - :dholbert spun off another bug 1339269
  - Bug 1339269 - Video/Audio controls don't layout correctly, if size is initially 0
    - r=jaws
  - Bug 1340523 - “Video format or MIME type is not supported.” text area is not 350x18px
    - INVALID
  - Bug 1340479 - Media control panel elements don't meet the distances given in the specifications document
    - INVALID
  - Bug 1340460 - The central play icon size is 72x72px instead of 75x75px
    - INVALID
  - For these invalid bugs:
    - New QC from SoftVision using inaccurate way to measure dimensions
    - Some spec need to be updated after continuing discussion and implementation


- [Form Autofill]
  - Bug 1324631 - Support multiple column autocomplete popup rich list for form autofill feature
    - Bug 1326138 - add a new profile item \<binding\> and make rich-result-popup append item accordingly
      - landed
    - Bug 1326139 - Implement two column layout for profile item binding
      - r=MattN
    - Bug 1326141 - Make adjustHeight method adapt profile item list
      - DUPLICATE as height is already handled by CSS


### Autofill Planning ###

- Q1 
  - Dropdown menu
    - New binding for Form Autofill
    - Two-columns styling
