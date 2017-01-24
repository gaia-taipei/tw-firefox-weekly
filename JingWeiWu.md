## 1/16 - 1/20

Android

- [Bug 1323366](https://bugzilla.mozilla.org/show_bug.cgi?id=1323366) - Crash in java.util.ConcurrentModificationException: at java.util.TreeMap$MapIterator.stepForward(TreeMap.java))
	- WIP, implement a test case to verify ConcurrentModificationException.
	
- [Bug 1325586](https://bugzilla.mozilla.org/show_bug.cgi?id=1325586) - Crash in java.lang.NullPointerException: key == null at android.util.LruCache.get(LruCache.java)
	- Patch landed
	
- [Bug 1237956](https://bugzilla.mozilla.org/show_bug.cgi?id=1237956) - Files uploaded to server have their filename changed
	- r?sebastian

- Performance Assessment
	- Still study Autophone S1S2 test case

- Autofill
	- Wait for PM's response for further investigation
	
