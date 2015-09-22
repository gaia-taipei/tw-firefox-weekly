## This week 9/30 ~ 10/2
* 2.5 blocker
  - Bug 1206678 - Outgoing MMS contains subject that was typed by user, but then hidden
* 2.5 feature
  - Bug 1207094 - [Messages] Disable appropriate controls when in low storage condition
* NGA
  - Bug 1179628 - [Messages][NG] Lay out Settings service structure
  - Bug 1201016 - [Messages][NG] Migrate the current Message manager event handling to NGA

## Last week 9/21 ~ 9/25
* 2.5 blocker 
  - Bug 1203886 - The back button in sms conversation view does not always work
    * Landed
* 2.5 feature
  - Bug 1207094 - [Messages] Disable appropriate controls when in low storage condition
    * Ongoing, we might need event handling ability in NGA related Bug 1201016 if we want to implement the storage as a service.
* NGA
  - Bug 1179628 - [Messages][NG] Lay out Settings service structure
    * Patch created for early feedback. Waiting for feedback about the settings client layout.
  - Bug 1201016 - [Messages][NG] Migrate the current Message manager event handling to NGA
    * Patch created for early feedback.

## 2015 Q4 Goals

1. 2.5: Complete low storage feature in message app.
2. 2.5: Blockers fixing(Message or other apps).
3. NGA in Message app: Complete client/service architecture and utilize navigation API for real split views.
4. NGA in Message app: Keep track of the serviceworker status and plan for serviceworker related NGA features.
5. Apply fast list module in message app when libraries are stabilized.

## 2015 Q3 delivered

1. NGA in Message app: Separate the original architecture into different views with independent markup/script/css/asset. Basically it's completed but we can still split more view in the future.
2. NGA in Message app: Client/service architecture based on bridge library. We have implemented most of the back-end service layout and trying to connect/test with service methods gradually, still ongoing because of the performance issue and workaround is not trivial process. 
3. 2.5: blockers and other regression fixing.
4. 2.5: feature (low storage) discussion and preparation.
5. Fast list(including Gaia component/dom scheduler module) experiment in message app(https://github.com/steveck-chung/gaia/tree/new-message-fast-list).
