## 08/24 ~ 08/28

2.5 Blocker

*  Bug 1198658 - MMS retrival unable to be rejected because of dataclone error
*  Bug 1197104 - [Messages][Drafts] Threadless drafts are broken

Message team NGA status

* Bug 1180592 - [Messages][NG] mozMobileConnections shim Implementation
* gaia fast list experiment

Threads.js

* Support DOMError instance in client/service method reject

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
