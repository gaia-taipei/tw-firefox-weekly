## 6/7 ~ 6/24

- [Firefox]
	- [r-] [Bug 1000700](https://bugzilla.mozilla.org/show_bug.cgi?id=1000700) - menu-button dropmarkers aren't inverted with dark LWT
		- Reviewer asked me to take a different direction
	- [UI feedback] [Bug 285836](https://bugzilla.mozilla.org/show_bug.cgi?id=285836) - Make "Remove All Cookies Now" undoable
		- Got a working patch, now asking a firefox UX to take a look
	- [Fixed] [Bug 754623](https://bugzilla.mozilla.org/show_bug.cgi?id=754623) - Name field of bookmarks saved via "Bookmark All Tabs" is empty when loading the tab is deferred
		- A bug related to [Bug 446171](https://bugzilla.mozilla.org/show_bug.cgi?id=446171)
		- Broken try results were caused by a [bug](https://bugzilla.mozilla.org/show_bug.cgi?id=1270962), issue mostly resolved after rebasing

- [Fennec about-improvements]
	- [UI feedback] [Bug 1091237](https://bugzilla.mozilla.org/show_bug.cgi?id=1091237) - Show more information in add-ons detail view in about:addons
		- Anthony said the design is still not ready yet

- [Date-time Picker]
	- [Bug 888320](https://bugzilla.mozilla.org/show_bug.cgi?id=888320) - [meta] implement all time and date related input types
		- Working on a rough UI based on the current design. Also experimenting different ways to implement scrolling.

- [London Work-Week]
	- Met up and catch up with people from Firefox front-end, Firefox Android, Firefox iOS.
	- Had meetings on different aspects of Date-time Picker, ex: UX, l10n, accessibility
	- Attended sessions on Activity Stream, Context Graph, Devtools, Firefox for Android & iOS, Project Coral, L10n, Mozilla Speakers Program, and more.
		- Activity Stream: [Issues on Github](https://github.com/mozilla/activity-stream/issues). The team is thinking about making standalone apps on iOS and Android. Currently it uses [Embedly](http://embed.ly/) for grabbing thumbnail and media widgets, but at some point it needs to be built into Firefox.
		- Firefox for Android & iOS: while the team works on Context Graph, they will still review patches and bug fixes. For iOS, bugs with mentor on it are good places to start.
		- Project Coral: A project focused on bringing out the value of comments on news websites. Allows journalists the ability to set advanced queries on comments, and does more than fight spam. It can foster better community and bring about constructive comments.
		- L10n: The new L10n system is set to land soon. It offers localisers more flexibility and makes the process easier.
