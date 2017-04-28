## Photon Preferences

* [Bug 1358394](https://bugzil.la/1358394) - preferences re-org - Report title
  * FIXED in Fx55
* [Bug 1330121](https://bugzil.la/1330121) - preferences re-org - checkbox width
  * review+'d. Waiting for bug 1357348.
* [Bug 1356507](https://bugzil.la/1356507) - preferences re-org - updater
  * feedback+'d. Waiting for bug 1330121.

## Firefox QX

* [Bug 1344431](https://bugzil.la/1344431) - Regression on Reader Mode button visibility
  * FIXED in Fx55, uplifted to Fx54/53
* [Bug 1319020](https://bugzil.la/1319020) - Update Emoji font from upstream
  * FIXED in Fx53, uplifted to Fx52/51
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

## Firefox (contextual insecure password warning)

* [Bug 1314478](https://bugzil.la/1314478) - Contextual Insecure Password Warning should show up for all username fields, even when there are no saved login
  * Fixed in Fx53, to be uplifted to Fx52
* [Bug 1318194](https://bugzil.la/1318194) - Saved logins sould be in the dropdown list for HTTP pages.
  * Fixed in Fx53, to be uplifted to Fx52
* [Bug 1317882](https://bugzil.la/1317882) - Incorrect autocomplete dropdown height.
  * Fixed in Fx53, to be uplifted to Fx52
* [Bug 1317284](https://bugzil.la/1317284) - Intermittent toolkit/components/passwordmgr/test/mochitest/test_password_field_autocomplete.html
  * Fixed in Fx53 by Sean, to be uplifted to Fx52

## Firefox
* [Bug 1327097](https://bugzil.la/1327097) - Proper fix to the hack below.
  * Has a WIP but need to figure out how pointer works in Gecko.
* [Bug 1273537](https://bugzil.la/1273537)
  * FIXED in Fx55, uplifted to Fx54/53/52/esr52
* [Bug 1338961](https://bugzil.la/1338961) - A hack in DOM event handling so range input works in video control
  * FIXED in Fx53, uplifted to Fx52
* [Bug 1316828](https://bugzil.la/1316828) - Drive by fix on reader mode narration speed
  * FIXED in Fx53 and uplifted to Fx51 & Fx52
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

## Firefox for Android
* [Bug 1303993](https://bugzil.la/1303993) - "Save Video" label when the file isn't a video
  * Quick drive-by fix, in Fx53

## Build

* [Bug 1292407](https://bugzilla.mozilla.org/show_bug.cgi?id=1292407) - Make sure artifact build finds topsrcdir
  * drive-by fix
  * FIXED in Fx51
* [Bug 1252976](https://bugzil.la/1252976) - Offer desktop artifact build in |mach bootstrap|
  * Address review comment on behave of the original contributor, follow-up with update on note
  * FIXED in Fx51

## HTML/Layout/DOM

* [Bug 570893](https://bugzil.la/570893) - Drive by fix on layout state to fix an annoy disabled state
  * FIXED in Fx53
