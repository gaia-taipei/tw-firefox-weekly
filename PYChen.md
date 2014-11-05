Last Week (10/28 - 10/31)

* [woodduck]
	- [done] Bug 1072064 - [Woodduck][Rose][Call log][Case Fail][SOUL35_GEMINI]The Data still displayed after you delete the call log from miss call Table.
		- addressed reviewer's comment and got r+, landed in v2.0m
	- [done] Bug 1087214 - [Woodduck][v2.0][Message][MGSEI]It will pop up "Camera ." and can't record video when add video attachment by selecting camera option in message. 
		- seems it is gecko issue and dup to bug 1082442.
	- [done] Bug 1089576 - [woodduck] Could not play youtube video on youtube
		- POVB, codec broken, partner issue.
	- [done] Bug 1087143 - [MGSEI][Woodduck][v2.0][Browser]Can't close tab when you tap "X" icon on the right. 
		- worksforme
	- [done] Bug 1090171 - [woodduck][feature] issue title [FFOS2.0][Woodduck][browser]Can't download RTSP video CRID ALPS01769548.
		- help to clarify this is a feature request.
	- [done] Bug 1087935 - [MGSEI][Flame][Woodduck][v2.0][Music]It switches from Playlist/Artists/Albums/Songs view to the main Music view automatically if you connect and disconnnect PC with USB storage.
		- help to cherry-pick from v2.1, dup to bug 1043712.
	- [done] Bug 1090911 - [FFOS2.0][Woodduck][Download]No response when select the file open in downloads.
		- worksforme.
	- traige meeting v2.0 x 1, v2.0m x 2
		- 2.0m+  `11 bugs` found, 3 stk bugs. 
		- 2.0m?  `11 bugs` found. 
		- defects unmarked `12 bugs` found.
* [others]
	- [done] Bug 1079647 - [Woodduck][Downloads]Stopped file can not try again 
		- help to apply v2.1 approval.
	- [done] Bug 1091993 - [Dialer] ConfirmDialog broken after deleting call logs. 
		- file a bug.
	- [done] Bug 1085303 - [Tako][Gallery]It takes long time to remove all picture thumbnails from Gallery app when removing SD-card with numerous jpg-pictures. 
		- help to clarify issue, seems I/O opreation is bottleneck.
	- [done] Bug 1087842 - [Flame]Character broken on the Shift-JIS encoding type web-site.
		- answer partner question.
* [Memory Profiler]
	- draw overall histogram on canvas, after discussing with Ting-yuan and Kanru, we need to draw function name tree on UI. more detail please refer to https://wiki.mozilla.org/MemoryProfiler.
	
This week

* [woodduck]
	- answer a lots of ni requests.
	
		

Last Week (10/20 - 10/24)

* [woodduck]
 	- [WIP] Bug 1072064 - [Woodduck] The Data still displayed after you delete the call log from miss call Table.
		- under review
	- [DONE] Bug 1079647 - [Woodduck][Downloads]Stopped file can not try again.
		-  apply v2.1 approval.
	- [DONE] Bug 1069151 - [Woodduck][Email]The sender will be not default email account when share picture by email.
		- Help to carify issue, seems it is by design.
	- traige meeting * 2
 		- 2.0m+ `6 bugs` found, all gaia are assigned.
 		- 2.0m? `10 bugs` found
 		- defects unmarked `20 bugs` found.
* [others]
	- reply to partner's questions on email
		- preload app
		- how to hide app on homescreen via app.role
		- how to coustomized camere config.js
	- help on Vliu about camera and html questions.
* [Memory Profiler]
	- construct trace information, survey canvas library for drwaing memory analytics data.
This week
* [Memory Profiler]
	- drwaing memory analytics data on canvas.
 
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