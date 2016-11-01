
# TDC Bug list by Firefox Programs: #
 - [TDC Resolved-Fixed for 52](https://mzl.la/2egjTCj)
 - [TDC Resolved-Fixed for 51](https://mzl.la/2c6nX6V)
 - [TDC Resolved-Fixed for 50](http://mzl.la/1Ye2Sbk)
 - [TDC Resolved-Fixed for 49](http://mzl.la/22eipYE)
 - [TDC Resolved-Fixed for 48](http://mzl.la/22eiVpB)

# Firefox #
- **_Content Handling_**
  - **Done**
      - [Bug 1289139](https://bugzilla.mozilla.org/show_bug.cgi?id=1289139) - Use SVG for the button icons in the Downloads Panel - **_Sean Lee_**
      - [Bug 1304680](https://bugzilla.mozilla.org/show_bug.cgi?id=1304680) - browser_downloads_panel_footer.js | Test timed out - after beta uplift simulation - **_Sean Lee_**
      - [Bug 1299712](https://bugzilla.mozilla.org/show_bug.cgi?id=1299712) - Use a new downloadTypeIcon in Summary Section of Downloads Panel - **_Sean Lee_**
      - [Bug 1298276](https://bugzilla.mozilla.org/show_bug.cgi?id=1298276) - Change the hover behavior in summary section with downloading file - **_Sean Lee_**
      - [Bug 1297657](https://bugzilla.mozilla.org/show_bug.cgi?id=1297657) - Correct the dropmarker design in Downloads Panel for RTL and plain style - **_Sean Lee_**
      - [Bug 1269962](https://bugzilla.mozilla.org/show_bug.cgi?id=1269962) - Implement the new features at "Show All Downloads" in Downloads panel. - **_Sean Lee_**
      - [Bug 1297039](https://bugzilla.mozilla.org/show_bug.cgi?id=1297039) - Implement the preference for showing dropmarker or not in Downloads Panel - **_Sean Lee_**
      - [Bug 950058](https://bugzilla.mozilla.org/show_bug.cgi?id=950058) - Split each download item so that all of the right part of it activates the action - **_KM Lee_**
      - [Bug 1282689](https://bugzilla.mozilla.org/show_bug.cgi?id=1282689) - Show an alert mark on badges if there are exceptional status to download files. - **_KM Lee_**

  - **Next**
      - [Bug 1282664](https://bugzilla.mozilla.org/show_bug.cgi?id=1282664) - Redesign the right-click menu for each item in downloads panel - **_Sean Lee_**
      - [Bug 1269958](https://bugzilla.mozilla.org/show_bug.cgi?id=1269958) - Change the summary section for Multiple Files information in Downloads Panel - **_Sean Lee_**
      - [Bug 1301384](https://bugzilla.mozilla.org/show_bug.cgi?id=1301384) - Unify the spacing and the progress bar styling in the Downloads Panel across platforms - **_KM Lee_**
      - [Bug 1269954](https://bugzilla.mozilla.org/show_bug.cgi?id=1269954) - Pop out download starting notification when a new download request is triggered - **_KM Lee_**

- **_Control Center_**
  - **Done** 
      - [Bug 1204007](https://bugzilla.mozilla.org/show_bug.cgi?id=1204007) - Cross out permission icons in the control center when they have been blocked - **_Fred Lin_**
      - [Bug 1193006](https://bugzil.la/1193006) - Show icons next to non-default permissions in the Permissions section of the Control Center - **_Fred Lin_**
      - [Bug 1206229](http://bugzil.la/1206229) - Inform the user that changes may require a page reload - **_Ricky Chien_**
      - [Bug 1291998](https://bugzilla.mozilla.org/show_bug.cgi?id=1291998) - Background color of cancel button in permission dropdown on Windows is distinct from OS X and Linux - **_Ricky Chien_**
      - [Bug 1203292](https://bugzilla.mozilla.org/show_bug.cgi?id=1203292) - Replace permissions dropdown with 'x' icon in Permissions main view in Control Center - **_Ricky Chien_**
 
  - **Next**

- **_Date-time Picker_**
  - **Done**
      - [Bug 1283385](https://bugzilla.mozilla.org/show_bug.cgi?id=1283385) - Implement UI for `<input type="date">` - **_Scott Wu_**
      - [Bug 1283384](https://bugzilla.mozilla.org/show_bug.cgi?id=1283384) - Implement UI for `<input type="time">` - **_Scott Wu_**
      - [Bug 1306251](https://bugzilla.mozilla.org/show_bug.cgi?id=1306251) - Rename form validation anchor to a more generic name for better reuse - **_Scott Wu_**

  - **Next**
      - [Bug 1301284](https://bugzilla.mozilla.org/show_bug.cgi?id=1301284) - Update picker style to match the visual spec for 'input type=time' - **_Scott Wu_**
      - [Bug 1309471](https://bugzilla.mozilla.org/show_bug.cgi?id=1309471) - [DateTimePicker] Add browser chrome test for time picker - **_Scott Wu_**

- **_DevTools_**
  - **Done**
      - [Bug 1274704](https://bugzilla.mozilla.org/show_bug.cgi?id=1274704) - Intermittent browser_responsiveui_touch.js | 300ms delay between touch events and mouse events should work - Got false, expected true | should not work - Got true, expected false - **_Dan Huang_**
      - [Bug 1273376](https://bugzilla.mozilla.org/show_bug.cgi?id=1273376) - Intermittent browser_responsiveui_touch.js | end event should work Got translate(20px, 10px), expected none - **_Dan Huang_**
      - [Bug 1295491](https://bugzilla.mozilla.org/show_bug.cgi?id=1295491) - Remove Reference() component in grip-array.js - **_Evan Tseng_**
      - [Bug 1289062](https://bugzilla.mozilla.org/show_bug.cgi?id=1289062) - Order the Event's properties - **_Evan Tseng_**
      - [Bug 1282465](https://bugzilla.mozilla.org/show_bug.cgi?id=1282465) - Reps: fix or remove recursive handling in ArrayRep and Obj rep - **_Evan Tseng_**
      - [Bug 1284838](https://bugzilla.mozilla.org/show_bug.cgi?id=1284838) - Reps: render events more uniformly - **_Evan Tseng_**
      - [Bug 1289912](https://bugzilla.mozilla.org/show_bug.cgi?id=1289912) - Can't scroll in JSON Viewer in Nightly - **_Evan Tseng_**
      - [Bug 1282791](https://bugzilla.mozilla.org/show_bug.cgi?id=1282791) - Reps: uninteresting props algorithm is wrong - **_Evan Tseng_**
      - [Bug 1286892](https://bugzilla.mozilla.org/show_bug.cgi?id=1286892) - Inspector sidebar tabs now have a bigger font-size - **_Evan Tseng_**
      - [Bug 1260382](https://bugzilla.mozilla.org/show_bug.cgi?id=1260382) - Storage inspector incorrectly tries to parse invalid localStorage JSON values - **_Fischer Liu_**
      - [Bug 1264582](https://bugzilla.mozilla.org/show_bug.cgi?id=1264582) - Table headers are not removed when selecting an empty storage - **_Fischer Liu_**
      - [Bug 1268444](https://bugzilla.mozilla.org/show_bug.cgi?id=1268444) - Convert network monitor to use new key shortcut API - **_Fred Lin_**
      - [Bug 1308440](https://bugzilla.mozilla.org/show_bug.cgi?id=1308440) - Migrate Net Panel Context Menu with framework/menu API in NetMonitor panel - **_Fred Lin_**
      - [Bug 1311614](https://bugzilla.mozilla.org/show_bug.cgi?id=1311614) - Move CustomRequestView to its own module - **_Fred Lin_**
      - [Bug 1311572](https://bugzilla.mozilla.org/show_bug.cgi?id=1311572) - Remove code associated with comments linking to bug 1265759 - **_Fred Lin_**
      - [Bug 1308500](https://bugzilla.mozilla.org/show_bug.cgi?id=1308500) - Migrate localization strings away from netmonitor.dtd - **_Fred Lin_**
      - [Bug 1309796](https://bugzilla.mozilla.org/show_bug.cgi?id=1309796) - add eslint support for netmonitor - **_Fred Lin_**
      - [Bug 1308503](https://bugzilla.mozilla.org/show_bug.cgi?id=1308503) - Migrate localization strings away from certManager.dtd - **_Fred Lin_**
      - [Bug 1292592](https://bugzilla.mozilla.org/show_bug.cgi?id=1292592) - sourceeditor uses xul - **_Fred Lin_**
      - [Bug 1304262](https://bugzilla.mozilla.org/show_bug.cgi?id=1304262) - Codemirror dialog does not work in inspector and scratchpad  - **_Fred Lin_**
      - [Bug 1291638](https://bugzilla.mozilla.org/show_bug.cgi?id=1291638) - change color theme of box-model view - **_Fred Lin_**
      - [Bug 1272364](https://bugzilla.mozilla.org/show_bug.cgi?id=1272364) - [rep tests] Ensure that ARIA presentation role is handled correctly in reps - **_Fred Lin_**
      - [Bug 1295161](https://bugzilla.mozilla.org/show_bug.cgi?id=1295161) - [RTL][networkmonitor] Collapse/Expand pane button is not properly displayed - **_Fred Lin_**
      - [Bug 1295081](https://bugzilla.mozilla.org/show_bug.cgi?id=1295081) - Fix inspector-searchinput-clear display behavior - **_Fred Lin_**
      - [Bug 1294937](https://bugzilla.mozilla.org/show_bug.cgi?id=1294937) - The context menu does not appear when right-click on the inspector-searchbox - **_Fred Lin_**
      - [Bug 1294929](https://bugzilla.mozilla.org/show_bug.cgi?id=1294929) - Don't hold "No matches" style, after clearing the "No matches" result using inspector-searchinput-clear - **_Fred Lin_**
      - [Bug 1294486](https://bugzilla.mozilla.org/show_bug.cgi?id=1294486) - Fix inspector textbox-search-clear position in RTL locales - **_Fred Lin_**
      - [Bug 1293591](https://bugzilla.mozilla.org/show_bug.cgi?id=1293591) - remove devtools/client/inspector/inspector.css - **_Fred Lin_**
      - [Bug 1286259](https://bugzilla.mozilla.org/show_bug.cgi?id=1286259) - Reps: grip-array rep should support limited preview - **_Fred Lin_**
      - [Bug 1265759](https://bugzilla.mozilla.org/show_bug.cgi?id=1265759) - Create an HTML replacement for Search Box - **_Fred Lin_**
      - [Bug 1264686](https://bugzilla.mozilla.org/show_bug.cgi?id=1264686) - Reps: Use grip-array rep to display NamedNodeMap - **_Fred Lin_**
      - [Bug 1285528](https://bugzilla.mozilla.org/show_bug.cgi?id=1285528) - [RTL] Collapse/Expand pane button is not properly displayed - **_Fred Lin_**
      - [Bug 1279526](https://bugzilla.mozilla.org/show_bug.cgi?id=1279526) - Firebug theme: fix CSS for rule view property - **_Fred Lin_**
      - [Bug 1285449](https://bugzilla.mozilla.org/show_bug.cgi?id=1285449) - Firebug theme - Don't apply inverted filter for sidebar-toggle, rewind-timeline, pause-resume-timeline in Inspector - **_Fred Lin_**
      - [Bug 1282427](https://bugzilla.mozilla.org/show_bug.cgi?id=1282427) - Reps: handle userDisplayName property on Function grips - **_Fred Lin_**
      - [Bug 1264701](https://bugzilla.mozilla.org/show_bug.cgi?id=1264701) - Move url utils to rep-utils.js - **_Fred Lin_**
      - [Bug 1284673](https://bugzilla.mozilla.org/show_bug.cgi?id=1284673) - Reps: add a cropLimit property to string rep - **_Fred Lin_**
      - [Bug 1272774](https://bugzilla.mozilla.org/show_bug.cgi?id=1272774) - some favicons are missing on about:debugging / tabs - **_Fred Lin_**
      - [Bug 1256767](https://bugzilla.mozilla.org/show_bug.cgi?id=1256767) - [ESLint] Fix ESLint errors/warnings in devtools/client/webconsole/console-commands.js - **_Fred Lin_**
      - [Bug 1266415](https://bugzilla.mozilla.org/show_bug.cgi?id=1266415) - about:debugging should display a warning if service workers are disabled - **_Fred Lin_**
      - [Bug 1274609](https://bugzilla.mozilla.org/show_bug.cgi?id=1274609) - replace uses of Ci.nsIDOMNodeFilter constants - **_Joseph Yeh_** 
      - [Bug 1279651](https://bugzilla.mozilla.org/show_bug.cgi?id=1279651) - The show-all button overlaps on inspector-breadcrumbs-toolbar - **_Joseph Yeh_**
      - [Bug 1268073](https://bugzilla.mozilla.org/show_bug.cgi?id=1268073) - Misleading error if you click "Debug" twice - **_Joseph Yeh_**
      - [Bug 967493](https://bugzilla.mozilla.org/show_bug.cgi?id=967493) - DevTools Inspector should display HTML Entities not evaluate them - **_Joseph Yeh_**
      - [Bug 1236283](https://bugzilla.mozilla.org/show_bug.cgi?id=1236283) - "object" and "embed" nodes in markup-view can always be expanded, even if they don't contain other nodes - **_Joseph Yeh_**
      - [Bug 1261133](https://bugzilla.mozilla.org/show_bug.cgi?id=1261133) - Style editor doesn't remove ".moz-styleeditor-transitioning" if I close it in the middle of transition, so there're infinite transitions - **_KM Lee_**
      - [Bug 1265686](https://bugzilla.mozilla.org/show_bug.cgi?id=1265686) - Add PgUp+PgDown+Home+End navigation in Performance Profiler treeview? - **_Luke Chang_**
      - [Bug 1263104](https://bugzilla.mozilla.org/show_bug.cgi?id=1263104) - Ctrl+F in Storage Inspector should open search - **_Luke Chang_**
      - [Bug 1309191](https://bugzilla.mozilla.org/show_bug.cgi?id=1309191) - Implement filter buttons for Net Panel Toolbar - **_Ricky Chien_**
      - [Bug 1308878](https://bugzilla.mozilla.org/show_bug.cgi?id=1308878) - Implement minimal Redux store for Net panel - **_Ricky Chien_**
      - [Bug 1290437](http://bugzil.la/1290437) - Fix and land the console netlogging tests - **_Ricky Chien_**
      - [Bug 1278923](https://bugzilla.mozilla.org/show_bug.cgi?id=1278923) - Exported HAR format is missing Content-Type and Content-Length headers - **_Ricky Chien_**
      - [Bug 1291618](https://bugzilla.mozilla.org/show_bug.cgi?id=1291618) - Fix dropmarker position of command-button-frames in RTL locales - **_Ricky Chien_**
      - [Bug 1102269](https://bugzilla.mozilla.org/show_bug.cgi?id=1102269) - [highlighter] infobar can be outside visible area - **_Ricky Chien_**
      - [Bug 1286283](https://bugzilla.mozilla.org/show_bug.cgi?id=1286283) - HTML ToolSidebar should support ARIA - **_Ricky Chien_**
      - [Bug 1229340](https://bugzilla.mozilla.org/show_bug.cgi?id=1229340) - Overflow scrollbar causes an offset between animations and the time header in the animation timeline - **_Ricky Chien_**
      - [Bug 1280791](https://bugzilla.mozilla.org/show_bug.cgi?id=1280791) - Don't apply min-width to the command-button-frames checkbox in firebug theme - **_Ricky Chien_**
      - [Bug 1273076](https://bugzilla.mozilla.org/show_bug.cgi?id=1273076) - Show more details in about:debugging#invalid-hash - **_Ricky Chien_**
      - [Bug 1268107](https://bugzilla.mozilla.org/show_bug.cgi?id=1268107) - Cannot use back in about:debugging after entering an invalid hash - **_Ricky Chien_**
      - [Bug 1308425](https://bugzilla.mozilla.org/show_bug.cgi?id=1308425) - Move Performance Statistics into its own module - **_Steve Chung_**
      - [Bug 1301042](https://bugzilla.mozilla.org/show_bug.cgi?id=1301042) - Firebug Theme - Make differences between checked style and unchecked style for toolbox-buttons - **_Steve Chung_**
      - [Bug 1296187](https://bugzilla.mozilla.org/show_bug.cgi?id=1296187) - Don't overlap inspector-searchinput-clear with text - **_Steve Chung_**
      - [Bug 1284855](https://bugzilla.mozilla.org/show_bug.cgi?id=1284855) - Reps: match spacing and brace placement in nested objects/arrays - **_Steve Chung_**
      - [Bug 1294464](https://bugzilla.mozilla.org/show_bug.cgi?id=1294464) - Don't overlap inspector-search and eyedropper, pane-toggle - **_Steve Chung_**
      - [Bug 1253327](https://bugzilla.mozilla.org/show_bug.cgi?id=1253327) - Fix direction of children-pointer in RTL - **_Steve Chung_**
      - [Bug 1295390](https://bugzilla.mozilla.org/show_bug.cgi?id=1295390) - Don't hold search result after clearing inspector-searchbox by inspector-searchinput-clear - **_Steve Chung_**
      - [Bug 1253323](https://bugzilla.mozilla.org/show_bug.cgi?id=1253323) - Fix direction of heap-tree-number in RTL - **_Steve Chung_**
      - [Bug 1294059](https://bugzilla.mozilla.org/show_bug.cgi?id=1294059) - Remove devtools/client/styleeditor/styleeditor.css and merge with devtools/client/themes/styleeditor.css - **_Steve Chung_**
      - [Bug 1205590](https://bugzilla.mozilla.org/show_bug.cgi?id=1205590) - [RTL] Waterfall twisty direction is wrong in RTL locales - **_Steve Chung_**
      - [Bug 1253330](https://bugzilla.mozilla.org/show_bug.cgi?id=1253330) - Fix heap-tree-item-field heap-tree-item-name inline style (margin-left) in RTL - **_Steve Chung_**
      - [Bug 1288341](https://bugzilla.mozilla.org/show_bug.cgi?id=1288341) - Don't overlap layout-expander in RTL Locales - **_Steve Chung_**
      - [Bug 1288401](https://bugzilla.mozilla.org/show_bug.cgi?id=1288401) - Inspector sidebar tabs are missing the :active styling - **_Steve Chung_**
      - [Bug 1287422](https://bugzilla.mozilla.org/show_bug.cgi?id=1287422) - Don't overlap font-showall button and scrollbar in the Font Inspector - **_Steve Chung_**
      - [Bug 1288996](https://bugzilla.mozilla.org/show_bug.cgi?id=1288996) - Replace float: inline-start before core fully support - **_Steve Chung_**
      - [Bug 1289827](https://bugzilla.mozilla.org/show_bug.cgi?id=1289827) - Waiting in netmonitor -> timings isn't visible on dark theme - **_Steve Chung_**
      - [Bug 1287391](https://bugzilla.mozilla.org/show_bug.cgi?id=1287391) - Wrong sidebar tabs direction in RTL locales with Firebug theme - **_Steve Chung_**
      - [Bug 1287371](https://bugzilla.mozilla.org/show_bug.cgi?id=1287371) - Tabs hover style was changed in firebug theme - **_Steve Chung_**
      - [Bug 1283522](https://bugzilla.mozilla.org/show_bug.cgi?id=1283522) - Reps: support -0 grip in number rep - **_Steve Chung_**
      - [Bug 1285530](https://bugzilla.mozilla.org/show_bug.cgi?id=1285530) - Reps: Off by one error in grip-array max length - **_Steve Chung_**

  - **Next**
      - [Bug 1309193](https://bugzilla.mozilla.org/show_bug.cgi?id=1309193) - Implement sidebar toggle button in Net Panel Toolbar - **_Fred Lin_**
      - [Bug 1309192](https://bugzilla.mozilla.org/show_bug.cgi?id=1309192) - Implement search filter in Net Panel Toolbar - **_Ricky Chien_**
      - [Bug 1307892](https://bugzilla.mozilla.org/show_bug.cgi?id=1307892) - Support network event update messages #196 - **_Ricky Chien_**
      - [Bug 1308440](https://bugzilla.mozilla.org/show_bug.cgi?id=1308440) - Migrate Net Panel Context Menu with framework/menu API in NetMonitor panel - **_Fred Lin_**
      
- **_Form Autofill_**
  - **Done**
     - [Bug 1300988](https://bugzilla.mozilla.org/show_bug.cgi?id=1300988) - Implement an API in the content process to fill a form with a specific form autofill profile using @autocomplete - **_Steve Chung_**
     - [Bug 1304322](https://bugzilla.mozilla.org/show_bug.cgi?id=1304322) - Refactor LoginStore.jsm to make it reusable for Form Autofill - **_Luke Chang_**

  - **Next**
     - [Bug 1309481](https://bugzilla.mozilla.org/show_bug.cgi?id=1309481) - Remove leftover code specific to Logins from JSONFile.jsm and add tests - **_Luke Chang_**
     - [Bug 1300990](https://bugzilla.mozilla.org/show_bug.cgi?id=1300990) - Implement an API in the parent process to decide which values of an autofill profile would be filled in which field - **_Luke Chang_**
     - [Bug 1016733](https://bugzilla.mozilla.org/show_bug.cgi?id=1016733) - Implement form auto-fill profile storage - **_Luke Chang_**
     - [Bug 1301544](https://bugzilla.mozilla.org/show_bug.cgi?id=1301544) - Define a schema and storage method for Form Autofill / Web Payment address profiles - **_Luke Chang_**

- **_Location Bar_**
  - **Done**
      - [Bug 1256074](https://bugzilla.mozilla.org/show_bug.cgi?id=1256074) - Always present a 'search' option, even location bar's contents are detected as URLs - **_Evan Tseng_**

- **_Mortar/PDF_**
  - **Done**
      - [Bug 1302335](https://bugzilla.mozilla.org/show_bug.cgi?id=1302335) - [jsplugins][UI] Implement a polyfill for drop-down menus - **_Luke Chang_**
      - [Bug 1287017](https://bugzilla.mozilla.org/show_bug.cgi?id=1287017) - [jsplugins][UI] Implement function of rotating PDF document clockwise/counterclockwise - **_Luke Chang_**
      - [Bug 1299399](https://bugzilla.mozilla.org/show_bug.cgi?id=1299399) - [jsplugins][UI] Implement scrolling feature - **_Luke Chang_**
      - [Bug 1299402](https://bugzilla.mozilla.org/show_bug.cgi?id=1299402) - [jsplugins][UI] Implement zoom-in and zoom-out buttons - **_Luke Chang_**

  - **Next**
      - [Bug 1299405](https://bugzilla.mozilla.org/show_bug.cgi?id=1299405) - [jsplugins][UI] Implement presentation mode - **_Luke Chang_**
      - [Bug 1306221](https://bugzilla.mozilla.org/show_bug.cgi?id=1306221) - [jsplugins][UI] Implement fitting types and the scaling drop-down menu - **_Luke Chang_**
      - [Bug 1299401](https://bugzilla.mozilla.org/show_bug.cgi?id=1299401) - [jsplugins][UI] Implement paging features - **_Luke Chang_**

- **_Password Manager_**
  - **Done**
      - [Bug 1302352](https://bugzilla.mozilla.org/show_bug.cgi?id=1302352) - browser_context_menu_iframe.js is skipped in e10s - **_Evan Tseng_**
      - [Bug 1277105](https://bugzilla.mozilla.org/show_bug.cgi?id=1277105) - Intermittent e10s browser_capture_doorhanger.js | Check the password changed - Got pass2, expected notifyp1 or Should only have 1 login - Got 0, expected 1 - **_Evan Tseng_**
      - [Bug 1288558](https://bugzilla.mozilla.org/show_bug.cgi?id=1288558) - Merge passwordManagerCommon.js into passwordManager.js - **_Steve Chung_**

  - **Next**
      - [Bug 1273871](https://bugzilla.mozilla.org/show_bug.cgi?id=1273871) - Intermittent passwordmgr/test/browser/browser_capture_doorhanger.js | This test exceeded the timeout threshold. It should be rewritten or split up. If that's not possible, use requestLongerTimeout(N), but only as a last resort. - **_Evan Tseng_**
      - [Bug 1257078](https://bugzilla.mozilla.org/show_bug.cgi?id=1257078) - Toggle selected password visibility in the manager with a button - **_Sean Lee_**

- **_Preferences_**
  - **Done**
      - [Bug 1305407](https://bugzilla.mozilla.org/show_bug.cgi?id=1305407) - Rename accesskeys in sync.dtd as .accesskey instead of .label.accesskey - **_Fischer Liu_**
      - [Bug 1130447](https://bugzilla.mozilla.org/show_bug.cgi?id=1130447) - Hide the password manager timeLastUsed column by default - **_Fischer Liu_**
      - [Bug 1028029](https://bugzilla.mozilla.org/show_bug.cgi?id=1028029) - Improve accesskeys in Sync pane of in-content preferences - **_Fischer Liu_**
      - [Bug 1120967](https://bugzilla.mozilla.org/show_bug.cgi?id=1120967) - Broken middle/right click on links via about:preferences pages - **_Fischer Liu_**
      - [Bug 1037166](https://bugzilla.mozilla.org/show_bug.cgi?id=1037166) - Convert the "Show Update History" dialog on advanced pane to be in-content - **_Fischer Liu_**
      - [Bug 1169704](https://bugzilla.mozilla.org/show_bug.cgi?id=1169704) - In-content preferences - Search tab - "One-click search engines" table remains highlighted after clicking elsewhere on the page - **_Fischer Liu_**
      - [Bug 1298872](https://bugzilla.mozilla.org/show_bug.cgi?id=1298872) - Text cropped and overflowed in advanced pane in-content dialogs - **_Joseph Yeh_**
      - [Bug 1049001](https://bugzilla.mozilla.org/show_bug.cgi?id=1049001) - Convert the certManager dialog to in-content - **_Joseph Yeh_**
      - [Bug 1184989](https://bugzilla.mozilla.org/show_bug.cgi?id=1184989) - Flipping preference through keyboard scrolls the tab as well - **_Joseph Yeh_**
      - [Bug 1036815](https://bugzilla.mozilla.org/show_bug.cgi?id=1036815) - Convert Advanced pane dialogs to be in-content - **_Joseph Yeh_**

  - **Next**
      - [Bug 1044586](https://bugzilla.mozilla.org/show_bug.cgi?id=1044586) - F5 key breaks about:preferences - **_Joseph Yeh_**
      - [Bug 1036595](https://bugzilla.mozilla.org/show_bug.cgi?id=1036595) - Convert the "Clear recent history" dialog on privacy page to be in-content - **_Joseph Yeh_**

- **_Private Browsing_**
  - **Done**
      - [Bug 1259340](http://bugzil.la/1259340) - New Private Browsing Window update - **_Ricky Chien_**
      - [Bug 1267434](http://bugzil.la/1267434) - Unnecessary whitespace displayed after aboutPrivateBrowsing.info.saved.emphasize in about:privatebrowing - **_Ricky Chien_**
      - [Bug 1267499](http://bugzil.la/1267499) - New Private Browsing start-page overflows off the window bottom (triggering a scrollbar) for totally-reasonable window sizes - **_Ricky Chien_**
      - [Bug 1269485](http://bugzil.la/1269485) - New Private Browsing start-page has white/gray-text-on-white-background, in overflowed area off the right side of the window - **_Ricky Chien_**

- **_Quality of Experience_**
  - **Done**
      - [Bug 1310073](https://bugzilla.mozilla.org/show_bug.cgi?id=1310073) - Tests for wikipedia.org - **_Evan Tseng_**
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
      - [Bug 1231701](https://bugzilla.mozilla.org/show_bug.cgi?id=1231701) - Ship an emoji font on Windows XP - **_Tim Chien_**

  - **Next**
      - [Bug 1310074](https://bugzilla.mozilla.org/show_bug.cgi?id=1310074) - Tests for yahoo.com - **_Evan Tseng_**
      - [Bug 1310075](https://bugzilla.mozilla.org/show_bug.cgi?id=1310075) - Tests for qq.com - **_Evan Tseng_**
      - [Bug 1177619](https://bugzilla.mozilla.org/show_bug.cgi?id=1177619) - Reader mode isn't offered on Blogger/Blogspot based blogs - **_Evan Tseng_**

- **_Video Controls_**
  - **Done**
      - [Bug 1312324](https://bugzilla.mozilla.org/show_bug.cgi?id=1312324) - Add test to confirm that fullscreen should(not) be available accordingly when video in an iframe - **_Ray Lin_**
      - [Bug 1303245](https://bugzilla.mozilla.org/show_bug.cgi?id=1303245) - add a test to confirm that video control show closed caption button when video has supported text track - **_Ray Lin_**
      - [Bug 1300805](https://bugzilla.mozilla.org/show_bug.cgi?id=1300805) - Disable WebVTT breaks some controls of the native media player - **_Ray Lin_**
      - [Bug 1293601](https://bugzilla.mozilla.org/show_bug.cgi?id=1293601) - [Fennec] The video controls are missing the time slider and show a random number at the start of video playback on YouTube - **_Ray Lin_**
      - [Bug 1291013](https://bugzilla.mozilla.org/show_bug.cgi?id=1291013) - Closed-caption button spacing is asymetric - **_Ray Lin_**
      - [Bug 1291009](https://bugzilla.mozilla.org/show_bug.cgi?id=1291009) - Closed-caption button fuzzy in hidpi mode - **_Ray Lin_**
      - [Bug 985915](https://bugzilla.mozilla.org/show_bug.cgi?id=985915) - [webvtt] The two rows subtitles are overlapped with video controls on mouse hover - **_Ray Lin_**
      - [Bug 887934](https://bugzilla.mozilla.org/show_bug.cgi?id=887934) - [webvtt] Update video controls to include options for closed captioning - **_Ray Lin_**

  - **Next**
      - [Bug 1302320](https://bugzilla.mozilla.org/show_bug.cgi?id=1302320) - add a test to confirm that video control show "noaudio" icon when video has no audio - **_Ray Lin_**
      - [Bug 1271765](https://bugzilla.mozilla.org/show_bug.cgi?id=1271765) - Visual refresh of media controls - **_Ray Lin_**

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
      - [Bug 754623](https://bugzilla.mozilla.org/show_bug.cgi?id=754623) - Name field of bookmarks saved via "Bookmark All Tabs" is empty when loading the tab is deferred - **_Scott Wu_** 
      - [Bug 1261234](https://bugzilla.mozilla.org/show_bug.cgi?id=1261234) - Insecure form action password form warning appears for trustworthy action URLs using HTTP - **_Sean Lee_**
      - [Bug 1191092](https://bugzilla.mozilla.org/show_bug.cgi?id=1191092) - InsecurePasswordUtils should handle |input type=password| outside of a form element - **_Sean Lee_**
      - [Bug 1243722](https://bugzil.la/1243722) - Wrong doorhanger when updating password on Facebook - **_Tim Chien_**
      - [Bug 1243729](https://bugzil.la/1243729) - Username is overwritten with a blank one when updating the password for a Twitter account - **_Tim Chien_**

- **_Others_**
  - **Done**
      - [Bug 1113581](https://bugzilla.mozilla.org/show_bug.cgi?id=1113581) - Artifact when editing a keyword, the keyword is displayed under the text-area - **_Fischer Liu_**
      - [Bug 1295151](https://bugzilla.mozilla.org/show_bug.cgi?id=1295151) - Install add-on should not show as a permission in the control center - **_Fred Lin_**
      - [Bug 1270321](https://bugzilla.mozilla.org/show_bug.cgi?id=1270321) - Ship remember password doorhanger visibility toggle - **_Fred Lin_**
      - [Bug 1273023](https://bugzilla.mozilla.org/show_bug.cgi?id=1273023) - Convert xpcshell-tests in toolkit/components/places/tests/bookmarks/test_385829.js to Bookmarks.jsm API - **_Fred Lin_**
      - [Bug 1275100](https://bugzilla.mozilla.org/show_bug.cgi?id=1275100) - browser_notifications_2.js is going to permafail when Gecko 49 merges to Aurora - **_Fred Lin_**
      - [Bug 1271201](https://bugzilla.mozilla.org/show_bug.cgi?id=1271201) - Convert xpcshell-tests in toolkit/components/places/tests/bookmarks/test_384228.js to Bookmarks.jsm API - **_Fred Lin_**
      - [Bug 1260718](https://bugzilla.mozilla.org/show_bug.cgi?id=1260718) - Switch to using plain promises instead of Promise.jsm in CustomizableUI code - **_Fred Lin_**
      - [Bug 1263557](https://bugzilla.mozilla.org/show_bug.cgi?id=1263557) -  Switch to use plain promise in CustomizeMode.jsm - **_Fred Lin_**
      - [Bug 1284172](https://bugzilla.mozilla.org/show_bug.cgi?id=1284172) - the indexedDB icon style shows a strange icon on Linux - **_Fred Lin_**
      - [Bug 1280525](https://bugzilla.mozilla.org/show_bug.cgi?id=1280525) - Search highlight (Ctrl + F) does not work properly when text is erased - **_Joseph Yeh_**
      - [Bug 1198279](https://bugzilla.mozilla.org/show_bug.cgi?id=1198279) - Closing Find Toolbar should clear all highlighted matches - **_Ray Lin_**
      - [Bug 1296128](http://bugzil.la/1296128) - (X) icon to remove permissions in control center doesn't have any indication its focused - **_Ricky Chien_**
      - [Bug 1288557](https://bugzilla.mozilla.org/show_bug.cgi?id=1288557) - Replace custom exceptions dialog (passwordManagerExceptions.xul) with usage of permissions.xul - **_Steve Chung_**
      - [Bug 1260276](https://bugzilla.mozilla.org/show_bug.cgi?id=1260276) - Reader mode messes with tab history when I navigate to article in reader mode (on facebook articles) - **_Tim Chien_**
      - [Bug 1277747](https://bugzilla.mozilla.org/show_bug.cgi?id=1277747) - Firefox freezes before restarting when I clicked the [Restart to Update...] button in about dialog - **_Tim Chien_**
      - [Bug 1266611](https://bugzilla.mozilla.org/show_bug.cgi?id=1266611) - Tab prompts can overlap in the same tab - **_Tim Chien_**

  - **Next**
      - [Bug 1000700](https://bugzilla.mozilla.org/show_bug.cgi?id=1000700) - menu-button dropmarkers aren't inverted with dark LWT - **_Scott Wu_**
      - [Bug 1217162](https://bugzilla.mozilla.org/show_bug.cgi?id=1217162) - Implement Contextual Feedback on Insecure Passwords - **_Sean Lee_**

# Fennec #

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

- **_Fennec Reader View_**
  - **Done**
       - [Bug 1272677](https://bugzilla.mozilla.org/show_bug.cgi?id=1272677) - Two parallel lines are displayed in "Aa" floating layout button in reader view - **_Dan Huang_**
       - [Bug 1276686](https://bugzilla.mozilla.org/show_bug.cgi?id=1276686) - Selection handles are displayed when tapping on the reader view toolbar - **_Ray Lin_**
