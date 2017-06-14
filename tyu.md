[ P1 for tyu ]

* [Bug 1370156](https://bugzil.la/1370156) - Consider enabling jumboMode for bigger string table 
  * Assignee, new assigned
  * r+nalexander, will submit after merge complete, this is needed otherwise we can't build.

* [Bug 1367768](https://bugzil.la/1367768) - Gradle build fails with DexIndexOverflowException, consider enabling jumbo mode.
  * Assignee, resolved fixed
  * r=maliu
  * Temporary fix to not block developers, but does not interfere the release product. We will land thoroughly with 1370156.
  
* [Bug 1286677](https://bugzil.la/1286677) - Re-evaluate multidex method limit solution before using gradle for production builds
  * Assignee, new assigned
  * First priority since this blocks any big code landing including from desktop.
  
* [Bug 1372075](https://bugzil.la/1372075) - Move android-api-15 tier-2 Taskcluster tasks to tier-1
  * Co-assignee-to-be, new unassigned
  * Will work on part of this with Max when resource available.
  
[ P2 for tyu ]
  
* [Bug 1369650](https://bugzil.la/1369650) - Fix lint: NewApi issues in WebAppActivity.java
  * Assignee, new assigned
  * r-maliu, some coding style need to sync. Will re-send when have time.
  
* [Bug 1369654](https://bugzil.la/1369654) - Fix lint: NewApi issues in themes.xml
  * Assignee, new assigned
  * Going to submit for review when have time.

[ Others ]
