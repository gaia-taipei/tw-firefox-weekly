## This week 12/21 ~ 12/25
* Bug 1221457 - [Messages]Apply gaia-fast-list for inbox list rendering
  - Still waiting for feedback

* Bug 1179628 - [Messages][NG] Lay out Settings service structure
  - Patch was ready and in review

* Reviewed some patches from contributors.

* Annual bug clean up and un-assign the pending features.

## Last week 12/14 ~ 12/18
* Bug 1221457 - [Messages]Apply gaia-fast-list for inbox list rendering
  - (feedback?)Still waiting for feedbacks from another peer.

* Bug 1224514 - [Messages][NG] We should shutdown MessagingService when app goes to background
  - Reviewed.

* Bug 1179628 - [Messages][NG] Lay out Settings service structure
  - (ongoing)Got some late feedback, resume the WIP and added unit tests.
  

## 2015 Q4 Goals

1. 2.5: Complete low storage feature in message app(Pending because it might move to 2.6 or later release).
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
