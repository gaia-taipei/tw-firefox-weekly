# Week of Jul 18, 2016

(Excluding management-related tasks)

## Firefox QX

* [Bug 1231701](https://bugzil.la/1231701) - Ship an Emoji font in Firefox
 * FIXED in Fx50
* [Bug 1266372](https://bugzil.la/1266372) - The close reader mode button on page should behave the same as bug 1184950
 * FIXED in Fx49.
 * Uplifted to Fx48.
* [Bug 1264805](https://bugzil.la/1264805) - Leaving Reader Mode should not reload on Fennec
 * FIXED in Fx48
* [Bug 1184950](https://bugzil.la/1184950) - Leaving Reader Mode should not reload
 * FIXED in Fx48
* [Bug 1229727](https://bugzil.la/1229727) - Mac OS X full screen warning
 * FIXED in Fx48

## Firefox

* [Bug 1260276](https://bugzil.la/1260276) - Dead reader mode page in session history
 * FIXED in Fx50
* [Bug 1277747](https://bugzil.la/1277747) - "Restarting..." label on the about dialog
 * FIXED in Fx50
* [Bug 1266611](https://bugzil.la/1266611) - Tab modal prompt should not overlap
 * FIXED in Fx49
* [Bug 1153393](https://bugzil.la/1153393) - Session restore should restore about:reader page scrolling
 * FIXED in Fx49
* [Bug 1269996](https://bugzil.la/1269996) - Reader mode page scroll position should be remembered
 * quick patch to remove unload listener and restore bfcache
 * FIXED in Fx49
* [Bug 1263760](https://bugzil.la/1263760) - TabSwitchDone does not fire when a dialog is opened
 * FIXED in Fx48
* [Bug 1243729](https://bugzil.la/1243729) - Username is overwritten with a blank one when updating the password for a Twitter account
 * FIXED in Fx48
 * Uplifted to Fx45/46/47
* [Bug 1243722](https://bugzil.la/1243722) - Wrong doorhanger when updating password on Facebook
 * FIXED in Fx48
 * Uplifted to Fx45/46/47

## Build

* [Bug 1292407](https://bugzilla.mozilla.org/show_bug.cgi?id=1292407) - Make sure artifact build founds topsrcdir
 * drive-by fix, FIXED in Fx51
* [Bug 1252976](https://bugzil.la/1252976) - Offer desktop artifact build in |mach bootstrap|
 * Address review comment on behave of the original contributor, follow-up with update on note, FIXED in Fx51
