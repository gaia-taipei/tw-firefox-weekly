10/20-10/25

**[Last week]**

* [Card UI]
	* [WIP] Bug 1076706 - [Stingray][Home] Implement card listing and launching function
		* patch is waiting for review [https://github.com/mozilla-b2g/gaia/pull/25477](https://github.com/mozilla-b2g/gaia/pull/25477)
		* DONE: 
			* model class for card and app
			* read card listing from datastore
			* display card listing onto UI
			* fake deck before we have real deck
			* process initial card list with build script, and load it at start-up time
			* able to sync card listing from and to datastore
	* [QUEUED] Bug 1076711 - [Stingray][Home] Pinning bookmark
	* [QUEUED] Bug 1076712 - [Stingray][Home] Implement "folder" 

* [Hardware Key Event]
	* [WIP] Bug 1014418 - Dispatching hardware button event in Gaia
		* got r+ from system app owners, still waiting :zac's review
		* There is an unexpected keydown/keyup event for embedder frame, see [https://bugzilla.mozilla.org/show_bug.cgi?id=1014418#c20](https://bugzilla.mozilla.org/show_bug.cgi?id=1014418#c20), that would make app-cancelled scenario not working. I will file a follow up bug for it.
	 
**[This week]**

* [Card UI]
	* [WIP] Bug 1076706 - [Stingray][Home] Implement card listing and launching function
		* patch is waiting for review [https://github.com/mozilla-b2g/gaia/pull/25477](https://github.com/mozilla-b2g/gaia/pull/25477)
		* DONE: 
			* model class for card and app
			* read card listing from datastore
			* display card listing onto UI
			* fake deck before we have real deck
			* process initial card list with build script, and load it at start-up time
			* able to sync card listing from and to datastore
	* [WIP] Bug 1089464 - [Smart Screen][Home]Launch card directly from smart home
	* [WIP] Bug 1076711 - [Stingray][Home] Pinning bookmark
	* [QUEUED] Bug 1076712 - [Stingray][Home] Implement "folder" 

* [Hardware Key Event]
	* [WIP] Bug 1014418 - Dispatching hardware button event in Gaia
		* got r+ from system app owners, still waiting :zac's review
		* There is an unexpected keydown/keyup event for embedder frame, see [https://bugzilla.mozilla.org/show_bug.cgi?id=1014418#c20](https://bugzilla.mozilla.org/show_bug.cgi?id=1014418#c20), that would make app-cancelled scenario not working. I will file a follow up bug for it.