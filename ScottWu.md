## 7/11 ~ 7/15

- [Firefox]
	- [r-] [Bug 1000700](https://bugzilla.mozilla.org/show_bug.cgi?id=1000700) - menu-button dropmarkers aren't inverted with dark LWT
		- Reviewer asked me to take a different direction
	- [UI feedback] [Bug 285836](https://bugzilla.mozilla.org/show_bug.cgi?id=285836) - Make "Remove All Cookies Now" undoable
		- Got UX feedback, will make a few changes to the patch

- [Date-time Picker]
	- [Bug 1283381](https://bugzilla.mozilla.org/show_bug.cgi?id=1283381) - [meta] Implement UI for date time input types
		- [Bug 1283382](https://bugzilla.mozilla.org/show_bug.cgi?id=1283382) - Implement UI for \<input type="month"\>
			- Improved the structure of the month picker
			- Working on putting together the month picker and run it in Firefox
	- [Tracking] [Bug 1280654](https://bugzilla.mozilla.org/show_bug.cgi?id=1280654) - Expose a generic API for polling data out of CLDR
		- Continued discussion about the APIs

#### Date Time Pickers Tasks:

- General features
	- Passing data between input field and pickers
	- Two way communication to reflect changes immediately
- Month picker
	- Spinner component
	- Spinners are combined when indivisible step is used
- Time picker
	- Spinner cycle feature
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
	- Keyboard control
	- Tab focus
	- Alt text & ARIA
