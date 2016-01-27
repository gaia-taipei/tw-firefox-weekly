## 12/21 - 12/31 ##

### This Week ###

* [GijTV]

  - [REVIEW] Bug 1235300 - [GijTV] Smart system has to set the ready-state attribute to let JSMarionette know ready to test
     - Modify smart-system bootstrap.js to set the ready-state attribute according to the JSMarionette rule
     - Modify smart-system core.js to use Promise API when starting
     - Modify smart-system marionette tests based on other phone Gij test examples

  - Bug 1236723 - [gatt] GijTV chunks not working
    - Bug identifying and test verification

* [FTU]

  - [REVIEW] Bug 1237181 - [TV][2.5][Marketplace] Revise l10n string for Tutorial
  - [REVIEW] Bug 1237507 - [TV][2.5][Marketplace][FTE] The default highlight will be at Next button or Done button
  - [WIP] Bug 1232584 - [TV] FTE for usage metrics specs update for the new legal approved terms

* [Other]

  - [REVIEW] Bug 1236808 - [TV][2.5] Remove remote control apps from both engineering and production building lists on TV 2.5 branch

### Last Week ###

* [GijTV]

  - [WIP] Bug 1235300 - [GijTV] Smart system has to set the ready-state attribute to let JSMarionette know ready to test
  - [WIP] Bug 1234482 - [GijTV] Re-enable smart-system app_modal_dialog test
  - [WIP] Bug 1234484 - [GijTV] Re-enable smart-system app_install_dialog and browser_context_menu test
    - Duplicate bug: Bug 1231460 - [GijTV] Smart-system browser context menu marionette test failure

### 2015 Q4 Goal ###
1. Improve the fling player UI and User experience, as measured by the number of improvements (should be around 2~4), working time in 15%
2. Implement the tests for Fling Player, including 6 unit tests and 1 marrionete test, as measured by the completeness, working time in 15%
3. Implement the FTU parts, including Send-to-TV tutorial, App Usage FTU and Marketplace FTU, as measured by the completeness, working time in 30%
4. Implement the tests for the FTU parts, including 3 marrionete tests, as measured by the completeness, working time in 10%
5. Fix GijTV issues on Gaia-try and in-bound, as measured by the completeness, working time in 10%
6. Fix the issue - Preloaded hosted app offline support did not work, as measured by the completeness, working time in 10%
7. Fix other minor issues found before including update smart-button and update the dependency from smart-components to gaia-components, as measured by the completeness, working time in 10%