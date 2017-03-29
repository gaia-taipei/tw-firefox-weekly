## 03/20 - 03/24 ##

* [Firefox]
  - Project Photon
    - Plan the Preferences work
      - Discussed the design spec with the UX designer.
        - Mock-up for discussion: https://mozilla.invisionapp.com/share/5RA0R4HAE#/220667161_Reorg-Privacy_-_Security-Reorg_With_Permissions_1_Mac
        - Search: https://mozilla.invisionapp.com/share/ZDAGPK3AF#/218928219_1-0_Cover
        - Reorg: https://mozilla.invisionapp.com/share/P4ACQT1E3#/217167559_1-0_Cover
      - Figured out what is blocking the preferences telemetry work and asked the status.
        - The block bug: Bug 1335907 - Re-arrange sections in about:preferences according to updated spec
        - https://bugzilla.mozilla.org/show_bug.cgi?id=1335907#c57
      - Made of a breakdown of preferences telemetry work by the design spec.
        - Bug 1330552 - [Telemetry User Story] Preference
          - We will hav five main components to work.
            - Bug 1350267 - Telemetry for General page
              - Bug 1350284 - Telemetry for Performance settings section
                - We need to make sure we have all about:config preferences for each (Quantum) performance setting. 
            - Bug 1350268 - Telemetry for Downloads & Links page
            - Bug 1350269 - Telemetry for Firefox Account page
            - Bug 1350270 - Telemetry for Privacy & Security page
            - Bug 1350272 - Telemetry for Updates page
    - Figure out the OnBoarding work
      - Bug 1332774 - Onboarding tour bar for Mar 2017 funnelcake
        - Had a meeting, realized we will have a new design spec, and commented the situation.
          - https://bugzilla.mozilla.org/show_bug.cgi?id=1332774#c21
