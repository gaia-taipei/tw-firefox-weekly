## 12/13 - 12/16 ##

* [Firefox]
  - QX
    - Reader Mode
      - Bug 1285543 - Different Yahoo News article title and content is displayed when using Reader Mode
        - Landed in m-c.
        - Wrote a patch and discussed it with reviewer.
      - Bug 1142312 - Unexpected reader view output when viewing random Yahoo article
        - Landed in m-c.
        - Wrote a patch and discussed it with reviewer.
      - Bug 1167568 - Reader View displays only the first part of specific articles from ehow.com
        - Discussed the patch with reviewer.
      - Review patches
        - [Pull 331][pull-331] - Clean <input>,<textarea>,<select>,<button> elements
        - [Pull 332][pull-332] - Use jsdom for parsing the document to determine readability (fixes #325)
      - Bug 1324630 - [meta] Readability algorithm improvements for top websites
        - We'll focus on and fix the bugs first, then we could start to consider to enable reader mode button for more websites.
        - Filed a bug to list reader mode result issues for top websites.

  - Hawaii All Hands
    - Discussed Reader Mode Plan with Gijs
      - Main conclusions
        - Focus reader mode result issues of [top websites] first, then we could try to enable reader mode button for more website.
        - Adding user feedback feature is a good idea, we could plan and implement it in the future. But now we need to focus on top websites issues first.
    - Evan Tseng is one of collaborators of [Readability.js][readability-js] now.

[pull-331]: https://github.com/mozilla/readability/pull/331
[pull-332]: https://github.com/mozilla/readability/pull/332
[top-websites]: http://www.alexa.com/topsites
[readability-js]: https://github.com/mozilla/readability
