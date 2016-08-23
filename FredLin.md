[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 8/15 ~ 8/19

Attend Coscup at 8/20~21.
Present about webby project, Slide https://hackmd.io/s/HJ7dfgVc#/

Devtools

- tab motion design (PLAN)
  - Helen (UX) sad she most wanted it than box-model view (Bug 1150496)
  - Review UI specs at Bug 1292054 - Polish sidebar style and add tab motion
    - found inspector, new debugger(on github), network monitor(xul) have sidebar tabs in 3 different implementation and places, so its not the work that should be done at this time.
  - hold study group to check how toolbox tab works, blocked by Bug 1245921 - Change toolbox tabs to HTML, taken by :miker
  - Therefore we told :pbro & :honza we will improve box-model view (Bug 1150496) first

- integrate new web console with rep (PLAN)
  https://github.com/devtools-html/gecko-dev/issues/195#issuecomment-239498136

- Bug 1294929 - remove no-match class when tap clear button
  - r+ & landed

- Bug 1294937 - The context menu does not appear when right-click on the inspector-searchbox
  - r+ & landed

- Bug 1286259 - Reps: grip-array rep should support limited preview
  - r+ & landed

- Bug 1291638 - change color theme of box-model view
  - updated color code
  - update highlighter.css
  - r?

- Bug 1295081 - Fix inspector-searchinput-clear display behavior
  - r?

- Bug 1294480 - inspector-searchbox focus behavior is gone
  - borrowed a windows machine to debug it
  - find windows input/ does not have blue-border when selected, which is different from xul textbox


Browser

- discuss form autocomplete with Luke, Steve, Evan (Tue Morning)


Toolkit

Shipped `remember password doorhanger visibility toggle` in 51

- Bug 1270321 - Ship remember password doorhanger visibility toggle
  - r+ & landed

- Bug 1190938 - password field staying selected under doorhanger
  - investigate and landed bernando's patch


Next Week

- Attend Modern Web 2016 at 8/24~25
- Come out Better Box Model Plan (For Sep~Oct) https://hackmd.io/s/H1sohXtq
