### Last week
* Read STK/ICC source codes.

* [WIP][bug 1069749](https://bugzil.la/1069749)
Take a polish bug. Found a related js: font_size_utils.js
The margin left/right of the header is calculated incorrectly due to clientWidth of header.
The incorrect alignment (Passcode cand Call log) are in the same situation that the button of tool menu is <a> tag rather than <button>.
However, I am not sure that the strange behavior is caused by <a>/<button> tag. I have to do more experiments.

* [WAITING][bug 1069217](https://bugzil.la/1069217) The send button is be covered when there have two matched phone muber in here  
This bug can be reproduced on Flame 2.2, so it is a generic bug.
Create a new bug 1083117 to track this generic one.
The bug 1082908 gets a patch to fix the same UX issue for bug 1083117.
Waiting for the code landed, and I will check the issue resolved or not then.

* [bug 1070439](https://bugzil.la/1070439)
SIM1&2 and Voicemail related issue. this bug is reproduced.
I have not taken a look the source code yet.

* [bug 1074069](https://bugzil.la/1074069) If we get an error when the user tries to send, check if PIN is required
l10n change is needed. bug 1079690 is created to rework the process of PIN panel displaying.

* [BLOCKED][bug 1080451](https://bugzil.la/1080451)
dup from [bug 1078978] Create a new bug for refining contacts highlight implementation.
The patch is finished, but it is abnormal where the keyword is in first name.
This bug is blocked by bug 1074643. Please see the description of bug 1074643.

* [bug 1074643](https://bugzil.la/1074643) When we inputted "a"to input box,the contact name display incorrectly.
When I try my patch for bug 1080451, the contact search is broken after the patch of 1074643 landed even without my patch.
I judge this is caused by the patch of bug 1074643, and the screenshots and details are commented on this.
bug 1083733 is created for the abnormal behavior.

### This week

* Keep tracking the bugs which are not finished yet.

* '14、STK的窗口关闭为什么要加设定时器。'
Read STK/ICC related source codes!!!!

