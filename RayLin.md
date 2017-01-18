# 01/09 - 01/13

- [Video Control]
  - Bug 1319584 - Remove right-border-radius
    - r?jaws
  - Bug 1328061 - Video controls break if I drag scrubber to the right twice
    - r?jaws
    - will consider adding :Gijs as secondary reviewer
  - Bug 1327097 - Video doesn't seek if page prevented mousedown event or mouseup event
    - redirected to :stone
    - deferred to Aurora
  - Bug 1328060 - Total time is partially overlapped by mute button in some cases (video controls aren't responsive)
    - WIP
    - discussed with :Gij and asked feedback from Peko.
    - will make the format of position label and duration label consistent, then no more twitch/resizing would happen while dragging timeline.
  - Bug 1325591 - Videos are not displayed correctly with high contrast themes
    - r?:mikedeboer
    - since this bug is flagged as regression, so simply fix the part regressed by visual refresh.
    - the HCM display issue should be fully fixed in another specific bug 1022553.


- [Form Autofill]
  - Bug 1324631 - Support multiple column autocomplete popup rich list for form autofill feature
    - Bug 1326138 - add a new profile item \<binding\> and make rich-result-popup append item accordingly
      - r?MattN
      - got a first version patch that addresses the binding resuing issue, will dicuss with :MattN in regurlar meeting
    - Bug 1326139 - Implement two column layout for profile item binding
      - WIP
    - Bug 1326141 - Make adjustHeight method adapt profile item list


### Autofill Planning ###

- Q1 
  - Support multiple column
