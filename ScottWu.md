## 12/28 ~ 12/31

- [Settings]
	- [WIP] [Bug 1232818](https://bugzilla.mozilla.org/show_bug.cgi?id=1232818) - The SIM PIN was incorrect screen disappears if the user enters 9 incorrect digits because the number of digits is not capped
		- PR for fxos-component accepted. Need to update the component in gaia.
	- [WIP] [Bug 973458](https://bugzilla.mozilla.org/show_bug.cgi?id=973458) - [settings] refactor Downloads panel with AMD pattern
		- Fixing unit tests
	- [WIP] [Bug 1208893] (https://bugzilla.mozilla.org/show_bug.cgi?id=1208893) - Add a warning text in Low Storage mode to the storage panels
		- Raised a question on [Bug 1204618] (https://bugzilla.mozilla.org/show_bug.cgi?id=1204618), now waiting for a response

- Planned Tasks
	- Testing
		- Fix [intermittent tests](https://github.com/mozilla-b2g/gaia/blob/master/shared/test/integration/tbpl-manifest.json#L54) for Settings
			- `airplane_mode_settings_test`
			- `app_permission_settings_test`
			- `hotspot_wifi_settings_test`
			- `message_settings_test`
			- `screen_lock_settings_test`
		- [Bug 1218698](https://bugzilla.mozilla.org/show_bug.cgi?id=1218698) - [Settings][Add-On] Add integration test for add-on install and removal
	- Refactoring
		- [Bug 1178156](https://bugzilla.mozilla.org/show_bug.cgi?id=1178156) - [Settings][meta] Define modules using new syntax provided by Observable
		- [Bug 973432](https://bugzilla.mozilla.org/show_bug.cgi?id=973432) - [Settings][meta] panel refactor with AMD pattern

- Reviewed
	- [r+] [Bug 1229263](https://bugzilla.mozilla.org/show_bug.cgi?id=1229263) - move getSupportedNetworkInfo into module
	- [r+] [Bug 1159657](https://bugzilla.mozilla.org/show_bug.cgi?id=1159657) - [Meta] remove utils.js and move all it's functionality to related modules

## 2015 Q4 Goals

1. Remove blocker issues for the Settings app & others, as measured by blocker burn down and days of blocker turnarounds.
- Implement new features for the Settings app & others, as measured by feature burn down and days of blocker turnarounds. (This goal need clarification if we know what feature to work on)
- Help increase unit/integration test coverage, as measured by # of tests planned and/or written.

