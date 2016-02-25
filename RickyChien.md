## 02/01 ~ 02/24
[TV System]
* [Landed] [Bug 1250032](http://bugzil.la/1250032) - [Marketplace] Hint should show after the app finish loading
* [Landed] [Bug 1249533](http://bugzil.la/1249533) - Add to apps confirm dialog focus on cancel button by default
* [WIP] [Bug 1250798](http://bugzil.la/1250798) - [System Merge] A fake marketplace website for running integration test

[Build System] [RefactoringToNodejs#Milestone_1](https://wiki.mozilla.org/Gaia/Build/RefactoringToNodejs#Milestone_1)
* See above link, Scott and I finished almost all build scripts refactoring during this month.
* However, we encountered performance issue since requirejs and spawn process on node are slower than xpcshell. (~2.5 slower)
* Node is able to be turned on by default once we solve performance problem.
 
[Other]
* Mentor Scott Wu to refactor [Bug 1243351](http://bugzil.la/1243351) - Running scan-appdir.js on node.js
* [Review History](https://bugzilla.mozilla.org/page.cgi?id=review_history.html&requestee=rchien%40mozilla.com)

## 2015 Q4 Goals
1. Support TV 2.5 feature - Provide an ability to preview an app on Marketplace [[TV][2.5] Preview an app on Marketplace](https://bugzilla.mozilla.org/show_bug.cgi?id=1211400), as measured by implementation (completeness and stability of the feature)
2. To lift the restrictions for gaia developers to use third-party NPM packages, we'll continue and deliver detailed plan for [refactoring build system run-time to node.js](https://wiki.mozilla.org/Gaia/Build/RefactoringToNodejs), as measured by implementation progress. (This is a long term plan so this goal does not aim for shipping on this quarter.)
3. CI machines are able to run / switch multi-version node.js in order to support new gaia build (node.js v4.x) and testing framework (node.js v0.10.x), as measured by implementation progress. (This is a long term plan so this goal does not aim for shipping on this quarter.)
4. Investigate new Gaia build 2.0 - confidant with Gareth, as measured by planning progress.
5. Fix bugs of build system, as measured by blocker burn down and days of blocker turnarounds.

## 2015 Q3 Delivered
1. Investigated new configure of Gaia build 2.0 - confidant
2. Surveyed and do experiment for new Gaia build 2.0 - gaia-playground
3. Fixed bugs of build system
4. Fixed bugs of settings app and system app
5. Supported Academy NCU 2015 Program - Introduced Git, Github, Bugzilla, WebIDE and DevTools
