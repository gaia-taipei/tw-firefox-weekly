### Last week

* [Form Fill]
  - [LANDED][Bug 1349489] The fixtures are updated, but we need to wait for legel review.
  - [LANDED][Bug 1347176] Improve findLabelElements function to satisfy W3C spec.
  - [r?][Bug 1349490] The part 1 got r+. Part 2 is waiting for review. We alos did Talos performance test for the whole Form Autofill feature.
  - [r?][BUg 1360370] Select elements can be detected in the latest patch including country, state fields.
  - [Bug 1360374] Any input fields added after DOMContentLoaded should be detected as well. We are going to use focusin event.
  - [Bug 1361237] WIP patch of Credit Card heuristics is ready. Need a little tweaks for the targeting websites.
  - [Bug 1361241] Implement Update operation for Sync Engine.
  - [Bug 1361242] Implement Prefer operation for Sync Engine.

* [Form Fill V.S. Sync WorkWeek]
  - [Please FormAutofill section for meeting minutes](https://docs.google.com/document/d/1VHgs4QGKEOIoWUsrCpQOHvClsGsa0Gg61eLrH7hxdn4/edit#heading=h.d8reqog20rbw)
  - Summary of this WW for FormAutofill
    - Confirm the scope of the sync feature
      - We will work on Sync features for both Profile and Credit Card.
    - Discuss how to divide up tasks and work together
      - Sync Team: Sync Engine, Firefox Account perference page, Preferences[Sync Section], Any _sync properties in ProfileStorage.
      - FormAutofill Team: Preferences[Privacy and Security], Onboarding UI[DoorHander], ProfileStorage[Update/Prefer/Migration]
    - Decide a migration strategy of the storage
      - Please see the meeting minutes.
    - Come up with a guideline for both side to update the schema if needed
      - Please see the meeting minutes.

* [Password Manager]
  - [Bug 1257078] Pending for waiting Bug 451955.
  - [r?][Bug 451955] Waiting for review.

### This week

* [Form Fill]
  - [Bug 1349490] Working on this bug.
  - [Bug 1360370] Working on this bug.
  - [Bug 1360374] Working on this bug.
  - [Bug 1361237] Working on this bug.

* [Password Manager]
  - [Bug 1257078] Improve selection restoring feature.
  - [Bug 451955] Working on this bug.
