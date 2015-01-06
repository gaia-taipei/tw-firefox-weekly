12/29-12/31

**[Last week]**
* [Card UI]
  * [DONE] Bug 1111466 - [Stingray]Unpin card from context menu of app deck
    - landed on master
  * [WIP] Bug 1114326 - [Stingray] Grid-view of app deck could not scroll down when app icons are out of screen
    - under review
  * [WIP] Bug 1115295 - [Stingray][AppDeck/Home] Empty folders are not removed correctly in cardManager
    - under review
  * [QUEUED] Bug 1112986 - [Stingray][Home] Application and AppBookmark should be merged into one class
  * [REVIEW]
    - Bug 1105982 - [Stingray][Home] Apply "new folder" as well as "empty folder" behavior and visual

* [Hardware Key Event]
  * [WIP] Bug 1116762 - Home button not working anymore 
    - regression caused by other gecko patch
    - discuss with Gina and Masayuki, we are going to compare KeyboardEvent.key with constant value instead of literal string. This needs both Gecko and Gaia work. Sean Lin will work the Gecko part.
  * [QUEUED] Bug 1113461 - Add tests of blurring focus when focus is on disabled button element in System app
    - follow-up of bug 1106844
   
**[This week]**
* [Card UI]
  * [WIP] Bug 1114326 - [Stingray] Grid-view of app deck could not scroll down when app icons are out of screen
    - under review
  * [WIP] Bug 1115295 - [Stingray][AppDeck/Home] Empty folders are not removed correctly in cardManager
    - under review
  * [QUEUED] Bug 1115273 - [Stingray][smart-home/smart-system] Implement opening search bar
  * [QUEUED] Bug 1112986 - [Stingray][Home] Application and AppBookmark should be merged into one class

* [Hardware Key Event]
  * [WIP] Bug 1116762 - Home button not working anymore 
    - regression caused by other gecko patch
    - discuss with Gina and Masayuki, we are going to compare KeyboardEvent.key with constant value instead of literal string. This needs both Gecko and Gaia work. Sean Lin will work the Gecko part.
  * [QUEUED] Bug 1113461 - Add tests of blurring focus when focus is on disabled button element in System app
    - follow-up of bug 1106844