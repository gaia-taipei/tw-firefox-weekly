# Week of May 9, 2016

(Excluding management-related tasks)

## Firefox QX

* [Bug 1231701](https://bugzil.la/1231701) - Ship an Emoji font in Firefox
 * Patch ready, UX/Visual/Product conformed their commitment of the Firefox Emoji font.
 * Crashed on Win8 debug builds on a assertion failure. Will seek help and try to reproduce locally -- this is now bug 1270878.
* [Bug 1270878](https://bugzil.la/1270878) - Crash on Win8 debug with `MOZ_BOUNDLE_FONTS` turned on.
 * Reproduced locally on a borrowed machine; johathan give out a fix.
 * Font don't show up even if the app stops crashing -- this is bug 1271536.
* [Bug 1271536](https://bugzil.la/1271536) - CMAP parsing problem for FirefoxEmoji.ttf
 * Different `cmapLen` when loaded locally or remotely. Need time to figure out the root cause.
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
