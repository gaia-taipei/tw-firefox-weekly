## 09/07 ~ 09/11

2.5 Blocker
* Bug 1190980 - [Messages] Duration of the copy paste menu triggered from "To:" field is too short to access

Message team NGA status
* Bug 1201016 - [Messages][NG] Migrate the current Message manager event handling to NGA
* gaia fast list experiment

## 08/31 ~ 09/04

2.5 Blocker
* Bug 1190980 - [Messages] Duration of the copy paste menu triggered from "To:" field is too short to access
  * (Invastigating) Kept tracking the possible gecko regression and tried to remove the blocking flag since it shouldn't be a regression after gecko issues addressed.
* Bug 1198658 - MMS retrival unable to be rejected because of dataclone error
  * (Landed) Left the issue for bridge library for logn term solution.
* Low storage scenario feature
  * Get a more clear picture about the scope of 2.5, but still need UX to provide more details.

Message team NGA status

* Bug 1180592 - [Messages][NG] mozMobileConnections shim Implementation
  * In review since all the peers was in PTO.
* Bug 1201016 - [Messages][NG] Migrate the current Message manager event handling to NGA
  * Start with some discussion about the event handling migrating to NGA
* gaia fast list experiment - No progress, but the libraries have huge refactor. Need to figure out the new implementation.

## 08/24 ~ 08/28

2.5 Blocker

* Bug 1198658 - MMS retrival unable to be rejected because of dataclone error
  * (In review) Had some discussion with Bevis that we might not need the DOMError for API in the future. But still need a workaround from gaia side currently.
* Bug 1197104 - [Messages][Drafts] Threadless drafts are broken
  * (Landed)
* Bug 1160049 - [Messages] Attach menu should not dismiss when user cancel the replace attachment request
  * (Closed) After more discussion with UX, we decided to close as WFM because of design consistency  
 
Message team NGA status

* Bug 1180592 - [Messages][NG] mozMobileConnections shim Implementation
  * (Ongoing) More discussion about the layout for mozMobileConnections shim.
* gaia fast list experiment
  * Some more discussion about the lastest gaia-fast-list and profiling.

Threads.js

* Support DOMError instance in client/service method reject
  * Explain why we will need this issue.

## 08/17 ~ 08/21

Message team NGA status

* Bug 1184865 - [Messages][NG] Replace some methods in MessageManager with messaging service in conversation view
  * Landed.
* Bug 1167144 - [Messages] Reduce the use of Threads.active and Threads.currentId in conversation view
  * Landed
* Bug 1180592 - [Messages][NG] mozMobileConnections shim Implementation
  * Have a brief discussion about the mozMobileConnections shim.
* gaia fast list experiment
  * Gave another try with new fast-list implementation and the rendering works fine now. Need to figure out how the raptor profiling works in fast-list.

Threads.js

* Make it possible to remove timeout altogether
  * Landed by Wilson himself since he had another thought.

## 08/10 ~ 08/14

Message team NGA status

* Brief update about the NGA workweek in Paris(Library status):
  * Navigation API: Patch is ready and overall looks good in demo. Will be landed in 2.5
  * ServiceWrokerWare: Feature completed but has performance issue. Will not be in 2.5
  * threads.js: Ready for use but SharedWorker might also have performance concern. Will be in 2.5 but not for performance sensitive case like app cold launch.

* Bug 1184865 - [Messages][NG] Replace some methods in MessageManager with messaging service in conversation view
  * Rebase after message navigation refactoring. It need a small feature in threads.js(in review)
  
* Bug 1167144 - [Messages] Reduce the use of Threads.active and Threads.currentId in conversation view
  * Rebase after message navigation refactoring(in review)

* gaia fast list experimant
  * Etienne and Wilson wrote/utilized some tools(dom scheduler/gaia-component/gaia-fast-list) in order to improve list rendering performance. Tools are still in development and I tried to work with them to migrate fast list in message app. WIP(https://github.com/steveck-chung/gaia/tree/new-message-fast-list) created with some serious performance issue and reported to Etienne. 

* Other
  * Code review: message app navigation refactoring(landed)

Threads.js

* Make it possible to remove timeout altogether
  * Create a patch(https://github.com/gaia-components/threads/pull/75) to ignore the default timeout(in review)
