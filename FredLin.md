[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## 4/25 ~ 4/29

Firefox

- Bug 1011023 - Simplify test_bookmarks_restore_notification.js to use add_task
  - r+ & landed

- Bug 1256772 - eslint fix for devtools/client/webconsole/jsterm.js
  - r+ & landed

- Bug 522668 - Integrate PlacesDBUtils.checkAndFixDatabase() in about:support
  - r+ & landed

- Bug 1228258 - search aliases should be trimmed
  - r?

WebVR

- Discuss webVR workshop with yifan, daosheng
- Make demos for workshop
  - partial panorama http://gasolin.github.io/webvrdemo/ ,  http://gasolin.github.io/webvrdemo/teambuilding
  - 360camera http://gasolin.github.io/webvrdemo/360vr

- create aframe-href-component https://gasolin.github.io/aframe-href-component/
Make each object could be used as a normal html linkable element.

- aframe bugs fix
  - [doc fix] fix a-curvedimage doc https://github.com/aframevr/aframe/pull/1417
    - merged
  - [doc fix] organize a-light component/value table in right order  https://github.com/aframevr/aframe/pull/1418
    - merged
  - [doc fix] correct a-sky default value https://github.com/aframevr/aframe/pull/1419
    - merged
  - change default animation easing method as linear
  https://github.com/aframevr/aframe/pull/1421
    - merged
  - Compress images https://github.com/aframevr/aframe/pull/1424
    - merged
