# [W06~09] Max Liu: 02/06 ~ 03/03


* [Fennec]

  - Bug 1331995 - [RTL] On some occasions, the URL on the URL bar disappears
    - landed


  - Bug 1321981 - [RTL] Swiping gesture between Top Sites, Bookmarks and History in a New Tab is reversed
  - Bug 1337440 - [RTL] Top Sites list's items in the Activity Stream should start from the right
    - Experiment solution A: 3rd party library from Github
      - https://github.com/lsjwzh/RecyclerViewPager
      - Result: Failed, scrolling does not support RTL
    - Experiment solution B: hack on ViewPagerAdapter/TabStrip
      - Result: Success, but too dirty
    - Searching for alternative solutions


  - Bug - Integrate SearchActivity with CustomTab
    - Experiment hack part 1 done
      - Animation, ActionBar color
    - Experiment hack part 2 in progress
      - Custom MenuItem


  - Bug 1340973 - Developer's note for RTL  Support
    - Drafting


## TODO
  - Bug - [RTL] UrlBar layout abnormal on API 17 RTL context
    - Solution ready, file a bug for review/landing


  * Fennec A/B testing
    - Study how other component been A/B tested
      - Bug 1323952 - Add A/B experiment for compact tabs
    - Drafting A/B testing process/flow


  - Research on CI process for Gradle build
    - How Mozilla's build system works
      - https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/How_Mozilla_s_build_system_works
    - Upgrade support library to 25.*
    - Upgrade Android SDK to 25
    - Enhance gradle build process


  * Bug 942609 - [meta] Reduce Fennec's storage impact: APK and data
    - Idle


  * Bug 1212648 - [Meta] Support of Progressive Apps in Fennec
    - Idle


## Study
  - Localization build feedback from :ahunt
    - https://wiki.mozilla.org/Mobile/Fennec/Android/Multilocale_Builds


  - Android Sync
    -  http://goo.gl/JD20wQ


  - Fennec bug monitor process
   - Config Bugzilla to watch fennec components


## Side Project
  - Single Hand Mode
   - Idle


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


  * JimDB HowTO
    - Download JimDB & setup
    - Setup virtualenv to avoid Python version bug
    - modify mozconfig
    - build fennec with debug symbol
    - to be continued...
