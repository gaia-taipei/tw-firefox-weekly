10/13-10/17

**[Last week]**

* [Card UI]
	* [WIP] Bug 1076706 - [Stingray][Home] Implement card listing and launching function
		* WIP patch [https://github.com/dwi2/gaia/commit/9753ab47f06e3b3aa70ce0e9f7cc8d7888f95538](https://github.com/dwi2/gaia/commit/9753ab47f06e3b3aa70ce0e9f7cc8d7888f95538)
		* DONE: 
			* model class for card and app
			* read card listing from datastore
			* display card listing onto UI
			* fake deck before we have real deck
			* process initial card list with build script, and load it at start-up time
		* TODO: 
			* able to sync card listing from and to datastore
	* [QUEUED] Bug 1076711 - [Stingray][Home] Pinning bookmark
	* [QUEUED] Bug 1076712 - [Stingray][Home] Implement "folder" 

* [Hardware Key Event]
	* [DUPED] Bug 1083231 - [Lockscreen] Unable to wake up phone with a short press of power button
		* Help to verify symptoms and discuss with Gina.
	* [WIP] Bug 1014418 - Dispatching hardware button event in Gaia
		* There is an unexpected keydown/keyup event for embedder frame, see [https://bugzilla.mozilla.org/show_bug.cgi?id=1014418#c20](https://bugzilla.mozilla.org/show_bug.cgi?id=1014418#c20), that would make app-cancelled scenario not working.
	 
**[This week]**

* [Card UI]
	* [WIP] Bug 1076706 - [Stingray][Home] Implement card listing and launching function
		* WIP patch [https://github.com/dwi2/gaia/commit/9753ab47f06e3b3aa70ce0e9f7cc8d7888f95538](https://github.com/dwi2/gaia/commit/9753ab47f06e3b3aa70ce0e9f7cc8d7888f95538)
		* DONE: 
			* model class for card and app
			* read card listing from datastore
			* display card listing onto UI
			* fake deck before we have real deck
			* process initial card list with build script, and load it at start-up time
		* TODO: 
			* able to sync card listing from and to datastore
	* [QUEUED] Bug 1076711 - [Stingray][Home] Pinning bookmark
	* [QUEUED] Bug 1076712 - [Stingray][Home] Implement "folder" 

* [Hardware Key Event]
	* [WIP] Bug 1014418 - Dispatching hardware button event in Gaia
		* There is an unexpected keydown/keyup event for embedder frame, see [https://bugzilla.mozilla.org/show_bug.cgi?id=1014418#c20](https://bugzilla.mozilla.org/show_bug.cgi?id=1014418#c20), that would make app-cancelled scenario not working.
		* TODO: discuss solution with Gina
	* [QUEUED] Bug 1014405 - [Stingray] Keyboard event handling in Gaia
		* TODO: integrate hardware key event dispatching into Card UI architecture
