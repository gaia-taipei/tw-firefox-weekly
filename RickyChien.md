## 11/03 - 11/07

###DevTools
* [Bug 1307892](https://bugzilla.mozilla.org/show_bug.cgi?id=1307892) - Support network event update messages 
 * Move [#196](https://github.com/devtools-html/gecko-dev/issues/196) from github to bugzilla
 * new issue fixed because of missing stubPacket keys for enzyme testing.
 * r?
* [Bug 1309191](https://bugzilla.mozilla.org/show_bug.cgi?id=1309191) - Implement filter buttons in Net Panel Toolbar
 * This bug is a vital best practice for introducing react + redux into filter buttons. Following reactoring will depend on & reference this one.
 * landed
* [Bug 1309194](https://bugzilla.mozilla.org/show_bug.cgi?id=1309194) - Implement summary info in Net Panel Toolbar
 * WIP
* [Bug 1308507](https://bugzilla.mozilla.org/show_bug.cgi?id=1308507) - Remove all usages of nsIURL and NetworkHelper
 * r-
* Netmonitor.html planning
 * High level plan overview [Overview]
 * Refactoring works will stick to bugzilla and replace xul to react component piece by piece
 * During last week, we made 3 meetings with EPM Marco to understand and settle up project management process. See [Tracking Dashboard] for more detials.
 * Create google groups for discussing gereral subjects which realtes to netmonitor [Groups]
 * Continue updating and discussing the refactoring strategy [Meetings] and tasks breakdown [Tasks] and filing new bugs for [Meta Bug - Migrate Net panel to HTML]

### References
* [Overview]
* [Meetings]
* [Tasks]
* [Tracking Dashboard]
* [Groups]
* [Meta Bug - Migrate Net panel to HTML]

[Overview]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit?usp=sharing
[Meetings]: https://docs.google.com/a/mozilla.com/document/d/1FneFiHkLMJjWFhFYI13IWlr02W5mCRsEqZQPUJHWmSU/edit?usp=sharing
[Tasks]: https://docs.google.com/document/d/1NUiCCwDutuuNQhKXYnBFt28LX0qFIylgXwmxHeuRKtY/edit?usp=sharing
[Tracking Dashboard]: https://docs.google.com/spreadsheets/d/17BXGCnQ5AFew1BBhXXsBxP3G_JpyLMow8HjEcivvEZQ/edit?usp=sharing
[Groups]: https://groups.google.com/a/mozilla.com/forum/#!forum/netmonitor
[Meta Bug - Migrate Net panel to HTML]: https://bugzilla.mozilla.org/show_bug.cgi?id=1307743
