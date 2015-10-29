## This week 10/19 ~ 10/23
* 2.5 blocker
  - Bug 1192263 - [Messages] We load Inbox before going to the notification conversation when app is run via notification click.
    - (Feedback granted) We've decided to apply the solution even it might have an edge case that notification might not work while doing rapid removal and clicking on another notification(But it's harmless).  
  - Bug 1211395 - Performance regression in Message
    - (Landed) and created another follow up to see if we can make sure the load event happens earlier.
  - Bug 1217075 - [Messages] Both message and draft are preserved in the main app instance in case message is sent from another activity instance (until app is restarted)
    - (Reviewing) It's known issue in message app and we have some existing event handling mechanism to solve it properly.

## Last week 10/12 ~ 10/16
* 2.5 blocker
- Bug 1192263 - [Messages] We load Inbox before going to the notification conversation when app is run via notification click.
  - (Requesting feedback) Since reviewer might have some concern about the race condition while startup, gave 2 different approaches for more thoughts.
- Bug 1211395 - Performance regression in Message
  - (Reviewing) Applied several regression fixes and further improvement. The raptor number could reach 2.2 standard now expect one concern: It might delay the loaded event because we lazyload css styles right after DOMContentLoaded event. Bug 1211853 might fix that if we can control the splash screen dismiss. 

## 2015 Q4 Goals

1. 2.5: Complete low storage feature in message app.
2. 2.5: Blockers fixing(Message or other apps).
3. NGA in Message app: Complete client/service architecture and utilize navigation API for real split views.
4. NGA in Message app: Keep track of the serviceworker status and plan for serviceworker related NGA features.
5. Apply fast list module in message app when libraries are stabilized.

## 2015 Q3 delivered

1. NGA in Message app: Separate the original architecture into different views with independent markup/script/css/asset. Basically it's completed but we can still split more view in the future. Will be measured by progress made on Message app views splits.
2. NGA in Message app: Client/service architecture based on bridge library. We have implemented most of the back-end service layout and trying to connect/test with service methods gradually, still ongoing because of the performance issue and workaround is not trivial process. Will be measured by progress made on landing NGA Message app bits.
3. 2.5: blockers and other regression fixing, as measured by blocker burn down and days of blocker turnarounds.
4. 2.5: feature (low storage) discussion and preparation, as measured by feature burn down and days of blocker turnarounds.
5. Fast list(including Gaia component/dom scheduler module) experiment in message app(https://github.com/steveck-chung/gaia/tree/new-message-fast-list), as measured by outcome of the experiment and applicability to Gaia.
