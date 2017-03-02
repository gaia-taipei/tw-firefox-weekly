
## [W07] Rex 2/20 - 2/24 ##

### This week ###
** content handling **
Content handling
- Bug 1338984 - The "attention" state of the Downloads Indicator does not have enough contrast for the "arrow" style progress
  - Got r+.
- Bug 1270006 - Replace the downloads remaining time on the downloads button with a downloading icon
  - Got r+. Pushed into inbound.
- Bug 1270012 - Visual for download animation on download start whenever a download is started
  - Since bug 1270006 has been done, rebasing and erasing conflict to chceking-in.
  
** mortar **
- Bug 1338094 - [Mortar] Support hotkey for copy selected text in PDF viewer.
  - got r+ and landed.
- Bug 1338095 -	[Mortar] Implement "View bookmark" button in PDF viewer.
  - got first feedback. Refining the patch for things like sanitinizing process of input texts.
  

### Last weeks ###
** content handling **
Content handling
- Bug 1338984 - The "attention" state of the Downloads Indicator does not have enough contrast for the "arrow" style progress
  - got r+ with some modification needed.
- Bug 1270006 - Replace the downloads remaining time on the downloads button with a downloading icon
  - got r+. 

** mortar **
- Bug 1338092 - [Mortar] Remove de-scoped user features on PDF viewer UI.
  - Got r+ and landed.
- Bug 1338094 - [Mortar] Support hotkey for copy selected text in PDF viewer.
  - Got r+ and landed.
- Bug 1338095 -	[Mortar] Implement "View bookmark" button in PDF viewer.
  - Studying codebase of Mortar required for achieving the asked feature.
  - Inspecting corresponding behavior of PDF.js.
