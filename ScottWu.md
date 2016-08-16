## 8/8 ~ 8/12

- [Firefox]
	- [r-] [Bug 1000700](https://bugzilla.mozilla.org/show_bug.cgi?id=1000700) - menu-button dropmarkers aren't inverted with dark LWT
		- Reviewer asked me to take a different direction
	- [UI feedback] [Bug 285836](https://bugzilla.mozilla.org/show_bug.cgi?id=285836) - Make "Remove All Cookies Now" undoable
		- Got UX feedback, will make a few changes to the patch

- [Date-time Picker]
	- [Bug 1283381](https://bugzilla.mozilla.org/show_bug.cgi?id=1283381) - [meta] Implement UI for date time input types
		- [Bug 1283384](https://bugzilla.mozilla.org/show_bug.cgi?id=1283384) - Implement UI for \<input type="time"\>
	- [Tracking] [Bug 1280654](https://bugzilla.mozilla.org/show_bug.cgi?id=1280654) - Expose a generic API for polling data out of CLDR
	- [Tracking] [Bug 1287677](https://bugzilla.mozilla.org/show_bug.cgi?id=1287677) - Expose an API to provide display names for calendar terms

#### Date Time Pickers Tasks:

- General features
	- [feedback?] Passing data between input field and pickers
	- Keyboard Controls
		- Jessica will handle keyboard events, UI only receives changes made
- Month picker
	- [Done] Spinner component (basic functionalities)
	- [Hold] Spinners are combined when indivisible step is used
		- UX considering removing this from the spec
- Time picker
	- [Done] AM/PM component
	- [WIP] Spinner cycle feature
	- [Done] Spinner scroll snap even with few items
	- [Done] Extract time state handling into a module
		- Fixed step with min & max
		- Could be used by input box too, will discuss detail with Jessica
- Date picker
	- Calendar component
	- First day of the week & weekends configurable
- Week picker
	- Calendar week feature
- Datetime picker
	- Combining date picker and time picker

- Full L10n support
	- Getting localized strings with Intl API
	- Get calendar info with Intl API
	- Spinner orders depend on locale
- Full a11y support
	- Tab focus
	- Alt text & ARIA

