## 08/08 ~ 08/12 ##

* [Firefox]
  - Dev Tools
    - Bug 1284838 - Reps: render events more uniformly
      - review+
    - Bug 1282465 - Reps: fix or remove recursive handling in ArrayRep and Obj rep
      - review+
    - Bug 1289062 - Order the Event's properties
      - feedback+
  - Location Bar
    - Bug 1256074 - Always present a 'search' option, even location bar's contents are detected as URLs
      - Looking for the code determine location bar treat the string as an URL or a keyword.
  - Password Manager
    - Bug 1277105 - Intermittent e10s browser_capture_doorhanger.js | Check the password changed - Got pass2, expected notifyp1 or Should only have 1 login - Got 0, expected 1
      - Re-triggered the browser_capture_doorhanger.js test for 10 times. If they are all good, let's close the bug.
  - Form Autofill
    - Survey works
      - Read UX spec to understand what we want to do in the feature.
      - Can learn related tech knowledge from [Autofill Forms][autofill-forms].

[autofill-forms]: https://github.com/sarahavilov/Autofill-Forms
