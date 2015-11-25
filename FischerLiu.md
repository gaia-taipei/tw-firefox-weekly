## 11/16 - 11/19 ##

### This Week ###
* [Fling Player]

  - [REVIEW] Bug 1222364 - [Stingray][fling-player][TV][2.5] UI polish, behaviour updates and skip error message
    The duplicated bugs related to this bug:
    - Bug 1222896 - [TV] The play/pause button should be highlighted after pressing any key to arouse progress bar
    - Bug 1223407 - [Stingray][fling-player][TV][2.5] Revise Fling app string base on copy review result
    - Bug 1226502 - [TV][Seamless Experience] The screen should not be moved
    - Bug 1222351 - Progress bar on TV should not disappear when cast video paused
    - Bug 1222353 - Screen should stay at initial screen and progress bar would not fade out when video ends

* [Send to TV App]

  - [WIP] Bug 1227812 - [TV] The new offline content for the FTE of Casting video and website to TV

* [App Usage Metric FTE]

  - [FIXED] Bug 1220588 - [TV] FTE for usage matrics
    Updates:
    - Focus on the terms section on load
    - Add one downward arrow icon to guide user scroll down the terms
    - Show the default scroll bar when scrolling the terms and no frame or outline effect when focusing on the terms
    - Hide the downward arrow icon when scrolling down to the end of the terms
    - Use Simple Navigation to resolve the navigation issue on the small screen

### Last Week ###

* [Marketplace FTE]

  - [FIXED] Bug 1223346 - [TV] FTE for Marketplace

    - Complete the visual, script controlling, l10n and file structure
      and give it to Joseph to integrate into the TV Marketplace App in the future.

* [Send to TV App]

  - [FIXED] Bug 1220584 - [TV] FTE for Casting video and website to TV

### Mozlando  Plan ###
1. Marketplace status & next steps / David Almstom, Lindsay Saunders
   - 15:00 ~ 17:00, 12/8: This session will talk about the Panasonic Marketplace implementation is as well as the next steps.

2. Performance & Stability Tool Demo / Kan Ru, Thinker
   - 13:15 ~ 14:15, 12/10: This seesion will demonstrate the task tracer and the DOM event record & replay tool to help identifing performance issue.

3. web component meetup / Fred Lin, Wilson Page
   - 09:00 ~ 10:00, 12/10: This seesion will talk about the gaia-components.

### 2015 Q4 Goal ###
1. Improve the fling player UI and User experience, as measured by the number of improvements (should be around 2~4), working time in 15%
2. Implement the tests for Fling Player, including 6 unit tests and 1 marrionete test, as measured by the completeness, working time in 15%
3. Implement the FTU parts, including Send-to-TV tutorial, App Usage FTU and Marketplace FTU, as measured by the completeness, working time in 30%
4. Implement the tests for the FTU parts, including 3 marrionete tests, as measured by the completeness, working time in 10%
5. Fix GijTV issues on Gaia-try and in-bound, as measured by the completeness, working time in 10%
6. Fix the issue - Preloaded hosted app offline support did not work, as measured by the completeness, working time in 10%
7. Fix other minor issues found before including update smart-button and update the dependency from smart-components to gaia-components, as measured by the completeness, working time in 10%
