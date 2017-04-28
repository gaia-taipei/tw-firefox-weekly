## 4/03 - 05/12 ##

### This Week ###

* [Photon Onboarding]
  - [WIP] 1054947 - "It looks like you haven't started Firefox in a while" message despite running Firefox daily
  - [r?] Bug 1335454 - Add the ablity to open advanced tab in the old Preferences through UITour
  - Bug 1354046 - [meta] Implement the Onboarding overlay
    - Got feedbacks from :Matt for the feedbacks on the architect/performance/file structures.
    - The patch implements
      - the UI,
      - interactions with user action,
      - onboarding tour navigation,
      - onboarding overlay toggle status,
      - highlighting buttons in hte hamburger menu,
      - interaction with the about:addons and about:newtab page,
      - about:config preferences control
  - Bug 1360109 - [UX] Auto-migration UX Spec
    - Bugs breakdown and technical feasibility discussion with Fred, Rex
    - Notes: https://docs.google.com/document/d/1NpPnW3HNsNV_j4V7baEZIZd_tI5JGF-pUKUtJHwDVuU/edit#heading=h.aaql59h4ka8n
  - Photon Workweek:
    - Discussed with Activity-Stream team on how to integrate the oboarding overlay and the auto-migration feature
    - Discussed with UX and PM on the onboarding overlay UI, the onboarding overlay specs, the auot-migration feature specs and the auto-refresh specs.
    - Discussed with Gijs, Matt on how to fix Fierfox profile refrsh time issue for the auto-refresh feature

* [Photon Preferences]
  - [r+] Bug 1358475 - Opening Preferences with subcategory on an existing Preferences page would result blank page
  - [r+] Bug 1360844 - Should test browserContainersGroup according to the pref state
  - [r+] Bug 1330315 - Add a telemetry probe to track how the Preferences are opened
  - Bugs breakdown and triage: Bug 1357285 - [meta] Preferences search
    - Dependency: https://bugzilla.mozilla.org/showdependencytree.cgi?id=1357285&hide_resolved=1

* [Storage Management]
  - [r+] Bug 1355795 - about:preferences#privacy is broken with browser.cache.offline.enable=false
  - [r+] Bug 1358381 - Fix Nightly-only enabled siteDataGroup testing issue beyond Beta build and reorganize tests to the proper test files
  - [r+] Bug 1349152 - Add Persistent-Storage permission in PermissionPrompts mozscreenshots
  - [r+] Bug 1358384 - Test the persistent-storage permission based on the pref-on/off state
  - [r+] Bug 1348733 - List sites using quota storage in Settings of Site Data
  - [review] Bug 1358160 - Get usage from observer subject instead of data field
  - The SV test plan review:
    - wiki: https://wiki.mozilla.org/QA/NewStorage
    - Test cases:
      - https://mail.google.com/mail/u/0/?ui=2&view=btop&ver=1czrat392q8rp#attid%253Datt_15bb27ac965ca6a9_0.1
      - https://docs.google.com/document/d/1a5m80ioJ_ncXENa8QKmBmIq3sDQ3-RJQg_s4d34d1mQ/edit

* [Brown Bag]
  - Let's talk about:preferences
    - enter about:preferences from inside FF/an external page
    - about:preferences structure, such as folders and url-to-paneId
    - About: redirecting
    - Logic of Prefernces search
    - Common used XUL components: preference, tree, richlistbox
    - Some useful testing help APIs while testing about:preferences
    - notification v.s prompt: diff between them, how to use, XUL bindings
    - Permission: see how a permission request goes from a web page to gecko to front-end permission UI, then back to gecko for saving
    - Origin Attributes: be careful when dealing with origin
    - SUMO "Learn more" link formatting
    - Some important thing about string formatting

### Last Week ###
* [Storage Management]
  - [r+] Bug 1309123 - Show persistent-storage permission request notification
  - [r+] Bug 1348252 - Disable buttons and display loading message in Site Data section while loading data
  - [r+] Bug 1352374 - Unexpectedly search on the pref-off Site Data section in Preferences
  - [r+] Bug 1354530 - Update the strings about Storage Manager according to the latest v1 specs

* [Preference]
  - [Review] Bug 1330315 - Add a telemetry probe to track how the Preferences are opened
  - [Review] Bug 1349051 - Split browser_advanced_siteData.js to browser_siteData.js and browser_siteData2.js since it was running too long.

* [Photon Onboarding]
  - Con-call meetings with UX: Verdi, EPM: Nicole to discuss about the project status and the next actions
  - Bugs breakdown and triage: Bug 1349422 - [meta] Photon - Improvements to First-Run Experience
    - Dependency: https://bugzilla.mozilla.org/showdependencytree.cgi?id=1349422&hide_resolved=1
