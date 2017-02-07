## 01/23 - 01/26 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1259763 - Reader mode omits opening paragraph on CNN articles
        - (Sent a MozReview push to land in m-c, and got review+ at 2/6.)
        - Landed in GitHub.
        - Updated patch for review comments.
        - Wrote the patch and tests.
      - Bug 1323861 - Reader Mode displays "Failed to load article from page" on all Breitbart articles
        - Discussed solution with reviewer, and the conclusion is that we'll fix it in JSDOMParser not in xmlserializer.
      - Bug 1320231 - Missing paragraph from http://www.nytimes.com/2016/11/22/technology/facebook-censorship-tool-china.html
        - RESOLVED DUPLICATE of Bug 1300697
        - Ensure this could be fixed by Bug 1300697
      - Replied comments, set labels, and reproduced the issues for GitHub Issues And Bugzilla bugs
        - https://bugzilla.mozilla.org/show_bug.cgi?id=1218221#c2
        - https://github.com/mozilla/readability/issues/279#issuecomment-273074023
        - https://github.com/mozilla/readability/issues/293
        - https://github.com/mozilla/readability/issues/294#issuecomment-274419812
        - https://github.com/mozilla/readability/issues/295
        - https://github.com/mozilla/readability/issues/299
      - Made a future plan for Reader Mode
        - https://public.etherpad-mozilla.org/p/readability-js-plan
