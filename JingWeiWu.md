## 1/3 - 1/6

Android

- [Bug 1285802](https://bugzilla.mozilla.org/show_bug.cgi?id=1285802) - Cancel fullscreen does not automatically adjust the screen orientation
	- r?wchen, asking for help reviewing

- [Bug 1289690](https://bugzilla.mozilla.org/show_bug.cgi?id=1289690) - Addons icon in url bar display is not normal
	- need info(alam@mozilla.com) for Addons spec to provide various icon densities
	- If alam suggests to provide different resolution icons, then there should be nothing we can do.

- [Bug 1323366](https://bugzilla.mozilla.org/show_bug.cgi?id=1323366) - Crash in java.util.ConcurrentModificationException: at java.util.TreeMap$MapIterator.stepForward(TreeMap.java))
	- need info(:sebastian), discuss for proper solution
	
- [Bug 1325586](https://bugzilla.mozilla.org/show_bug.cgi?id=1325586) - Crash in java.lang.NullPointerException: key == null at android.util.LruCache.get(LruCache.java)
	- WIP

- Performance Assessment
	- Study Autophone and try to create a sample test case
	- Study Perfherder

- Autofill
	- Study Last Pass behavior(Use AccessibilityService or Addons to communicate with firefox)
	- AccessibilityService doesn't always work on fennec, need further investigatiton
	- Study spec for requirement on mobile
	
