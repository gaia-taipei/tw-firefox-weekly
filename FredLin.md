[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 2/13 - 2/10

### Devtools#Netmonitor.html

- Honza wil come to Taipei at 3/20~24 to discuss Netmonitor related plan 

- netmonitor.html(deXUL netmonitor)
  - [on track](https://wiki.mozilla.org/DevTools/Netmonitor/Archive), current project estimate finish release is `Fx55`
  - Project summary in [Project document], [Mana page]
  - Bug solving status available on [Project Wiki]
  - **All MVP bugs completed**

- [Netmonitor UI analysis] (https://docs.google.com/document/d/1Z9J8uY4aGRB_BcsLKQCqwBaxXo9MuZEW3ClyVjQ2XfQ/edit)
  - add UI improvement proposals
    - custom request UI validation
    - Raw Headers
    - Service worker integration

- Bug 1314921 - Reduce number of top-level files in devtools/client/netmonitor/
  - PART 1 - move top-level files into utils; 
  - PART 2 - merge events.js into constants
  - r+ & landed
  
- Bug 1339686 - Convert MDN [learn more] link as a react component
  - r+ & landed

- Bug 1316291 - Rename the "requests-menu" CSS classes in netmonitor.css
  - PART 1:Rename the requests-menu CSS classes in netmonitor.css
  - PART 2:remove request-list elements with fixed IDs
  - PART 3:Remove toolbar elements with fixed IDs
  - r+

Review

- Bug 1336384 - Implement top level NetworkMonitor component
- Bug 1309826 - convert netmonitor xul to xhtml
- Bug 1340366 - Remove privilege APIs for har-builder, har-collector and clipboard


### Devtools#Debugger.html
  - Review Refactory from jlaster
    - [landed](https://github.com/gasolin/postcss-bidirection/pull/8)
  - support rules with non-bidirectional rules
    - [landed](https://github.com/gasolin/postcss-bidirection/commit/a491425b5f4d4578eb4ebd59f2b862c8b3e5ada1)
  - Support multiple selectors in a rule
    - [landed](https://github.com/gasolin/postcss-bidirection/commit/66330f51c31d005966205f325d9551c90732488f)


[Project document]: https://docs.google.com/document/d/19lyV04YtfX9X5ev2rhFeIuQPaVApgl8qdFpe4Rw4Np4/edit
[Mana page]: https://mana.mozilla.org/wiki/display/PM/Netmonitor+Project+Update
[Project Wiki]:  https://wiki.mozilla.org/DevTools/Netmonitor

