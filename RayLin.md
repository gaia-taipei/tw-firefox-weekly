# 01/16 - 01/20

- [Video Control]
  - Bug 1319584 - Remove right-border-radius
    - r?jaws
  - Bug 1328061 - Video controls break if I drag scrubber to the right twice
    - landed
  - Bug 1327097 - Video doesn't seek if page prevented mousedown event or mouseup event
    - :stone opened an issue for discussion on whatwg repo: https://github.com/whatwg/html/issues/2258
  - Bug 1328060 - Total time is partially overlapped by mute button in some cases (video controls aren't responsive)
    - r?jaws
  - Bug 1325591 - Videos are not displayed correctly with high contrast themes
    - landed
  - Bug 1327238 - Ctrl+Click doesn't work in timeline in video controls and volume bar, unlike for other buttons
    - ni :stone, asked him is this behavior a documented standard for input or not.
    - tested with CodePen, it looks like the input refrain from triggering `input` or `change` events, when Ctrl+Click
  - Bug 1329117 - The subtitle is displayed even if it's set to Off
    - redirected to :bechen, as TextTrackManager send event prior to setting track's mode.


- [Form Autofill]
  - Bug 1324631 - Support multiple column autocomplete popup rich list for form autofill feature
    - Bug 1326138 - add a new profile item \<binding\> and make rich-result-popup append item accordingly
      - WIP
      - seperate the code from existing autocomplete to formautofill its own folder, and have stylesheets loaded in bootstrap process.
    - Bug 1326139 - Implement two column layout for profile item binding
      - WIP
    - Bug 1326141 - Make adjustHeight method adapt profile item list


### Autofill Planning ###

- Q1 
  - Dropdown menu
    - New binding for Form Autofill
    - Two-columns styling
