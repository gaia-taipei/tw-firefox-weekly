# [W03] Max Liu: 01/16 ~ 01/20


* [Fennec]

  - Bug 1320072 - Firefox doesn't integrate with Android's Web Search "Intent"
    - review+, landed

  - Bug 1029646 - RTL locale support in locale picker
    - review+, landed

  - Bug 1332258 - [RTL] Faded text sometimes becomes blank after scrolling
    - review+, landed

  - Bug 1326291 - [RTL] Align the domain name in the site info panel to the right
    - Root cause found, brewing solution

  - Bug 1333089 - RTL - The back arrow is pointing left instead of right on Android
    - Android framework(L:21) specific bug, still investigating root cause.


## TODO
  - Bug - [RTL] UrlBar layout abnormal on API 17 RTL context
    - Solution ready, file a bug for review/landing

  - Bug - [RTL] Home view pager not right to left
    - Replace ViewPager with RecyclerView, huge effort

  * Fennec HSR
    - Idle

  * Bug 942609 - [meta] Reduce Fennec's storage impact: APK and data
    - Idle

  * Bug 1212648 - [Meta] Support of Progressive Apps in Fennec
    - Idle


## Study
  - Localization build feedback from :ahunt
    - https://wiki.mozilla.org/Mobile/Fennec/Android/Multilocale_Builds


## Side Project
  - Single Hand Mode

  - Shell Scripting
    - multiple device deploy
    - locale switcher
    - adb wrapper
    - adbportforward, deploy to remote server

  * Development environment setup
    - install jdk
    - install pip/python-requests
    - install git/hg/git-cinnabar&helper/git-remote-hg
    - git clone hg::https://hg.mozilla.org/mozilla-central
    - ./mach bootstrap
    - install android-studio; Intel-VT; create VMs
    - setup adbportforward server
    - done
