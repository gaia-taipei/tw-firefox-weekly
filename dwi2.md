11/3-11/7

**[Last week]**
* [Card UI]
  * [DONE] Bug 1089464 - [Smart Screen][Home]Launch card directly from smart home
  * [DONE] Bug 1095219 - Failing unit test, smart-home-test/unit/card_manager_test.js | Uncaught Error: ReferenceError: evt is not defined
  * [WIP] Bug 1094091 - [Stingray] Scaffolding Apps Deck of Stingray
  * [QUEUE] Bug 1094094 - [Stingray] Implement Navigation of Apps Deck
  * [QUEUED] Bug 1076712 - [Stingray][Home] Implement "folder" 
  * [REVIEW]
    - Bug 1093436 - [Stingray][Home] move libraries to tv-shared folder
    - Bug 1092934 - [Stingray] Create settings app for changing landing app
    - Bug 1093529 - [Stingray] link home app to settings app
    - Bug 1093534 - [Stingray][Settings] add settings list to settings app

* [Hardware Key Event]
  * [DONE] Bug 1014418 - Dispatching hardware button event in Gaia
  * [QUEUED] Bug 1094066 - VolumeUp and VolumeDown key should handled by app first then fall back to system app
    * Follow up of bug 1014418
    * TODO: discuss solution with Gina
  * [QUEUED] Bug 1014405 - [Stingray] Keyboard event handling in Gaia
    * TODO: integrate hardware key event dispatching into Card UI architecture
    * discuss schedule of this bug with Howie
   
**[This week]**
* [Card UI]
  * [WIP] Bug 1094091 - [Stingray] Scaffolding Apps Deck of Stingray
    - under review
  * [WIP] Bug 1094094 - [Stingray] Implement Navigation of Apps Deck
    - WIP is at https://github.com/dwi2/gaia/tree/bug1094094_preview
  * [QUEUED] Bug 1076712 - [Stingray][Home] Implement "folder" 
  * [REVIEW]
    - Bug 1096737 - [Settings] All unit tests of settings app are not running
    - Bug 1098274 - [Stingray][Home] Add and remove card programitacally

* [Hardware Key Event]
  * Bug 1097814 - Sofware buttons are broken in mulet and simulator 
    - provide information for :ochameau
  * Bug 1096146 - No default actions of keydown event should be made if mozbrowserbeforekeydown event is defaultPrevented
    - Investigated, will be fixed at Gecko side
  * [QUEUED] Bug 1094066 - VolumeUp and VolumeDown key should handled by app first then fall back to system app
    * Follow up of bug 1014418
    * TODO: discuss solution with Gina
  * [QUEUED] Bug 1014405 - [Stingray] Keyboard event handling in Gaia
    * TODO: integrate hardware key event dispatching into Card UI architecture
    * discuss schedule of this bug with Howie



