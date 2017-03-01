# 02/20 - 02/24

- [Video Control]
  - Bug 1319653 - Intermittent toolkit/content/tests/widgets/test_videocontrols_audio_direction.html
    - wait and see if Bug 1339269 has fixed this intermittent
  - Bug 1339269 - Video/Audio controls don't layout correctly, if size is initially 0
    - r+jaws
    - landed and aurora-approval?
  - For invalid visual refresh bugs:
    - clarify the diff between current implementation and spec.
    - will ask Peko to update spec


- [Form Autofill]
  - Bug 1324631 - Support multiple column autocomplete popup rich list for form autofill feature
    - Bug 1326139 - Implement two column layout for profile item binding
      - r+MattN, landed
    - Bug 1326141 - Make adjustHeight method adapt profile item list
      - reopened as "collapse" property of XUL doesn't affect for HTML
      - r+MattN, landed
    - Bug 1340468 - Notify formautofill add-on of which item is being hovered in the suggestion dropdown
      - WIP
    - Bug 1341019 - 'item' is not defined in autocomplete-richlistitem#_onChanged after bug 1326138
      - r+standard8, landed
    - Bug 1329628 - Address phishing danger concerns about [Form Autofill]
      - UX has a proposal for phishing problem, which adds extra information at the bottom of dropdown menu
      - try to implement new layout with some hacks, but could not meet the requirement for some technical issue
      - need further discussion with MattN


### Autofill Planning ###

- Q1 
  - Dropdown menu
    - New binding for Form Autofill
    - Two-columns styling

- Q2
  - Dropdown menu
    - Notify add-on for preview
    - Phishing layout
