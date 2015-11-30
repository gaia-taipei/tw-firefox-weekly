## This week 11/9 ~ 11/13
* Bug 1221457 - [Messages]Apply gaia-fast-list for inbox list rendering
  - Continuing the work for first runnable version.

* Developer conference in Japan
  - Slides polishing and rehearsal.

* Bug 1224045 - Pasting something ther than text into a message can prevent SMS from accepting input fro the keyboard
  - Should be fixed in 2.5 because rich text copy/paste would be disabled on 2.5. Pinging Boris for more information.

* Bug 1223280 - Migrate network-alerts to use NotificationHelper api
  - Reviewing the patch about utilizing NotificationHelper.

* Review the patch about NGA module splitting.

## Last week 11/2 ~ 11/6
* Bug 1221457 - [Messages]Apply gaia-fast-list for inbox list rendering
  - Rebased on master with latest fast-list module. working on the first runnable version on device.

* Developer conference in Japan
  - Working on the slides for NGA introduction and polishing.

* NGA related libraries optimization landed. Reviewing the idea about the further service/client module splitting.

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
