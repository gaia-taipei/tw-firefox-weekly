10/27-10/31

**[Last week]**

* [Card UI]
  * [DONE] Bug 1076706 - [Stingray][Home] Implement card listing and launching function
    - landed on master
  * [WIP] Bug 1089464 - [Smart Screen][Home]Launch card directly from smart home
    - Follow up bug of 1076706. Almost done (got r+ with nits).
  * [REVIEW]
    - Bug 1092934 - [Stingray] Create settings app for changing landing app
  
* [Hardware Key Event]
  * [WIP] Bug 1014418 - Dispatching hardware button event in Gaia
    * got backed out because there is a plain iframe inside system app - Fx account login dialog. Add permission 'before-after-keyboard-event' in system could solve this problem. I'll send another review to timdream for relanding.
  * [QUEUED] Bug 1094066 - VolumeUp and VolumeDown key should handled by app first then fall back to system app
    * Follow up of bug 1014418
    * TODO: discuss solution with Gina
  * [QUEUED] Bug 1014405 - [Stingray] Keyboard event handling in Gaia
    * TODO: integrate hardware key event dispatching into Card UI architecture
   
**[This week]**
* [Card UI]
  * [WIP] Bug 1089464 - [Smart Screen][Home]Launch card directly from smart home
    - Follow up bug of 1076706. Almost done (got r+ with nits).
  * [QUEUED] Bug 1074079 - [Stingray] Apps deck view and operations
    * Bug 1094091 - [Stingray] Scaffolding Apps Deck of Stingray
    * Bug 1094094 - [Stingray] Implement Navigation of Apps Deck
  * [QUEUED] Bug 1076712 - [Stingray][Home] Implement "folder" 
  * [REVIEW]
    - Bug 1093436 - [Stingray][Home] move libraries to tv-shared folder

* [Hardware Key Event]
  * [WIP] Bug 1014418 - Dispatching hardware button event in Gaia
    * got backed out because there is a plain iframe inside system app - Fx account login dialog. Add permission 'before-after-keyboard-event' in system could solve this problem. I'll send another review to timdream for relanding.
  * [QUEUED] Bug 1094066 - VolumeUp and VolumeDown key should handled by app first then fall back to system app
    * Follow up of bug 1014418
    * TODO: discuss solution with Gina
  * [QUEUED] Bug 1014405 - [Stingray] Keyboard event handling in Gaia
    * TODO: integrate hardware key event dispatching into Card UI architecture
    * discuss schedule of this bug with Howie

