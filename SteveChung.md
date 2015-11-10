## This week 11/2 ~ 11/6
* Bug 1221457 - [Messages]Apply gaia-fast-list for inbox list rendering
  - Resume the gaia fast list experiment since the libraries changed a lot. 
  
* Developer conference in Japan
  - Working on the slides for NGA introduction.

* Review the patch for optimizing the NGA related libraries.

## Last week 10/26 ~ 10/30
* 2.5 blocker
  - Bug 1215674 - If the user closes music and quickly locks the device, the music widget will still be present.
    - Landed. Applied a workaround that check the music app existence.

* Addon migration to marketplace
  - Got some reply from addon author and he merged the patch in his branch.  
  
* Developer conference in Japan
  - Provide the profile and abstract to Tomoya and Peyton. Start to prepare for the slides.

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
