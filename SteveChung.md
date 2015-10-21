## This week 10/12 ~ 10/16
* 2.5 blocker
  - Bug 1192263 - [Messages] We load Inbox before going to the notification conversation when app is run via notification click.
  - Bug 1211395 - Performance regression in Message
    - Message team will profile between 2 version and try out any possible way to shave more usage of memory and the cold launch time before FC.

## Last week 10/5 ~ 10/9
* 2.5 blocker
  - (Landed)Bug 1206678 - Outgoing MMS contains subject that was typed by user, but then hidden
* 2.5 feature
  - (Pending)Bug 1207094 - [Messages] Disable appropriate controls when in low storage condition
    - Patch got some feedback but the spec is still not clear enough, and low storage feature is suspended because of the lack of resource for QA testing. 
* NGA
  - (Pending)Bug 1179628 - [Messages][NG] Lay out Settings service structure
  - (Pending)Bug 1201016 - [Messages][NG] Migrate the current Message manager event handling to NGA
    - All the NGA features reviewing are pending.

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
