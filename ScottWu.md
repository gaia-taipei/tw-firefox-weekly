## 10/24 ~ 10/28

- [Firefox]
	- [r-] [Bug 1000700](https://bugzilla.mozilla.org/show_bug.cgi?id=1000700) - menu-button dropmarkers aren't inverted with dark LWT
		- Reviewer asked me to take a different direction
	- [UI feedback] [Bug 285836](https://bugzilla.mozilla.org/show_bug.cgi?id=285836) - Make "Remove All Cookies Now" undoable
		- Got UX feedback, will make a few changes to the patch

- [Date-time Picker]
	- [Bug 1283381](https://bugzilla.mozilla.org/show_bug.cgi?id=1283381) - [meta] Implement UI for date time input types
		- [landed] [Bug 1283384](https://bugzilla.mozilla.org/show_bug.cgi?id=1283384) - Implement UI for \<input type="time"\>
		- [r-] [Bug 1301284](https://bugzilla.mozilla.org/show_bug.cgi?id=1301284) - Update picker style to match the visual spec for \<input type="time"\>
			- Got feedback from Mike, will address issues and r? again ASAP
		- [WIP] [Bug 1309471](https://bugzilla.mozilla.org/show_bug.cgi?id=1309471) - [DateTimePicker] Add browser chrome test for time picker
			- WIP is on mozreview
		- [WIP] [Bug 1283385](https://bugzilla.mozilla.org/show_bug.cgi?id=1283385) -  Implement UI for \<input type="date"\>

#### Date Time Pickers Tasks:

- General features
	- [Done] Passing data between input field and pickers
	- [Hold] Keyboard Controls
		- To be implemented in follow up bugs
		- Input box handles keyboard events most of the time, until user triggers shifting "visual focus" to picker
- Month picker
	- [Done] Spinner component (basic functionalities)
	- [Hold] Spinners are combined when indivisible step is used
		- UX considering removing this from the spec
- Time picker
	- [Done] AM/PM component
	- [Done] Spinner cycle feature
	- [Done] Spinner scroll snap even with few items
	- [Done] Extract time state handling into a module
	- [Done] Changed how updates are handled to make sure it works for years
	- [Done] Integrate with input boxes
	- [Done] Out of range items are displayed but greyed out
	- [Done] Fix panel arrow position
- Date picker
	- [WIP] Basic calendar component
		- Display calendar in 6 week rows
		- First day of the week & weekends configurable
		- Apply basic styling
	- Add max and min features
		- Dates earlier than min or later than max are greyed out
		- Out of range years are not displayed, and months are greyed out
	- Add step features
		- Off step items are greyed out
	- Transition animation
		- Animation for previous and next month
		- Animation for opening picker
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
