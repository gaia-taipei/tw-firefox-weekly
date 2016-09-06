## 08/29 ~ 09/02 ##

* [Firefox]
  - QX
    - Finished the cuts-control[1] and cuts-tabs[2] meta bugs.
    - Added into QX list
      - Bug 565993 - List shortcuts in Menus (especially context menus)
      - Bug 612228 - Move Reload/Bookmark All Tabs to the List All Tabs menu
    - Duplicate of another issue
      - Bug 566528 - Autofill button for Firefox forms
    - Closed the invalid issues
      - Bug 565764 - Scrollbar gets too small to use on long pages
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - After investigated, we could add two `richlistitem` elements(moz-action:visiturl and moz-action:searchengine ones) on the `#PopupAutoCompleteRichResult` panel when the `moz-action` is `visiturl`.
      - Sent an email to Stephen for UI review.
  - Password Manager
    - Bug 1277105 - Intermittent e10s browser_capture_doorhanger.js | Check the password changed - Got pass2, expected notifyp1 or Should only have 1 login - Got 0, expected 1
      - Investing why `fieldValues.username`[3] is null after the code `userField.value = "notifyu1";`[4] already assigned the value.

* [Fennec]
  - Bug 1280184 - Android: uninstalling firefox will delete all downloaded files, very annoying
    - On Z3C, downloaded files are always stored in "internal storage" even a sd card is inserted. On Android, the internal storage files are always removed after the app is uninstalled[5].

[1]: https://bugzilla.mozilla.org/show_bug.cgi?id=565512
[2]: https://bugzilla.mozilla.org/show_bug.cgi?id=565515
[3]: http://searchfox.org/mozilla-central/source/toolkit/components/passwordmgr/test/browser/browser_capture_doorhanger.js#74
[4]: http://searchfox.org/mozilla-central/source/toolkit/components/passwordmgr/test/browser/subtst_notifications_1.html#17
[5]: https://developer.android.com/training/basics/data-storage/files.html
