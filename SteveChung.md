## This week (09/14 ~ 09/18)

2.5 Blocker
* Bug 1190980 - [Messages] Duration of the copy paste menu triggered from "To:" field is too short to access

Message team NGA status
* Bug 1201016 - [Messages][NG] Migrate the current Message manager event handling to NGA
* Bug 1179628 - [Messages][NG] Lay out Settings service structure 

## Last week (09/07 ~ 09/11)

2.5 Blocker
* Bug 1190980 - [Messages] Duration of the copy paste menu triggered from "To:" field is too short to access
  * Pinged QA about the reproduce step but no responding. Will ask Ting-yu about the issue.

Message team NGA status
* Bug 1180592 - [Messages][NG] mozMobileConnections shim Implementation
  * Landed.
* Bug 1201016 - [Messages][NG] Migrate the current Message manager event handling to NGA
  * Ongoing, created a WIP for early feedback and tried to fix the duplicated event from different instances because message event will be broadcasted from service instead of from API event listener, and All the instance will receive the broadcast no matter which instance fires the event.
* gaia fast list experiment: Still no progress, will move it into low priority topic for now
