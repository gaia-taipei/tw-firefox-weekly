
## [W06] Rex 2/13 - 2/17 ##

### This week ###
** content handling **
Content handling
- Bug 1338984 - The "attention" state of the Downloads Indicator does not have enough contrast for the "arrow" style progress
  - The requirement looks not very reasonable to me. Under discuss with reviewer and visual.
  - Reviewer think it blocks bug 1270006 but it seems to be independent issues to me. Still need discussing.
- Bug 1270006 - Replace the downloads remaining time on the downloads button with a downloading icon
  - Got 7th and 8th reviews finished, still need working.

** mortar **
- Bug 1338092 - [Mortar] Remove de-scoped user features on PDF viewer UI.
  - Got r+ and landed.
- Bug 1338094 - [Mortar] Support hotkey for copy selected text in PDF viewer.
  - 1st review ended. Further studying to prevent regression.
- Bug 1338095 -	[Mortar] Implement "View bookmark" button in PDF viewer.
  - Studying codebase of Mortar required for achieving the asked feature.
  - Inspecting corresponding behavior of PDF.js.
  

### Last weeks ###
** mortar **
- Bug 1330932	- [Mortar] Support password-locked PDF file
  - landed.
  
** content handling **
- Bug 1270012 - Visual for download animation on download start whenever a download is started
  - got r+. (May need to land with bug 1270006, under discussion)
- Bug 1270006 - Replace the downloads remaining time on the downloads button with a downloading icon
  - got f+ and still working.
- Bug 1325574 - Make main area of download item slightly highlighted on mouseover
  - landed.
