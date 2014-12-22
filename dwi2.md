12/15-12/19

**[Last week]**
* [Card UI]
  * [WIP] Bug 1105976 - [Stingray][Home] Add Folder structure and its data access methods
    - r+, ready to land
  * [WIP] Bug 1111466 - [Stingray]Unpin card from context menu of app deck
    - working on it
  * [QUEUED] Bug 1076712 - [Stingray][Home] Implement "folder" 

* [Hardware Key Event]
  * [DONE] Bug 1106844 - [Stingray] prevent focus stays on disabled elements in order to receive keyboard event 
    - After Gina discussed with :smaug, they think it is a correct behavior at Gecko side. So I made a Gaia patch, to blur the focus when focus is on a disabled element.
    - r+ and landed.
  * [QUEUED] Bug 1113461 - Add tests of blurring focus when focus is on disabled button element in System app
    - follow-up of bug 1106844
   
**[This week]**
* [Card UI]
  * [WIP] Bug 1105976 - [Stingray][Home] Add Folder structure and its data access methods
    - r+, ready to land
  * [WIP] Bug 1111466 - [Stingray]Unpin card from context menu of app deck
    - working on it
  * [QUEUED] Bug 1114326 - [Stingray] Grid-view of app deck could not scroll down when app icons are out of screen
  * [QUEUED] Bug 1112986 - [Stingray][Home] Application and AppBookmark should be merged into one class
  * [QUEUED] Bug 1076712 - [Stingray][Home] Implement "folder"

* [Hardware Key Event]
  * [QUEUED] Bug 1113461 - Add tests of blurring focus when focus is on disabled button element in System app
    - follow-up of bug 1106844

