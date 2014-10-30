Last Week (10/13 - 10/17)

* [woodduck]
	- [WIP] Bug 1079647 - [Woodduck][Downloads]Stopped file can not try again
		- investigate download manager.
		- have a patch for reviewing.
	- [DONE] Bug 1071350 - [Woodduck][Rose][SQC1][Free Test][Call]The UI will display abnormally when we tap one call before merge to conference call successfully(5/5) 
		-	can't be reproduced, set work for me. 
 	- traige meeting * 2
 		- 2.0m+ `9 bugs` found, all gaia are assigned.
 		- 2.0m? `5 bugs` found
 		- defects unmarked `25 bugs` found.
* [Memory Profiler]
	- mock memoryprofiler api	
		- https://github.com/mpizza/memoryprofiler
	- figure out outdata format and will implement this tool on firefox add-ons in first phase.
* [Other]
	- answer partner how to preload app.
		- https://www.evernote.com/shard/s146/sh/c1d448f9-66e4-4a1d-b377-bf9082f636a0/e4b49db2934f95269900e67123d714a7 
* [PTO] *1
This Week
	- [DONE] Bug 1079647 - [Woodduck][Downloads]Stopped file can not try again
		- r+ and land in v2.0m, file follow up issue for fixing root cause, `bug 1085245`.
* [Memory Profiler]
	- constroct trace infromation with allocation_event and trace.

## 10/06 - 10/09 ##
### Last Week ###
* [woodduck]
	1. Bug 1078151 - [Comms][Contacts]After we tap "Search" in Gmail view,some contacts without picture have a circle.
		- got r+
	2. Bug 989704 - "visible to all' was disabled after turn off bluetooth and turn on again
		- After investigating and discussing with Arthur and Jenny, it is by design. We decided to file `bug 1080427`, Jenny will give a full specs in the future. 
	3. traige meeting * 1
		- 2.0m+ 9 bugs found, 2 non-assignee, bug 1059037, 1074069.
		- 2.0m? 9 bugs found, 1 assignee. 
		- defects unmarked 29 bugs found.
		- Bug 1080481 - (Woodduck_2.0_Generic) [meta][Woodduck 2.0 Generic]
			- tracking 2.0_Generic issue but only land in 2.0m.
			- 22 bugs found
* [dolphin]
	1. Bug 1069822 - unable to set wallpaper after zoom in a picture
		- there is a dup `bug 1055805`, help to prepare `v1.4`, `v2.0` patch.
* [Memory Profiler]
	- We are planning to use dev-tool profiler panel, and we will find someone to help on how to integate profiler panel. I will focus on app side.
	
* [others]
	1. Bug 1068540 - [camera] recording stopped by power key is not saved
		- camera app can not receive 'storage change' event when screen passcode enabled, seems this is a gecko issue.
	2. Bug 1071433 - [gallery]share with ringtone is seen in gallery
		- help TAM to redirect right people to review patch.
### This Week ###
* [Memory Profiler]
	- using sample logs for prototype.

## 9/29 - 10/3 ##

### Last Week ###

* [DE team work flow discussion]
* [woodduck] 
	1. Bug 1073395 "unplug usb cable to disable" become "disable" when you suspend and resume the device.
		- help to verifed issue, seems can not be reporduced on flame and woodduck set as 'worksforme'.
	2. Bug 1076601 - Usb storage "show disable" all the time.
		- help to verifed issue, seems can not be reporduced
	3. Bug 1069792 - [Calendar]The mark show uncorrectly when the time from 18 to 19.
		- discussed with Evan, since flame can be reproduced he filed another generic bug 1075455 for tracing it.
	4. Bug 1068504 - [woodduck][Gallery]After deleting an image,will back to homescreen.
		- help to verifed issue and record video for proving it, seems can not be reporduced on flame and woodduck set as 'worksforme'.
	5. traige meeting*2
		- 2.0m+ 8 bugs found, 0 gaia issue
		- 2.0m? 14 bugs found, 3 assignee. 
		- defects unmarked 42 bugs found.
* [dolphin]
	1. Bug 1069822 - unable to set wallpaper after zoom in a picture
	- sent a patch to djf and wait feedback.
* [memory profilng tool]
	1. investigate tasktracer how to update log from devices, and trace webIDE code base.

**
### This Week ###

* [woodduck]
	1. Bug 1078151 - [Comms][Contacts]After we tap "Search" in Gmail view,some contacts without picture have a circle.
	- fixed it and sent to review.
* [dolphin]
	1. Bug 1069822 - unable to set wallpaper after zoom in a picture
	- sent a patch to djf and wait feedback.
* [memory profilng tool]
	1. using sample log for brainstorming with Chens. 