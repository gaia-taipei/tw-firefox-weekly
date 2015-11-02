## This week 10/26 ~ 10/30
* 2.5 blocker
  - Bug 1215674 - If the user closes music and quickly locks the device, the music widget will still be present.
    - (Reviewing) It's known issue since there's some race condition between music IAC and app terminated event. Created a workaround that check the music app existence before applying the playback status.

* Addon migration to marketplace
  - Help to migrate some addons in hackerplace to marketplace. Stuck in requesting permission and waiting for Andrew's reply.  
  
* Developer conference in Japan
  - Have some discussion with Tomoya and Peyton about the speech topic and abstract. 

## Last week 10/19 ~ 10/23
* 2.5 blocker
  - Bug 1192263 - [Messages] We load Inbox before going to the notification conversation when app is run via notification click.
    - Landed.
  - Bug 1217075 - [Messages] Both message and draft are preserved in the main app instance in case message is sent from another activity instance (until app is restarted)
    - Landed.
  - Reviewing other messages patches.

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
