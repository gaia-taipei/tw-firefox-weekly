## This week 1/11 ~ 1/15
* Investigate more intermittent failed issues
  - Bug 1235842 - new activity test intermittent failed: Remove aria-hidden: true property if we need to test the element.
  - Bug 1236418 - Postpone the investigation due to the low rate and unrelated error message

* Revisit some serious copy/paste issues:
  - Bug 1127587 - Revisit select all broken case within master. There might be some regression about user-select inheritance.
  
* Medical Platform Project discussion:
  - Notes: https://docs.google.com/document/d/1TQRfJYBNp8qO8oLx5gsah2Fy4dlapBXWXur2KzxXa84/edit

## This week 1/4 ~ 1/8
* Bug 1221457 - [Messages]Apply gaia-fast-list for inbox list rendering
  - Moved to low priority background work.

* Bug 1179628 - [Messages][NG] Lay out Settings service structure
  - Moved to low priority background work.

* Investigate more intermittent failed issues(Bug 1235842, Bug 1236418) with docker and MozITP tool.
 - Bug 1235842 - new activity test intermittent failed: Found some regression in a11y test framework changes.
 - Bug 1236418 - attachment test intermittent failed: Can't find the root cause because of extremely low reproduce rate.

## 2016 Q1 Goals

* Goals updated on Workday


## 2015 Q4 delivered

1. 2.5: Complete low storage feature in message app, pending because it moved to 2.6 or later release.
2. 2.5: Blockers fixing(Message or other apps), as measured by blocker burn down and days of blocker turnarounds.
3. NGA in Message app: Complete client/service architecture and utilize navigation API for real split views, as measured by progress made on landing NGA Message app.
4. NGA in Message app: Keep track of the serviceworker status and plan for serviceworker related NGA features, as measured by task break down for serviceworker related features or any other experiment for it.
5. Apply fast list module in message app when libraries are stabilized, as measured by the progress of the experimental WIP.  
