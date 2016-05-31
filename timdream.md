# Week of May 30, 2016

(Excluding management-related tasks)

## Firefox QX

* [Bug 1231701](https://bugzil.la/1231701) - Ship an Emoji font in Firefox
 * Created a test suite for EmojiOne Mozilla font in https://github.com/mozilla/emojione-colr; all release-blocking defects are found and fixed.
 * Patch updated with about:license modification, need r+ from gerv.
 * (dependency; not my bug) Found [Bug 1270878](https://bugzil.la/1270878) - Crash on Win8 debug with `MOZ_BOUNDLE_FONTS` turned on.
  * FIXED by jkew
 * (dependency; not my bug) Found [Bug 1271536](https://bugzil.la/1271536) - CMAP parsing problem for FirefoxEmoji.ttf
  * FIXED by jkew
 * (dependency; not my bug) Found [Bug 1276594](https://bugzil.la/1276594) - FontConfig backend can't find characters on EmojiOne Mozilla font because there isn't b/w glyths encoded.
  * being worked on by jkew.
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
