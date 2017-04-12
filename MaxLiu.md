# [W13~14] Max Liu: 03/27 ~ 04/07


* [Fennec]
  - Sec-Bug
    - review+, sec-approval+, landing


  - Bug 1340973 - Developer's note for RTL  Support
    - First draft done
    - material collecting, drafting for MDN version.


  - Bug 1354973 - IllegalStateException in RtlViewPager
    - review?


  - Bug 1347103 - NullPointerException implicit type conversion
    - research for real root cause


  - Bug 1337425 - RTL activity-stream welcome highlights missing
    - root cause found, patch brewing


## TODO
  - Photon on Android
    - First mock on tablet


  - Fennec A/B testing
    - Study how other component been A/B tested
      - Bug 1323952 - Add A/B experiment for compact tabs
    - Drafting A/B testing process/flow


  - Research on CI process for Gradle build
    - How Mozilla's build system works
      - https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/How_Mozilla_s_build_system_works
    - Mostly done by Sebastian
    - Research on verify the diff of two build output
      - AndroidManifest.xml
      - classes.dex
      - resources.arsc
      - others
  - Build failed on latest android build tools
    - Bug 1338629 - No rule to make target `[...]/tools/lib/lint-checks.jar', needed by `annotationProcessors.jar'.
      - fixed by :ahunt
    - Research to stabilize build environment


  * Bug 942609 - [meta] Reduce Fennec's storage impact: APK and data
    - While working on Gradle build, ArscBlamer output raise alert on resource sparse problem


  * Bug 1212648 - [Meta] Support of Progressive Apps in Fennec
    - Idle


## Study
  - Localization build feedback from :ahunt
    - https://wiki.mozilla.org/Mobile/Fennec/Android/Multilocale_Builds


  - Android Sync
    -  http://goo.gl/JD20wQ


  - Fennec bug monitor process
    - Config Bugzilla to watch fennec components
    - How to monitor more efficiently?


## Side Project
  - Single Hand Mode
   - Photon approach, planning prototype before workweek


   - Bug - Integrate SearchActivity with CustomTab
     - Experiment hack part 1 done
       - Animation, ActionBar color
     - Experiment hack part 2 in progress
       - Custom MenuItem


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
