## 12/16 ~ 12/18

- [Settings]
	- [WIP] [Bug 1232818](https://bugzilla.mozilla.org/show_bug.cgi?id=1232818) - The SIM PIN was incorrect screen disappears if the user enters 9 incorrect digits because the number of digits is not capped
	- [Fixed] [Bug 1232797](https://bugzilla.mozilla.org/show_bug.cgi?id=1232797) - The 2nd 'Enter PUK code' dialog (if 1st PUK dialog is skipped) lacks labeling on fields
	- [WIP] [Bug 973458](https://bugzilla.mozilla.org/show_bug.cgi?id=973458) - [settings] refactor Downloads panel with AMD pattern
	- [WIP] [Bug 835497](https://bugzilla.mozilla.org/show_bug.cgi?id=835497) - [B2G][Settings] Display: Brightness does not adjust as the slider is being moved
		- Has a working version but want to try a different approach.
	- [WIP] [Bug 1208893] (https://bugzilla.mozilla.org/show_bug.cgi?id=1208893) - Add a warning text in Low Storage mode to the storage panels
		- Raised a question on [Bug 1204618] (https://bugzilla.mozilla.org/show_bug.cgi?id=1204618), now waiting for a response

- Planned Tasks
	- Testing
		- [Bug 1218698](https://bugzilla.mozilla.org/show_bug.cgi?id=1218698) - [Settings][Add-On] Add integration test for add-on install and removal
	- Refactoring
		- [Bug 1178156](https://bugzilla.mozilla.org/show_bug.cgi?id=1178156) - [Settings][meta] Define modules using new syntax provided by Observable
		- [Bug 973432](https://bugzilla.mozilla.org/show_bug.cgi?id=973432) - [Settings][meta] panel refactor with AMD pattern

## 2015 Q4 Goals

1. Remove blocker issues for the Settings app & others, as measured by blocker burn down and days of blocker turnarounds.
- Implement new features for the Settings app & others, as measured by feature burn down and days of blocker turnarounds. (This goal need clarification if we know what feature to work on)
- Help increase unit/integration test coverage, as measured by # of tests planned and/or written.

