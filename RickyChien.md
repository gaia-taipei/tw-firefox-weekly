## 1/9 - 1/13 Ricky Chien

### DevTools
* Quantum flow workweek updates
 * Participated Devtools meeting on Wednesday to ask and confirm my some of questions
   * (Greg) Cleopatra developers have been taking for a long time to collect feature requests and idea from platform engineers
   * (Greg) Implemention strategic will focus on delivering new features in Cleopatra and then replace current perf tools.
   * (Greg) Cleopatra migration will begin in Q3 ideally.
   * (Markus) There are some deliverable features has been picked up and documentation will be updated.
   * (Markus) We're looking forward to shipping those features in 2017 H1.
   * (Bryan) Quantum flow related support is P0.
   * (Bryan) P1 is aiming for major tooling refactor (Debugger, Network Monitor -> HTML) and Github + System Addon "ship fast"
   * (Bryan) New devtools UX is in hiring process.
   * (Jim) Devtools is supporting Chrome RDP and it can benefit Servo as well.

* Netmonitor
 * All sidebar panels are done. That's a great progress!
    * [Bug 1317648](https://bugzilla.mozilla.org/show_bug.cgi?id=1317648) Implement Header Panel - Ricky Chien
    * [Bug 1317649](https://bugzilla.mozilla.org/show_bug.cgi?id=1317649)	Implement Cookies Panel - Fred Lin
    * [Bug 1317650](https://bugzilla.mozilla.org/show_bug.cgi?id=1317650)	Implement Params Panel - Ricky Chien
    * [Bug 1317651](https://bugzilla.mozilla.org/show_bug.cgi?id=1317651)	Implement Response Panel - Ricky Chien
    * [Bug 1309187](https://bugzilla.mozilla.org/show_bug.cgi?id=1309187)	Implement Timings Panel - Ricky Chien
    * [Bug 1309188](https://bugzilla.mozilla.org/show_bug.cgi?id=1309188) Implement Security Panel - Ricky Chien
    * [Bug 1317659](https://bugzilla.mozilla.org/show_bug.cgi?id=1317659)	Implement Preview Panel - Ricky Chien
 * I've picked up next MVP tasks (Bug 1328197 - Implement details view and Bug 1317645 - Implement sidebar view).
 * I'm looking forward to finishing Sidebar migration on Feb.
   
* [Bug 1307892](https://bugzilla.mozilla.org/show_bug.cgi?id=1307892) - Support network event update messages 
 * r?
* [Bug 1328500](https://bugzilla.mozilla.org/show_bug.cgi?id=1328500) - Support input field when user clicks on cell for TreeView
 * landed
* [Bug 1328828](https://bugzilla.mozilla.org/show_bug.cgi?id=1328828) - Implement Properties View for reusing in network details panels
 * landed
* [Bug 1317650](https://bugzilla.mozilla.org/show_bug.cgi?id=1317650) - Implement Params Panel
 * landed
* [Bug 1317651](https://bugzilla.mozilla.org/show_bug.cgi?id=1317651) - Implement Response Panel
 * landed
* [Bug 1317648](https://bugzilla.mozilla.org/show_bug.cgi?id=1317648) - Implement Header Panel
 * landed

* Review [Bug 1317649](https://bugzilla.mozilla.org/show_bug.cgi?id=1317649) - Implement Cookies Panel

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
