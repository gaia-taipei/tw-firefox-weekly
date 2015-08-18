## 08/17 ~ 08/21

Message team NGA status

* Bug 1184865 - [Messages][NG] Replace some methods in MessageManager with messaging service in conversation view
* Bug 1167144 - [Messages] Reduce the use of Threads.active and Threads.currentId in conversation view
* Bug 1180592 - [Messages][NG] mozMobileConnections shim Implementation
* gaia fast list experiment

Threads.js

* Make it possible to remove timeout altogether

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
