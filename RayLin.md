# 01/03 - 01/06

- [Video Control]
  - Bug 1319584 - Remove right-border-radius
    - r?jaws
  - Bug 1328061 - Video controls break if I drag scrubber to the right twice
    - WIP, caused by incorrect dragging state management.
  - Bug 1327289 - Spacebar/Up/Down in video controls does 2 actions simultaneously
    - duplicate
  - Bug 1327097 - Video doesn't seek if page prevented mousedown event or mouseup event
    - redirected to :stone
  - Bug 1325594 - Pressing the space key do nothing when the focus is on the Play/Pause button
    - landed
    - filed another bug for CC button and fullscreen button keyboard-accessibility


- [Form Autofill]
  - Bug 1324631 - Support multiple column autocomplete popup rich list for form autofill feature
    - Bug 1326138 - add a new profile item \<binding\> and make rich-result-popup append item accordingly
      - f?MattN
      - tested two different implementations and came up with some more solid thoughts about the direction
      - will discuss with :MattN in next regular meeting, and confirm which to go
    - Bug 1326139 - Implement two column layout for profile item binding
      - WIP
    - Bug 1326141 - Make adjustHeight method adapt profile item list


### Autofill Planning ###

- Q1 
  - Support multiple column
