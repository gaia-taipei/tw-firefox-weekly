## 3/20 - 4/14

Android

- [Bug 1232439](https://bugzilla.mozilla.org/show_bug.cgi?id=1232439) - Full-page edit bookmark dialog 
	- Reject because of several sync issue, discussed with Grisha and fixed for another review.
	- r?grisha
	
- [Bug 1329130](https://bugzilla.mozilla.org/show_bug.cgi?id=1329130) - Fennec Bookmark Management: Allow users to created nested folders
	- Reject because of several sync issue, discussed with Grisha and fixed for another review.
	- r?grisha
	
- [Bug 1329128](https://bugzilla.mozilla.org/show_bug.cgi?id=1329128) - Fennec Bookmark Management: Allow users to create, remove and move folders
	- r?grisha
	
- [Bug 1339884](https://bugzilla.mozilla.org/show_bug.cgi?id=1339884) - Crash in java.lang.NullPointerException: at org.mozilla.gecko.prompts.PromptInput$DateTimeInput.getValue(PromptInput.java) on Android 4.x
	- patch landed
	
- [Bug 1332547](https://bugzilla.mozilla.org/show_bug.cgi?id=1332547) - Simplify fennec bookmark menu items
	- r-grisha, he suggested providing more telemetry experiments.
	- Provide context menu telemetry data in bookmarks panel for further invetigation.
		- https://sql.telemetry.mozilla.org/queries/3721/source
	- Ask Tori and Anthony for helping decide how to simplfy the menu items.
	- WIP
	
- Study sync behavior in Fennec
	- FxA & Android-sync
	- https://hackmd.io/CYNhFME4FYGMEMC014CYBGiAsAGDjIdwtE9YstJh4BmHARmiA===

- Study BrowserToolbar(Awesome bar) behavior for Photon
