## 1/11 ~ 1/15

- [Settings]
	- [WIP] [Bug 1004348](https://bugzilla.mozilla.org/show_bug.cgi?id=1004348) - Intermittent failing test, manipulate app permissions set geolocation of first app to Grant
	- [Reviewing] [Bug 981560](https://bugzilla.mozilla.org/show_bug.cgi?id=981560) - [settings] add marionette test for device information - More information panel
	- [WIP] [Bug 1232818](https://bugzilla.mozilla.org/show_bug.cgi?id=1232818) - The SIM PIN was incorrect screen disappears if the user enters 9 incorrect digits because the number of digits is not capped
		- Sent another PR, to fix inputmode issue. Waiting for review.
	- [Fixed] [Bug 973458](https://bugzilla.mozilla.org/show_bug.cgi?id=973458) - [settings] refactor Downloads panel with AMD pattern
	- [WIP] [Bug 1208893] (https://bugzilla.mozilla.org/show_bug.cgi?id=1208893) - Add a warning text in Low Storage mode to the storage panels
		- Raised a question on [Bug 1204618] (https://bugzilla.mozilla.org/show_bug.cgi?id=1204618), now waiting for a response

- [Build]
	- [WIP] [Bug 1131497](https://bugzilla.mozilla.org/show_bug.cgi?id=1131497) - Running build-test.js on node.js
	- [Fixed] [Bug 1131514](https://bugzilla.mozilla.org/show_bug.cgi?id=1131514) - Remove deprecated watcher.js and monitor.js

- Planned Tasks
	- Testing
		- Fix [intermittent tests](https://github.com/mozilla-b2g/gaia/blob/master/shared/test/integration/tbpl-manifest.json#L54) for Settings
			- `app_permission_settings_test`
			- `hotspot_wifi_settings_test`
			- `message_settings_test`
		- [Bug 1218698](https://bugzilla.mozilla.org/show_bug.cgi?id=1218698) - [Settings][Add-On] Add integration test for add-on install and removal
	- Refactoring
		- [Bug 1178156](https://bugzilla.mozilla.org/show_bug.cgi?id=1178156) - [Settings][meta] Define modules using new syntax provided by Observable

- Reviewed
	- [r+] [Bug 1131519](https://bugzilla.mozilla.org/show_bug.cgi?id=1131519) - Running push-to-device.js on node.js
	- [r+] [Bug 1131524](https://bugzilla.mozilla.org/show_bug.cgi?id=1131524) - Running shared-utils.js on node.js
	- [r+] [Bug 1131505](https://bugzilla.mozilla.org/show_bug.cgi?id=1131505) - Running homescreen-manager.js on node.js
	- [r+] [Bug 1227796](https://bugzilla.mozilla.org/show_bug.cgi?id=1227796) - Intermittent screen\_lock\_settings\_test.js | manipulate screenLock settings passcode is enabled and won't get disabled if you tap back button when we try to disable passcode directly
	- [r-] [Bug 1238445](https://bugzilla.mozilla.org/show_bug.cgi?id=1238445) - enable apps/settings/test/marionette/tests/airplane\_mode\_settings\_test.js

## 2015 Q4 Goals

1. Remove blocker issues for the Settings app & others, as measured by blocker burn down and days of blocker turnarounds.
- Implement new features for the Settings app & others, as measured by feature burn down and days of blocker turnarounds. (This goal need clarification if we know what feature to work on)
- Help increase unit/integration test coverage, as measured by # of tests planned and/or written.

