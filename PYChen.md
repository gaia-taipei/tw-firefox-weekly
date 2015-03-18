Last Week (03/09-03/13)
* [woodduck]
	- Bug 1138259 - [Monitor][Contacts]Some contact doesn't deleted when from dialer to contacts. 
		- still has discussion with Francisco on this issue, seem mozContact API limitation or need to split contacts and dialer APPs.
 	- Bug 1139238 - [FFOS2.0][Woodduck][Airplane mode]The airplane mode is invalid
 		- got r+ and fixed test failed.
 	- Bug 1118676 - [E.ME][v2.0] Cannot add app to homescreen
 		- fixed and land in v2.0m
 	- Bug 1129278 - [FFOS][Woodduck]Application run in clear all automaticlly after restarting MS
 		- help to invesigate and wait onwer to check Whether is feature or bug?
 	- Bug statuts
      		- 2.0M?, UNFIX: 2
      		- 2.0M+, UNFIX: 2
* [other]
 	- Bug 1141947 - [Camera][flame] enable ZSL (zero shutter lag)
 		- help Becker and answer him some camera issue.
        - help to clarify camera performace issue with partner via email
* [lockscreen]
	- prepare brownbag
        
Last Week (03/02-03/06)
* [wooduck]
	- Bug 1138259 - [Monitor][Contacts]Some contact doesn't deleted when from dialer to contacts.
		- have a patch for reviewing.
	- Bug 1139238 - [FFOS2.0][Woodduck][Airplane mode]The airplane mode is invalid 
		- have a patch for reviewing, and need to address reviewer's comment.
	- [fixed] Bug 1121365 - [Flame][Homescreen]The text in the delete app page is shown out of the page when user delete the custom smart collection with the name more than 30 characters.
		- fixed and land in v2.0m, v2.1s
	- Bug statuts
      		- 2.0M?, UNFIX: 2
      		- 2.0M+, UNFIX: 1
* [memory profiler]
	- move js to shared repo, let two add-ons can use share files.
	- fix minor bug
	- improve canvas feature
		- add base line and the maximum label.

Last Week (02/09 - 02/26)

* [wooduck]
	- Bug 1099019 - [Settings]The notification will cover the tiltle when you tap "Terms of Service/Privacy Notice". 
		- QA want to uplift to v2.1, but bajaj reject approval.
	- [fixed] Bug 1128359 - [FFOS2.0][Woodduck][Voicemail]MS go to SIM2 when set the voicemail number.
		- fixed and landed, and double confirmed with partner, TCL code still has issue but it wasn't cause by mozilla.
	- Bug 1130941 - [Woodduck]FTU doesn't show up after pressing "Reset Phone" in "Settings"
		- clean ni?, it's a POVB.
	- [fixed]Bug 1106693 - [woodduck][BT] Can't disconnect with stereo BT headset if media connection not connected
		- fixed and landed, disable button while it still in processing. 
	- [fxied] Bug 1129278 - [FFOS][Woodduck][Settings]Application run in clear all automaticlly after restarting MS
		- help to provide v2.0m's patch from bug 821604.
	- Bug 1124554 - [FFOS2.0][Woodduck][3rd][File Manager]MS will display a black screen after you share a file by BT.
		- clean ni?, graphic and perfromance issues it won't fix in v2.0m.
	- Bug statuts
      - 2.0M?, UNFIX: 1
      - 2.0M+, UNFIX: 6

* [RTL]
	- [dup] Bug 1128864 - [RTL][Contacts] The reset button display on the wrong position. 
		- have patch for reviewing but reviewer fould it was cat set DUPLICATE of bug 1116803 .
	- [invaild] Bug 1136466 - [RTL] Media player controls progress bar should NOT be mirrored if the rest of controls are not.
		- Have patch but conflict with spec., pm close it and set invaild.
	- [fixed] Bug 1135976 - [RTL][Privacy Controls] Overlapping text in Transparency Control Permissions page 
		- fixed and landed it.
	- [invaild] Bug 1124105 - [RTL][Camera]"More info..." is covered by underline in App Permission view after launching camera in RTL language.
		- have patch but kgrandon(review) set invalid, per comment #8, if we have underline in LTR it sould be there in RTL as well.
	- Bug stauts
		- P1 & P2, UNFIX: 5 (5 Assignees).
		
* [Others]

	- Bug 1131917 - [FFOS7715 v2.1][gaia][camera]When recording video, incoming call, answer the phone, press home button, click camera icon to restart camera, touch the screen, focus ring didn't disappear sometimes. 
		- help to answer ni? 
	- [fixed] Bug 1134321 - Settings app does not fire moz-app-loaded or mark fullyLoaded
		- regression, fixed and landed it.
	- Bug 1117485 - [Video][dolphin][FFOS7715 v2.1] [performance] Open a background Video app spend a longer time.
		- anwser ni?, seems v2.1 has better performance than v1.4.
* [Lockscreen]
	- lockscreen.js, lockscreen_window.js lockscreen_window_manager.js, LockScreenInputWindow.js

This Week
	* [Lockscreen]
		- investigate lockscreen status.
	
	

Last Week (01/26 - 02/06)

* [woodduck]
	- [FIXED]Bug 1126677 - [FFOS2.0][Woodduck]No IMSI detach prodecure when power off.
		- fixed it and land in v2.0m.
	- Bug 1119112 - [woodduck][feature][Call]There is no incoming call interface when incoming a call during quering supplementary services on call setting.
		- Help to figure out the root cause, and transfer to Luke for helping this scince I got OOO last week.
	- Bug 1128359 - [FFOS2.0][Woodduck][Voicemail]MS go to SIM2 when set the voicemail number. 
		- Ask Ej and clarified this issue was fixed on bug 1119696.
	- Bug 1038846 - [Dialer] Once you get a contact suggestion, tapping on it even when empty triggers an "Invalid Number" message.
		- help to prepare v2.0m patch.
	- Bug 1118190 - [Dialer]Device will show an error page after user tap number suggestion panel.
		- Check this issue was fixed on bug 1038846.
	- Bug 1124554 - [FFOS2.0][Woodduck][3rd][File Manager]MS will display a black screen after you share a file by BT.
		- help to invesigate this issue, should be graphic limitation.
	- Bug 1121345 - [FFOS2.0][Woodduck][BT]Music will play out from MS one second after disconnect with headset.
		- per comment it've already fixed in master but it won't not fix in v2.0m.
	- Bug 1106693 - [woodduck][BT] Can't disconnect with stereo BT headset if media connection not connected.
		- fixed it and send to review. 
* [RTL]
	- [dup] Bug 1128864 - [RTL][Contacts] The reset button display on the wrong position. 
	  - Filed bug and send a patch to review, but reviewer siad this bug dup on the other bug so cancel reivew.
	- Read the mail thread about 'RTL' from Juilen, he talks about how to patch RTL issue.
   - bug statuts
      - 2.0M?, UNFIX: 1
      - 2.0M+, UNFIX: 6
This week
	* [woodduck]
		- keep cleaning ni?
	* [Study Group]
		- lockscreen in v2.1 
	* [Memory Profiler]
		- investigate performance issue.

Last Week (01/12 - 01/16)

* [woodduck]
	- [FIXED] Bug 1118545 - [FFOS2.0][Woodduck][Network][data connection]can't enable data conection through shortcut. 
		- prepare v2.1 patch and request v2.1 approval.
	- [PROGRESS] Bug 1121345 - [FFOS2.0][Woodduck][BT]Music will play out from MS one second after disconnect with headset
		- Can be reproduce after communicating with partner and Josh, will figure out how to fix it, but it isn't a blocking bug.
	- [DONE] Bug 1117307 - [Video][dolphin][FFOS7715 v2.1] [performance] Video app first start-up spend a longer time
		- Answer ni, it should be performance polish.
	- [DONE] Bug 1117486 - [FFOS2.0][Woodduck][Video streaming]MS restart when play video streaming.
		- It should be gecko issue.
	- [WORKSFORME] Bug 1109982 - [FFOS2.0][Woodduck][Contacts]MS will display serval duplicate names when search contacts.
		- Can not be reproduced.
	- bug statuts
      - 2.0M?, UNFIX: 4, FIXED: 0.
      - 2.0M+, UNFIX: 13, FIXED: 146.
*[Others]
	- Set up new laptop.
	- help VLiu's cmaera issue about porting L.
	- Teach Sku how to preload app via WebIDE.
	- [PROGRESS][2.2+]Bug 1123164 - [Settings]There is no SIM settings icons when you insert SIM2 only in Settings -> Cellular & Data.
		- QA thinks it might be regression from Bug #1094129, but after invesigating, the root cause is settings root panel chnage behavior so there is a timing issue here.

* [Memory Profiler]
	- quick update with Thinker and Ting-yua, sync up our status, but we still pospone sicne stuck in woodduck proejct.

* [Study Group]
	- no progess

This Week

* [woodduck]
	- keep cleaning ni?
* [Study Group]
	- lockscreen in v2.1 
* [Memory Profiler]
	- investigate performance issue.
			
Last Week (01/05 - 01/09)

* [woodduck]
	* [WONTFIX]Bug 1116361-[FFOS2.0][Woodduck][Download]Display as "Save Video" when save a audio.
		- Not gaia isssue, we won't fix on our site partner will customize on thier site.
	* [FIXED] Bug 1113544 - [FFOS2.0][Woodduck][wap][push]the second push message can't be loaded. 
		- Cherry-pick from bug 1041383 and bug 1044406, partner verified it.
	* [FIXED]Bug 1115658 - [FFOS2.0][Woodduck][GCF]Device should not send CLIR register message automatically in powering on.
		- help partner to clarify this issue and give them suggestion for passing certification.
	* [FIXED] Bug 1100262 - [Contacts]These matching contacts are displayed without color tag in Search list when you enable "Order by last name".
		- r+ and landed in v2.0m
	* [FIXED] Bug 1118545 - [FFOS2.0][Woodduck][Network][data connection]can't enable data conection through shortcut.
		- r+ then waiting v2.0m+
	* Bug 1118587 - [Network]there should have a data roaming prompt message display when insert a orange card
		- Consultant.
	* Bug 1118660 - [gaia][camera][FFOS7715 v2.1]How to enable a debug mode by namespaces in Camera.
		- Consultant.
	* [DUP] Bug 1117489 - [Bluetooth]There is a broken highlight area in bluetooth device list.
		-  DUPLICATE of bug 1104618
	* bug statuts
      - 2.0M?, UNFIX: 17, FIXED: 0.
      - 2.0M+, UNFIX: 14, FIXED: 136.
 * [Memory Profiler]
	- no progess

* [Study Group]
	- no progess


This Week

* [woodduck]
	- keep cleaning ni?
* [Study Group]
	- lockscreen in v2.1 
* [Memory Profiler]
	- investigate performance issue.


Last Two Weeks (2014-12-22 ~ 2014-12-31)

* [woodduck] 
	* [Progress] Bug 1113544 - the second push message can't be loaded.
		- ni Gabriele for helping this issue.
	* Bug 1115658 - [FFOS2.0][Woodduck][GCF]Device should not send CLIR register message automatically in powering on 
		- Has a long discussion with partner, we won't change our design and let partner custmize in their code base.
	* [Worksforme]Bug 1109564 - [woodduck][BT] Icon of switch audio path is not correct while make a call via BT headset at the first time.
		- can not reproduce.
	* [fixed] Bug 1115238 - The check icon will be covered by "Mirrored English" after you change to "Mirrored English" language.
		- landed in v2.0m.
	* [Worksforme]Bug 1114908 - [FFOS2.0][Woodduck][Gallery] MS update picture too slow when change insert SD card.
		- HW limitation agree postpone.
	* [fixed] Bug 1092019 - [Woodduck][v2.0][First Time Experience]The check icon will be covered by "Mirrored English" after you change to "Mirrored English" language. 
		- landed in v2.0m.
	* [dup] Bug 1110664 - [Notifications]You can't see update notification and music widget in notification bar.
		- figure out the root cause and find out thr dup bug 1095856.
	* bug statuts
      - 2.0M?, UNFIX: 17, FIXED: 0,
      - 2.0M+, UNFIX: 12, FIXED: 126,

This Week
* [woodduck]
	- keep cleaning ni?
	
* [Memory Profiler]
	- investigate performance issue.

* [Study Group]
	- lockscreen in v2.1 

Last Week (12/15 - 12/19)

* [woodduck] 
	- [INVAILD] Bug 1094119 [Download Manager]There is no button which shown behind the faild file and user can tap it to download the failed file again , user only can try to download the failed file from the notification.
		- excepted behaviour, invaild.
	- [DONE] Bug 1104434 - PNN and SPN can not display when register onto HPLMN.
		- fixed it and landed in v2.0m and master.
	- [DONE] Bug 1099019 - [Settings]The notification will cover the tiltle when you tap "Terms of Service/Privacy Notice".
		- fixed it and landed in v2.0m and master.
	- [WORKSFORME] Bug 1100197 - [FFOS2.0][Woodduck][BT]"Searching for devices" menu display as black during searching process. 
		- can not be reproduced.
	- [GECKO ISSUE] Bug 1108520 - [Woodduck][Dialer]MS will ring all the time after recieve a MT call and immediately hang up it from remote device.
		- investigate and found it should be gecko issue.
	- [DUP] Bug 1111473 - [FFOS2.0][Woodduck][Download][DSW]BMP/WBMP image are displayed as black screen when open it after completed download.
		- have a patch but found :djf has already fixed on other bug 1096839.
	- [DONE] Bug 1092019 - [Woodduck][v2.0][First Time Experience]The check icon will be covered by "Mirrored English" after you change to "Mirrored English" language. 
		- fixed it and landed in v2.0m.
	- [INVAILD] Bug 1102817 - [FFOS2.0][Woodduck][Monitor][Contacts]The Keyboard will appear when click "Gmail" or "Outlook".
		- clarify fxos design.
	- [INVAILD] Bug 1112505 - FFOS2.0][Woodduck][BT]cannot accept transfer files when alarm is ringing unless stop alarm.
		- Help to calrify this is by design.
	- [WORKSFORME] Bug 1110081 - [ALPS01861524][G07][English/Greek/Italian/Turkish/French][BT]Several same bluetooth names showed when search for devices after change language.
		- Can no be reproduced.
	- [PROGRESSING] Bug 1111904 - [FFOS2.0][Woodduck][Gallery]Reaccess gallery after format SD&internal storage, image and video files will refresh for minutes then popup "no photos or videos".
		- Seems FxOS limitation or SDCard format performance issue.
	- [Ni?]Bug 1111490 - [FFOS2.0][Woodduck][Camera]The videos still play after lock the screen.
		- Request help from Sotaro and Wilson page to clairfy is this by design.
	- status
	  - 2.0M?  unfix: 25, fixed:0
	  - 2.0M+  unfix: 14, fixed:109

This Week

* [woodduck]
	- keep cleaning ni?
	
* [Memory Profiler]
	- investigate performance issue.		




Last Week (12/09 - 12/12)

PTO

This Week
* [woodduck]
	- clear up ni?
* [Memory Profiler]
	- planning futuner work such as: `filter feature`, `performance issue` etc....

Last Week (11/10 - 11/17)

* [woodduck]
	- Bug 1097494 - [FFOS2.0][Woodduck][FM][Music]Define how long it takes before prompt pops up to warn the users of hearing damage.
		- help to answer parter issue
	- Bug 1096743 - [FFOS2.0][Woodduck][Call]phone does not vibrate when receive a call.
		- worksforme
	- Bug 1095313 - [woodduck][Camera]Not possible to take videos with low size
		- parter can resolve this issue via camera-config.js
	- Bug 1096158 - [FFOS2.0][Woodduck][PLMN][Network]Network operator 2G and 3G display unclearly 
		- invesigate this is a feature request, we need gecko support for imprving this issue.
	- [done] Bug 1092962 - [FFOS2.0][Woodduck][Voicemail]There is any prompt message when dial the voicemail number by long press the "1" key.
		- r+ and landed on v2.0m
	- traige meeting v2.0m X 2
		- 2.0m? `16 bugs` found
		- 2.0m+ `24 bugs` found
*[others]
	- Bug 1071437 - [Gallery] [Video]Video poster image is flickering after power button pressed twice 
		- video always play first frame before jump to current frame, ni vliu for gecko support.
	- Bug 1098664 - [Midori 2.0][HOMO][o2 Germany] webapps.json for firefox hello(loop) is not properly configured
		- help to answer partner how to preload `hello(loop)`. 
* [Memory Profiler]
	- build up basic UI and rank list view, it can run as an add-ons with simple data. 
	- https://github.com/profiler-tools/memoryprofiler
This week:
* [Memory Profiler]
	- integrate into WEBIDE with Kanru and Ting-yuan. 
Last Week (11/03 - 11/07)

* [woodduck]
	- Bug 1091442 - [Midori 2.0][Camera][Contacts]Can add a video for contact head portrait
		- can not reproduce.
	Bug 1092940 - [FFOS2.0][Woodduck][Dialer]The default value of number and name match is not 7. 
		- can not reproduce.
	- Bug 1091996 - [FFOS2.0][Woodduck][video streaming]The icon disappear during playing video with 128*96 resolution.
		- by design
	- Bug 1092968 - [woodduck][Contacts][Call]It is not display contacts when input 1# in the dialer
		- help to clarify gaia or gecko side handle this issue. 
	- traige meeting v2.0m X 2
		- 2.0m? `8 bugs` found
		- 2.0m+ `31 bugs` found (using new bugzilla search filter)
* [others]
	- Bug 1092012 - [FFOS2.0][Woodduck][Browser][HTML5]Animation effect don't work. 
		- help to answer issue.
* [Memory Profiler]
	- drawing mockup and update on wikipage 
	 - https://wiki.mozilla.org/MemoryProfiler#User_Interface	

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
