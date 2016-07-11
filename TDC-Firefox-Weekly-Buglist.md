

# TDC Bug list by Firefox Programs: #
 - [TDC Resolved-Fixed for 50](http://mzl.la/1Ye2Sbk)
 - [TDC Resolved-Fixed for 49](http://mzl.la/22eipYE)
 - [TDC Resolved-Fixed for 48](http://mzl.la/22eiVpB)

# Firefox #
- **_Content Handling_**
  - **Next**
      - [Bug 1269962](https://bugzilla.mozilla.org/show_bug.cgi?id=1269962) - Implement the new features at "Show All Downloads" in Downloads panel. - **_Sean Lee_**
      - [Bug 1269957](https://bugzilla.mozilla.org/show_bug.cgi?id=1269957) - Change the number of maximum download items displayed - **_Sean Lee_**
      - [Bug 1270012](https://bugzilla.mozilla.org/show_bug.cgi?id=1270012) - Show download complete animation on downloads button whenever a download is completed - **_KM Lee_**
      - [Bug 1270006](https://bugzilla.mozilla.org/show_bug.cgi?id=1270006) - Replace the downloads remaining time on the downloads button with a downloading icon - **_KM Lee_**

- **_Control Center_**
  - **Done** 
      - [Bug 1204007](https://bugzilla.mozilla.org/show_bug.cgi?id=1204007) - Cross out permission icons in the control center when they have been blocked - **_Fred Lin_**
      - [Bug 1193006](https://bugzil.la/1193006) - Show icons next to non-default permissions in the Permissions section of the Control Center - **_Fred Lin_**
 
  - **Next**
      - [Bug 1203292](https://bugzilla.mozilla.org/show_bug.cgi?id=1203292) - Replace permissions dropdown with 'x' icon in Permissions main view in Control Center - **_Ricky Chien_** 

- **_Date-time Picker_**
  - **Done**
      - [Bug 1283382](https://bugzilla.mozilla.org/show_bug.cgi?id=1283382) - Implement UI for <input type="month"> - **_Scott Wu_**

- **_DevTools_**
  - **Done**
      - [Bug 1274704](https://bugzilla.mozilla.org/show_bug.cgi?id=1274704) - Intermittent browser_responsiveui_touch.js | 300ms delay between touch events and mouse events should work - Got false, expected true | should not work - Got true, expected false - **_Dan Huang_**
      - [Bug 1273376](https://bugzilla.mozilla.org/show_bug.cgi?id=1273376) - Intermittent browser_responsiveui_touch.js | end event should work Got translate(20px, 10px), expected none - **_Dan Huang_**
      - [Bug 1272774](https://bugzilla.mozilla.org/show_bug.cgi?id=1272774) - some favicons are missing on about:debugging / tabs - **_Fred Lin_**
      - [Bug 1256767](https://bugzilla.mozilla.org/show_bug.cgi?id=1256767) - [ESLint] Fix ESLint errors/warnings in devtools/client/webconsole/console-commands.js - **_Fred Lin_**
      - [Bug 1266415](https://bugzilla.mozilla.org/show_bug.cgi?id=1266415) - about:debugging should display a warning if service workers are disabled - **_Fred Lin_**
      - [Bug 1279651](https://bugzilla.mozilla.org/show_bug.cgi?id=1279651) - The show-all button overlaps on inspector-breadcrumbs-toolbar - **_Joseph Yeh_**
      - [Bug 1268073](https://bugzilla.mozilla.org/show_bug.cgi?id=1268073) - Misleading error if you click "Debug" twice - **_Joseph Yeh_**
      - [Bug 967493](https://bugzilla.mozilla.org/show_bug.cgi?id=967493) - DevTools Inspector should display HTML Entities not evaluate them - **_Joseph Yeh_**
      - [Bug 1273076](https://bugzilla.mozilla.org/show_bug.cgi?id=1273076) - Show more details in about:debugging#invalid-hash - **_Ricky Chien_**
      - [Bug 1268107](https://bugzilla.mozilla.org/show_bug.cgi?id=1268107) - Cannot use back in about:debugging after entering an invalid hash - **_Ricky Chien_**

  - **Next**
      - [Bug 1264582](https://bugzilla.mozilla.org/show_bug.cgi?id=1264582) - Table headers are not removed when selecting an empty storage - **_Fischer Liu_**
      - [Bug 1260225](https://bugzilla.mozilla.org/show_bug.cgi?id=1260225) - Move inspector-related command buttons (eyedropper, rulers, screenshot, measurement) to the Inspector panel and enable them by default - **_Joseph Yeh_**
      - [Bug 1236283](https://bugzilla.mozilla.org/show_bug.cgi?id=1236283) - "object" and "embed" nodes in markup-view can always be expanded, even if they don't contain other nodes - **_Joseph Yeh_**
      - [Bug 1261133](https://bugzilla.mozilla.org/show_bug.cgi?id=1261133) - Style editor doesn't remove ".moz-styleeditor-transitioning" if I close it in the middle of transition, so there're infinite transitions - **_KM Lee_** 
      - [Bug 1265686](https://bugzilla.mozilla.org/show_bug.cgi?id=1265686) - Add PgUp+PgDown+Home+End navigation in Performance Profiler treeview? - **_Luke Chang_**
      - [Bug 1263104](https://bugzilla.mozilla.org/show_bug.cgi?id=1263104) - Ctrl+F in Storage Inspector should open search - **_Luke Chang_**
      - [Bug 1229340](https://bugzilla.mozilla.org/show_bug.cgi?id=1229340) - Overflow scrollbar causes an offset between animations and the time header in the animation timeline - **_Ricky Chien_**

- **_Private Browsing_**
  - **Done**
      - [Bug 1259340](http://bugzil.la/1259340) - New Private Browsing Window update - **_Ricky Chien_**
      - [Bug 1267434](http://bugzil.la/1267434) - Unnecessary whitespace displayed after aboutPrivateBrowsing.info.saved.emphasize in about:privatebrowing - **_Ricky Chien_**
      - [Bug 1267499](http://bugzil.la/1267499) - New Private Browsing start-page overflows off the window bottom (triggering a scrollbar) for totally-reasonable window sizes - **_Ricky Chien_**
      - [Bug 1269485](http://bugzil.la/1269485) - New Private Browsing start-page has white/gray-text-on-white-background, in overflowed area off the right side of the window - **_Ricky Chien_**

- **_Quality of Experience_**
  - **Done**
      - [Bug 1151200](https://bugzil.la/1151200) - User should be able to set margins widths in Reader mode **_Dan Huang_**
      - [Bug 1269521](https://bugzil.la/1269521) -  User should be able to set line height in Reader mode - **_Dan Huang_**
      - [Bug 1203481](https://bugzilla.mozilla.org/show_bug.cgi?id=1203481) - All dividers in the URL bar should have the same style - **_Ray Lin_**
      - [Bug 995758](https://bugzilla.mozilla.org/show_bug.cgi?id=995758) - Address bar doesn't capture focus if a new tab is created via Ctrl+T shortcut while in Customization mode - **_Ray Lin_**
      - [Bug 1269996](https://bugzil.la/1269996) - Reader mode page scroll position should be remembered - **_Tim Chien_**      
      - [Bug 1263760](https://bugzil.la/1263760) - TabSwitch[Done] does not fire when a dialog is opened bug caused by quirky behavior of nested event loop - **_Tim Chien_**
      - [Bug 1229727](https://bugzil.la/1229727) - Mac OS X full screen warning - **_Tim Chien_**
      - [Bug 1266372](https://bugzil.la/1266372) - Regression - The close reader mode button on page should behave the same as bug 1184950 - **_Tim Chien_**
      - [Bug 1184950](https://bugzil.la/1184950) - Leaving Reader Mode should not reload - **_Tim Chien_**
      - [Bug 1264805](https://bugzil.la/1264805) - Leaving Reader Mode should not reload on Fennec - **_Tim Chien_**
      - [Bug 1153393](https://bugzil.la/1153393) - Session restore should restore about:reader page scrolling - **_Tim Chien_**

  - **Next**  
      - [Bug 1231701](https://bugzilla.mozilla.org/show_bug.cgi?id=1231701) - Ship an emoji font on Windows XP - **_Tim Chien_**

- **_Video Controls_**
  - **Next**
      - [Bug 887934](https://bugzilla.mozilla.org/show_bug.cgi?id=887934) - [webvtt] Update video controls to include options for closed captioning - **_Ray Lin_**
      - [Bug 1281414](https://bugzilla.mozilla.org/show_bug.cgi?id=1281414) - [webvtt] Update the design of closed caption button icon - **_Ray Lin_**

  - **Done**
      - [Bug 985915](https://bugzilla.mozilla.org/show_bug.cgi?id=985915) - [webvtt] The two rows subtitles are overlapped with video controls on mouse hover - **_Ray Lin_**

- **_Good First Bug/Mentor Bug/Good Next Bug_**
  - **Done**
      - [Bug 1126967](https://bugzilla.mozilla.org/show_bug.cgi?id=1126967) - Improve the loading transition - **_Dan Huang_**
      - [Bug 920956](https://bugzilla.mozilla.org/show_bug.cgi?id=920956) - DevTools touch emulation: suppress regular mouse events, emulate 300ms delay - **_Dan Huang_**
      - [Bug 1229927](https://bugzilla.mozilla.org/show_bug.cgi?id=1229927) - Allow showHeartbeat to change the icon - **_Fischer Liu_**
      - [Bug 1174900](https://bugzilla.mozilla.org/show_bug.cgi?id=1174900) - Capture doorhanger password field should stay disabled for master password users - **_Fred Lin_**
      - [Bug 969443](https://bugzilla.mozilla.org/show_bug.cgi?id=969443) - Update CustomizableUI tests to yield on CustomizeMode.reset instead of gCustomizeMode.resetting - **_Fred Lin_**
      - [Bug 1217134](https://bugzilla.mozilla.org/show_bug.cgi?id=1217134) - Replace show password placeholder with conventional show password checkbox - **_Fred Lin_**
      - [Bug 1240727](https://bugzilla.mozilla.org/show_bug.cgi?id=1240727) - Capital letters keywords are not recognized when showing which of the search engine will be used in the next search - **_Fred Lin_**  
      - [Bug 1219495](https://bugzilla.mozilla.org/show_bug.cgi?id=1219495) - about:addons renders with huge "Server not found" page if you're offline, instead of placeholder content - **_Fred Lin_**
      - [Bug 1011023](https://bugzilla.mozilla.org/show_bug.cgi?id=1011023) - Simplify test_bookmarks_restore_notification.js to use add_task - **_Fred Lin_**
      - [Bug 1256772](https://bugzilla.mozilla.org/show_bug.cgi?id=1256772) - Fix ESLint issues in devtools/client/webconsole/jsterm.js - **_Fred Lin_**
      - [Bug 1228258](https://bugzilla.mozilla.org/show_bug.cgi?id=1228258) - One click search aliases should be trimmed - **_Fred Lin_**
      - [Bug 530999](https://bugzilla.mozilla.org/show_bug.cgi?id=530999) -  Login manager UI should show site favicons - **_Joseph Yeh_**
      - [Bug 925101](https://bugzilla.mozilla.org/show_bug.cgi?id=925101) - Remove legacy signons.txt files - **_Ray Lin_**
      - [Bug 1251863](http://bugzil.la/1251863) - Browser Console focuses wrong window when I close it after openning from Scratchpad - **_Ricky Chien_**
      - [Bug 446171](https://bugzilla.mozilla.org/show_bug.cgi?id=446171) - Name field of bookmarks saved via "Bookmark All Tabs" has "(null)" value if history is disabled or just in private browsing mode - **_Scott Wu_**
      - [Bug 1261234](https://bugzilla.mozilla.org/show_bug.cgi?id=1261234) - Insecure form action password form warning appears for trustworthy action URLs using HTTP - **_Sean Lee_**
      - [Bug 1191092](https://bugzilla.mozilla.org/show_bug.cgi?id=1191092) - InsecurePasswordUtils should handle |input type=password| outside of a form element - **_Sean Lee_**
      - [Bug 1243722](https://bugzil.la/1243722) - Wrong doorhanger when updating password on Facebook - **_Tim Chien_**
      - [Bug 1243729](https://bugzil.la/1243729) - Username is overwritten with a blank one when updating the password for a Twitter account - **_Tim Chien_**

  - **Next**
      - [Bug 285836](https://bugzilla.mozilla.org/show_bug.cgi?id=285836) - Make "Remove All Cookies Now" undoable - **_Scott Wu_**
      - [Bug 754623](https://bugzilla.mozilla.org/show_bug.cgi?id=754623) - Name field of bookmarks saved via "Bookmark All Tabs" is empty when loading the tab is deferred - **_Scott Wu_**

- **_Others_**
  - **Done**
      - [Bug 1273023](https://bugzilla.mozilla.org/show_bug.cgi?id=1273023) - Convert xpcshell-tests in toolkit/components/places/tests/bookmarks/test_385829.js to Bookmarks.jsm API - **_Fred Lin_**
      - [Bug 1275100](https://bugzilla.mozilla.org/show_bug.cgi?id=1275100) - browser_notifications_2.js is going to permafail when Gecko 49 merges to Aurora - **_Fred Lin_**
      - [Bug 1271201](https://bugzilla.mozilla.org/show_bug.cgi?id=1271201) - Convert xpcshell-tests in toolkit/components/places/tests/bookmarks/test_384228.js to Bookmarks.jsm API - **_Fred Lin_**
      - [Bug 1260718](https://bugzilla.mozilla.org/show_bug.cgi?id=1260718) - Switch to using plain promises instead of Promise.jsm in CustomizableUI code - **_Fred Lin_**
      - [Bug 1263557](https://bugzilla.mozilla.org/show_bug.cgi?id=1263557) -  Switch to use plain promise in CustomizeMode.jsm - **_Fred Lin_**
      - [Bug 1198279](https://bugzilla.mozilla.org/show_bug.cgi?id=1198279) - Closing Find Toolbar should clear all highlighted matches - **_Ray Lin_**
      - [Bug 1277747](https://bugzilla.mozilla.org/show_bug.cgi?id=1277747) - Firefox freezes before restarting when I clicked the [Restart to Update...] button in about dialog - **_Tim Chien_**
      - [Bug 1266611](https://bugzilla.mozilla.org/show_bug.cgi?id=1266611) - Tab prompts can overlap in the same tab - **_Tim Chien_**

  - **Next**
      - [Bug 1000700](https://bugzilla.mozilla.org/show_bug.cgi?id=1000700) - menu-button dropmarkers aren't inverted with dark LWT - **_Scott Wu_**
      - [Bug 1257078](https://bugzilla.mozilla.org/show_bug.cgi?id=1257078) - Toggle selected password visibility in the manager with a button - **_Sean Lee_**

# Fennec #

- **_Add-on Manager_**
  - **Next**
      - [Bug 1079504](https://bugzilla.mozilla.org/show_bug.cgi?id=1079504) - Improve about:addons if user has no add-ons installed - **_Ray Lin_**

- **_Fennec Video Control_**
  - **Done**
      - [Bug 1260304](https://bugzilla.mozilla.org/show_bug.cgi?id=1260304) - mediasource: prepended to the context menu of MSE videos - **_Ray Lin_**
      - [Bug 1065076](https://bugzilla.mozilla.org/show_bug.cgi?id=1065076) - Update icons for video controls - **_Ray Lin_**
      - [Bug 1250741](https://bugzilla.mozilla.org/show_bug.cgi?id=1250741) - Update video player spec - **_Ray Lin_**
      - [Bug 1267935](https://bugzilla.mozilla.org/show_bug.cgi?id=1267935) -  Video controls are not correctly scaled for several video types - **_Ray Lin_**

- **_Fennec about: pages_**
  - **Done**
       - [Bug 1198935](https://bugzilla.mozilla.org/show_bug.cgi?id=1198935) - Set about: pages header height to 48px - **_Ray Lin_**
       - [Bug 1091241](https://bugzilla.mozilla.org/show_bug.cgi?id=1091241) - Make add-on detail page look more like a detail page - **_Ray Lin_**

  - **Next**
      - [Bug 1086911](https://bugzilla.mozilla.org/show_bug.cgi?id=1086911) - Update style of about:firefox - **_Ray Lin_**
      - [Bug 1091237](https://bugzilla.mozilla.org/show_bug.cgi?id=1091237) - Show more information in add-ons detail view in about:addons - **_Scott Wu_**

- **_Fennec Reader View_**
  - **Done**
       - [Bug 1272677](https://bugzilla.mozilla.org/show_bug.cgi?id=1272677) - Two parallel lines are displayed in "Aa" floating layout button in reader view - **_Dan Huang_**
       - [Bug 1276686](https://bugzilla.mozilla.org/show_bug.cgi?id=1276686) - Selection handles are displayed when tapping on the reader view toolbar - **_Ray Lin_**

- **_Others_**
  - **Next**
       - [Bug 1188271](https://bugzilla.mozilla.org/show_bug.cgi?id=1188271) - "Import bookmarks and history" should be disabled or warn if no data is available - **_Dan Huang_**
