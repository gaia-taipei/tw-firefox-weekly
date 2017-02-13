## 1/23 - 1/26

Android

- [Bug 1323366](https://bugzilla.mozilla.org/show_bug.cgi?id=1323366) - Crash in java.util.ConcurrentModificationException: at java.util.TreeMap$MapIterator.stepForward(TreeMap.java))
	- r?sebastian, also ask what kind of unit test should add for this bug.
	
- [Bug 1237956](https://bugzilla.mozilla.org/show_bug.cgi?id=1237956) - Files uploaded to server have their filename changed
	- Patch landed
	
- [Bug 1330257](https://bugzilla.mozilla.org/show_bug.cgi?id=1330257) - LastPass auto-fill has broken in latest version of Firefox for Android
	- This regression might be caused by LastPass because using firefox 48/49 with latest LastPass, the problem still occurs.
	- Send a support case to LastPass. They said it's not optimized to work in Firefox and suggested to use add-on.
	- Servey AccessibilityService to see if anything we can do to make LastPass workable

- Performance Assessment
	- Still study Autophone S1S2 test case

- Autofill
	- Wait for PM's response for further investigation
	
