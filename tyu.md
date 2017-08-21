Zerda
=============

Feature
-------------
* [Issue 46](https://github.com/mozilla-tw/Zerda/issues/46) - [Function] Search
  * WIP
  * Studied Fennec search suggestion

Feature: Bottom Sheet Architecure / Protocol
-------------

* [Issue 256](https://github.com/mozilla-tw/Zerda/issues/256) - Tap on browsing history should close the panel automatically
  * Merged [Pull Request 305](https://github.com/mozilla-tw/Zerda/pull/305) - Implement PanelFragment as a transaction to close ListPanelDialog from childrens

* [Issue 293](https://github.com/mozilla-tw/Zerda/issues/293) - [Smoke Test] Unable to switch to Screenshots tab
  * Merged [Pull Request 304](https://github.com/mozilla-tw/Zerda/pull/304) - Add temporary empty fragment as a placeholder for screenshot list

* [Issue 279](https://github.com/mozilla-tw/Zerda/issues/279) - [dogfooding] no fling effect on bottom sheet
  * Merged [Pull Request 299](https://github.com/mozilla-tw/Zerda/pull/299) - Block recyclerview nestedScrolling to enable fling.

* [Issue 281](https://github.com/mozilla-tw/Zerda/issues/281) - Align tab to UI spec
  * Merged [Pull Request 303](https://github.com/mozilla-tw/Zerda/pull/303) - Align panel tab UI with spec.

* [Issue 273](https://github.com/mozilla-tw/Zerda/issues/273) - [dogfooding] Full page history list will have white background in the top
  * Merged [Pull Request 301](https://github.com/mozilla-tw/Zerda/pull/301) - Remove redundant white backgrounds in Browsing History widgets

* [Issue 210](https://github.com/mozilla-tw/Zerda/issues/210) - Move History From own Activity to the shared ListPanelDialog panel
  * Merged [Pull Request 231](https://github.com/mozilla-tw/Zerda/pull/231) - Merge history into panel

* [Issue 238](https://github.com/mozilla-tw/Zerda/issues/238) - Gap between keyboard and website
  * Merged [Pull Request 287](https://github.com/mozilla-tw/Zerda/pull/287) - Truncate the Webview margin for toolbar when keyboard is shown

P0 / Crash / Architectural P1 bugs
-------------

* [Issue 316](https://github.com/mozilla-tw/Zerda/issues/316), [Issue 317](https://github.com/mozilla-tw/Zerda/issues/317), [Issue 318](https://github.com/mozilla-tw/Zerda/issues/318), [Issue 319](https://github.com/mozilla-tw/Zerda/issues/319) - Buddybuild crash report on build #417
  * Merged [Pull Request 320](https://github.com/mozilla-tw/Zerda/pull/320) - Add empty handler for three unlisted buttons

* [Issue 312](https://github.com/mozilla-tw/Zerda/issues/312) - icons in menu / panel does not have color on 5.0 devices
  * Merged [Pull Request 313](https://github.com/mozilla-tw/Zerda/pull/313) - Avoid using the API23 attribute drawableTint

* [Issue 308](https://github.com/mozilla-tw/Zerda/issues/308) - Zerda is crashing Gmail and some other Apps.
  * Merged [Pull Request 311](https://github.com/mozilla-tw/Zerda/pull/311) - Disable Custom Tab Service completely

* [Issue 238](https://github.com/mozilla-tw/Zerda/issues/238) - Gap between keyboard and website
  * Merged [Pull Request 291](https://github.com/mozilla-tw/Zerda/pull/291) - Restore marginBottom to original value after keyboard is dismissed

* [Issue 166](https://github.com/mozilla-tw/Zerda/issues/166), [Issue 255](https://github.com/mozilla-tw/Zerda/issues/255) - WebView resolution is larger than visible area
  * Merged [Pull Request 263](https://github.com/mozilla-tw/Zerda/pull/263) - Changing webview padding to reflect to new menu bar design

* [Issue 230](https://github.com/mozilla-tw/Zerda/issues/230) - Buddybuild crash report on build #303
  * Merged [Pull Request 235](https://github.com/mozilla-tw/Zerda/pull/235) - Fix bug #230
  * Merged [Pull Request 246](https://github.com/mozilla-tw/Zerda/pull/246) - Implement `safeForFragmentTransactions` flag (was `afterResume`) in a safer manner

* [Issue 253](https://github.com/mozilla-tw/Zerda/issues/253) - Missing onClick() for Menu/Download
  * Merged [Pull Request 254](https://github.com/mozilla-tw/Zerda/pull/254) - Add onClick() for Download button in menu

* [Issue 198](https://github.com/mozilla-tw/Zerda/issues/198) - Long page screenshot is not immediately shown in the Galleries.
  * Merged [Pull Request 225](https://github.com/mozilla-tw/Zerda/pull/225) - Change to correct parameter sequence in .scanFile()
