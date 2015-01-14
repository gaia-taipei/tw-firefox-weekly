1/5-1/9

**[Last week]**
* [Card UI]
  * [DONE] Bug 1114326 - [Stingray] Grid-view of app deck could not scroll down when app icons are out of screen
    - landed on master
  * [DONE] Bug 1115295 - [Stingray][AppDeck/Home] Empty folders are not removed correctly in cardManager
    - landed on master
  * [DONE] Bug 1118143 - [Stingray][AppDeck] Newly installed app should display in AppDeck automatically
    - landed on master
  * [QUEUED] Bug 1115633 - [Stingray] Behavior after unpin app in App-Deck is inconsistent with other deck
  * [QUEUED] Bug 1111471 - [Stingray][Home] Newly pinned card should be located right after its parent card
  * [QUEUED] Bug 1118584 - [Stingray][Home] After pinning an app to home, the latest pined app should get the focus
  * [QUEUED] Bug 1112986 - [Stingray][Home] Application and AppBookmark should be merged into one class
  * [REVIEW]
    - Bug 1115273 - [Stingray][smart-home/smart-system] Implement opening search bar
    - Bug 1113499 - [Stingray][Smart-home] Open app with specified hash/URL
    - Bug 1105986 - [Stingray][Home] Delete card

* [Hardware Key Event]
  * [DISCUSSION] Bug 1116762 - Home button not working anymore 
    - regression caused by other gecko patch
    - discuss with Gina and Masayuki, we are going to compare KeyboardEvent.key with constant value instead of literal string. This needs both Gecko and Gaia work. Sean Lin has finish the Gecko part.
  * [DONE] Bug 1119673 - KeyboardEvent.key of Home key will be changed to 'MozHomeScreen'
    - follow up of bug 1116762
    - landed on master
  * [QUEUED] Bug 1113461 - Add tests of blurring focus when focus is on disabled button element in System app
    - follow-up of bug 1106844
   
**[This week]**
* [Card UI]
  * [WIP] Bug 1115633 - [Stingray] Behavior after unpin app in App-Deck is inconsistent with other deck
  * [QUEUED] Bug 1111471 - [Stingray][Home] Newly pinned card should be located right after its parent card
   [QUEUED] Bug 1118584 - [Stingray][Home] After pinning an app to home, the latest pined app should get the focus
  * [QUEUED] Bug 1112986 - [Stingray][Home] Application and AppBookmark should be merged into one class

* [Hardware Key Event]
  * [QUEUED] Bug 1113461 - Add tests of blurring focus when focus is on disabled button element in System app
    - follow-up of bug 1106844
