## 08/15 ~ 08/19 ##

* [Fennec]
  - Bug 1280184 - Android: uninstalling firefox will delete all downloaded files, very annoying
    - Still don't know why files are removed after uninstall the app. We use `Environment.getExternalStoragePublicDirectory` to store our downloaded files. Maybe we have code somewhere to delete them?
  - Bug 1295018 - Android's Keyboard shouldn't learn new words when Private Tab is opened
    - The issue might not to be resolved because "Use autocomplete but do not learn from this input" might be not possible.

* [Firefox]
  - Dev Tools
    - Bug 1289062 - Order the Event's properties
      - review+
    - Bug 1295491 - Remove Reference() component in grip-array.js
      - landed
    - Bug 1284838 - Reps: render events more uniformly
      - landed
    - Bug 1282465 - Reps: fix or remove recursive handling in ArrayRep and Obj rep
      - landed
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - After investigated, we could add two `richlistitem` elements(moz-action:visiturl and moz-action:searchengine ones) on the `#PopupAutoCompleteRichResult` panel when the `moz-action` is `visiturl`.
  - Password Manager
    - Bug 1277105 - Intermittent e10s browser_capture_doorhanger.js | Check the password changed - Got pass2, expected notifyp1 or Should only have 1 login - Got 0, expected 1
      - The intermittent failures might be related with [`_searchLogins`][storage-json.js] method in `storage-json.js` file.
  - Form Autofill
    - Implemented a [workable prototype add-on][form-autofill] to autofill forms.

[form-autofill]: https://github.com/evanxd/form-autofill
[storage-json.js]: http://searchfox.org/mozilla-central/source/toolkit/components/passwordmgr/storage-json.js#282
