## 1/9 - 1/13

Android

- [Bug 1285802](https://bugzilla.mozilla.org/show_bug.cgi?id=1285802) - Cancel fullscreen does not automatically adjust the screen orientation
	- Patch landed

- [Bug 1289690](https://bugzilla.mozilla.org/show_bug.cgi?id=1289690) - Addons icon in url bar display is not normal
	- Assign to nobody
	- Sebastian thinks add-on needs provide icons in multiple densities, so there is nothing we can do in Fennec.

- [Bug 1323366](https://bugzilla.mozilla.org/show_bug.cgi?id=1323366) - Crash in java.util.ConcurrentModificationException: at java.util.TreeMap$MapIterator.stepForward(TreeMap.java))
	- r-sebastian, need more investigation
	
- [Bug 1325586](https://bugzilla.mozilla.org/show_bug.cgi?id=1325586) - Crash in java.lang.NullPointerException: key == null at android.util.LruCache.get(LruCache.java)
	- r?sebastian, also ask Sebastian should we show a default icon in search preference page

- Performance Assessment
	- Still study Autophone S1S2 test case

- Autofill
	- Study spec for requirement on mobile and have a discussion with PM
	- Ask Joe to help get wireframe for further investigation
	
