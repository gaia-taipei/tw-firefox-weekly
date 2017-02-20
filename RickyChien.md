## 2/13 - 2/17 Ricky Chien

### DevTools
* Netmonitor Overall
 * I did a survey and architecture anaysis for next migration scope. See plan and bug breakdown discussion in [Netmonitor next migration roadmap and breakdown](https://groups.google.com/a/mozilla.com/forum/#!topic/netmonitor/eZ2ROcOmiYI)
 * Overall status of [Netmonitor MVP scope]
* [Bug 1309183](https://bugzilla.mozilla.org/show_bug.cgi?id=1309183) - Replace XUL Splitter by SplitBox
 * Landed
* [Bug 1336384](https://bugzilla.mozilla.org/show_bug.cgi?id=1336384) - Implement top level NetworkMonitor component
 * Landed
 * The top level react component in Netmonitor. There is no any static XUL elements in netmonitor.xul.
* [Bug 1309826](https://bugzilla.mozilla.org/show_bug.cgi?id=1309826) - convert netmonitor xul to xhtml
 * Landed
 * de-XUL!! Converted netmonitor.xul -> netmonitor.xhtml
* [Bug 1340366](https://bugzilla.mozilla.org/show_bug.cgi?id=1340366) - Remove privilege APIs for har-builder, har-collector and clipboard
 * Landed
 * As part of de-chrome netmonitor
* [Bug 1340368](https://bugzilla.mozilla.org/show_bug.cgi?id=1340368) - Rewrite har-exporter and use WebAPIs instead
 * r?
 * As part of de-chrome netmonitor

#### Netmonitor technical survey and discussions

* [Flux Standard Action (FSA)](https://groups.google.com/a/mozilla.com/forum/#!msg/netmonitor/CcIgCLLukVc/3lZtlJJgAwAJ)
* [Pass all state into connect() will kill any performance optimizations](https://groups.google.com/a/mozilla.com/forum/#!topic/netmonitor/Oq8MyZ7tfDk)
* [Focus on Properties View (bug 1328828)](https://groups.google.com/a/mozilla.com/forum/?utm_medium=email&utm_source=footer#!topic/netmonitor/UPK2o_ONsUE)
* [Netmonitor next migration roadmap and breakdown](https://groups.google.com/a/mozilla.com/forum/#!topic/netmonitor/eZ2ROcOmiYI)

#### Netmonitor.html planning
 * High level plan overview [Overview]
 * Refactoring works will stick to bugzilla and replace xul to react component piece by piece
 * During last week, we made 3 meetings with EPM Marco to understand and settle up project management process. See [Tracking Dashboard] for more detials.
 * Create google groups for discussing gereral subjects which realtes to netmonitor [Groups]
 * Continue updating and discussing the refactoring strategy [Meetings] and tasks breakdown [Tasks] and filing new bugs for [Meta Bug - Migrate Net panel to HTML]
 * Current project forecast release date will be in release 56 [Mana project update]
 * please see also [Wiki] for more status about MVP scope, reserve work and release / iterations

### References
* [Overview]
* [Meetings]
* [Tasks]
* [Tracking Dashboard]
* [Groups]
* [Meta Bug - Migrate Net panel to HTML]
* [Mana project update]
* [Wiki]
* [Netmonitor MVP scope]

[Overview]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit?usp=sharing
[Meetings]: https://docs.google.com/a/mozilla.com/document/d/1FneFiHkLMJjWFhFYI13IWlr02W5mCRsEqZQPUJHWmSU/edit?usp=sharing
[Tasks]: https://docs.google.com/document/d/1NUiCCwDutuuNQhKXYnBFt28LX0qFIylgXwmxHeuRKtY/edit?usp=sharing
[Tracking Dashboard]: https://docs.google.com/spreadsheets/d/17BXGCnQ5AFew1BBhXXsBxP3G_JpyLMow8HjEcivvEZQ/edit?usp=sharing
[Groups]: https://groups.google.com/a/mozilla.com/forum/#!forum/netmonitor
[Meta Bug - Migrate Net panel to HTML]: https://bugzilla.mozilla.org/show_bug.cgi?id=1307743
[Mana project update]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Wiki]: https://wiki.mozilla.org/DevTools/Netmonitor
[Netmonitor MVP scope]: https://wiki.mozilla.org/DevTools/Netmonitor#MVP_Scope
