## 1/16 - 1/20 Ricky Chien

### DevTools
* Netmonitor
 * Overall status of [Netmonitor MVP scope](https://wiki.mozilla.org/DevTools/Netmonitor)
* [Bug 1307892](https://bugzilla.mozilla.org/show_bug.cgi?id=1307892) - Support network event update messages 
 * r?
* [Bug 1329068](https://bugzilla.mozilla.org/show_bug.cgi?id=1329068) - Fix layout issue for PropertiesView
 * landed
* [Bug 1331821](https://bugzilla.mozilla.org/show_bug.cgi?id=1317651) - Details Panel covers most of the Network Monitor when docked on the side.
 * landed
* [Bug 1332151](https://bugzilla.mozilla.org/show_bug.cgi?id=1332151) - Fix layout issues for network monitor sidebar panels
 * landed

#### Netmonitor technical survey and discussions

* [Flux Standard Action (FSA)](https://groups.google.com/a/mozilla.com/forum/#!msg/netmonitor/CcIgCLLukVc/3lZtlJJgAwAJ)
* [Pass all state into connect() will kill any performance optimizations](https://groups.google.com/a/mozilla.com/forum/#!topic/netmonitor/Oq8MyZ7tfDk)
* [Focus on Properties View (bug 1328828)](https://groups.google.com/a/mozilla.com/forum/?utm_medium=email&utm_source=footer#!topic/netmonitor/UPK2o_ONsUE)

#### Request to performance tools
 * Set up a meeting with Taipei performance team and collected a list of features and requirements from them to figure out how to improve performance tools.
 * Deliver collected requirements to the members of devtools performance tool and figure out the project roadmap.

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

[Overview]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit?usp=sharing
[Meetings]: https://docs.google.com/a/mozilla.com/document/d/1FneFiHkLMJjWFhFYI13IWlr02W5mCRsEqZQPUJHWmSU/edit?usp=sharing
[Tasks]: https://docs.google.com/document/d/1NUiCCwDutuuNQhKXYnBFt28LX0qFIylgXwmxHeuRKtY/edit?usp=sharing
[Tracking Dashboard]: https://docs.google.com/spreadsheets/d/17BXGCnQ5AFew1BBhXXsBxP3G_JpyLMow8HjEcivvEZQ/edit?usp=sharing
[Groups]: https://groups.google.com/a/mozilla.com/forum/#!forum/netmonitor
[Meta Bug - Migrate Net panel to HTML]: https://bugzilla.mozilla.org/show_bug.cgi?id=1307743
[Mana project update]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Wiki]: https://wiki.mozilla.org/DevTools/Netmonitor
