[Open bugs assigned to me](https://bugzilla.mozilla.org/buglist.cgi?quicksearch=assignee%3Agasolin%40mozilla.com) (ASSIGNED = current working on; NEW = backlog)

## Q4 2017

### Onboarding

Telemetry (follow-up to Photon 57)

* Could query daily overlay usage by new/update user in v57 (done)
  - https//sql.telemetry.mozilla.org/queries/48942
  - Bug 1389424 - Integrate ping-centre in onboarding addon to send ping events
  - Bug 1412164 - add new tour_type and timestamp column for onboarding telemetry

* Discuss new requirements with PM/UX/ENG (done)
  - https://docs.google.com/spreadsheets/d/1BQzncwklWZvvkLtbLaYO2unMG3Tw9LQX-c6XXqmYTUo/edit#gid=1665623309
* Get consensus for the new telemetry events/columns (done)
  - https://docs.google.com/spreadsheets/d/1BQzncwklWZvvkLtbLaYO2unMG3Tw9LQX-c6XXqmYTUo/edit#gid=1665623309
* Coordinate the data review/server side table update (done)
* Task breakdown and implement onboarding new telemetry (P1/P2, wip)
    * Bug 1418191 - Should not send the CTA telemetry event ping when tours have no CTA button (r+ & landed)
    * Bug 1418167 - validate data before send for onboarding telemetry (r+ & landed)
    * Bug 1417769 - collect onboarding-noshow-smallscreen and overlay-disapear-resize event for onboarding telemetry
      - data review+
      - PR ready
    * Bug 1413830 - Data schema change got data review
      - data review+
      - r?

* Help Cindy(PM) build the redash board, update queries to do meaningful analytics (done)
  - https://sql.telemetry.mozilla.org/dashboard/onboarding

Modularization

*  Discuss requirements with PM and UX & evaluate the efforts (done)
  - https://docs.google.com/document/d/1LYx_zy2c4eibwdikxx1IJIv7R-dDqJhwxJ8M9pOw5C4/edit
* Implemented related Modularization features and document them  (done)
  - Bug 1404193 - make Onboarding more configurable
  - Bug 1404193 - enable customizable logo, speech bubble string, and hide the skip button
  - Bug 1409977 - mark Onboarding tour will set as completed instantly via dataset
  - https://github.com/mozilla/gecko-dev/tree/master/browser/extensions/onboarding#customizable-preferences
* Cindy agreed we have completed modulization goal for Q4 (allow pref flipping on onboarding elements) (done)
  - https://docs.google.com/document/d/1LYx_zy2c4eibwdikxx1IJIv7R-dDqJhwxJ8M9pOw5C4/edit?disco=AAAABam-VgY
* Come out the proposal to use goFaster for modulization phase II (allow update layout/cta actions off cycle) (wip)


Shield studies as needed

* DIscuss with PM & UX to clarify the experiment priority and the required customization - chosen to do the onboarding notification experiment (done)
  - https://docs.google.com/document/d/1-czDviCKbNIlyHpkuwKm_nz8_GJ8VRRcJ4fjImr_XHU/edit
* Evaluate several experiment possibilities (perf flip, shield study) and choose shield study to fulfill UX requirement to flip the pref within the first 5 minutes (done)
* Create v57 compatible shield study addon for the experiment (done)
  - https://github.com/mozilla/shield-onboarding/
  - got QA verified https://public.etherpad-mozilla.org/p/onboarding_shield_QA
  - https://bugzilla.mozilla.org/show_bug.cgi?id=1420373

### Devtools#Netmonitor.html

- performance

![Imgur](https://i.imgur.com/RZBavjh.png)
We reduced Requests finished time from 9.6s -> 6.7s (from 11/10 to day) for complicated requests (~200 requests)

* https://treeherder.mozilla.org/perf.html#/graphs?timerange=5184000&series=mozilla-central,1418041,1,1&series=mozilla-central,1418039,1,1&series=mozilla-central,1418040,1,1&series=mozilla-central,1470290,1,1
* http://firefox-dev.tools/performance-dashboard/tools/netmonitor.html?days=14&filterstddev=true

The effors includes

* run damp tests on tree herder to experiment potertial perf issues, validate and file related bugs
 - test shouldComponentUpdate for SearchBox
 - remove transform in waterfall and do the damp test
 - connect width directly to the waterfall column
 - track reselect recount number via damp

* Make patches
 - Bug 1408737 - Upgrade reselect in Devtools shared libraries
 - Bug 1404929 - Security info should be loaded lazily, -13% for simple.requestsFinished, -4.7% for complicate.requestsFinished cases
 - Bug 1411855 remove unused and no inline function in toolbar
 - Bug 1386184 - wait all transition end before redirect
 - Bug 1419401 - HTTP status code is missing in raw response headers display

* Mentor bugs
 - Bug 1409651 - Fix security side panel color in netmonitor
 - Bug 1407561 - Lazy loading of tooltip text when user hovers the status column
 - Bug 1407550 - Cache L10N values in security-panel
 - Bug 1407552 - Caching L10N values in netmonitor toolbar.
 - Bug 1407981 - WEBCONSOLE_L10N is not used
 - Bug 1407548- Cache L10N values in request-list-empty-notice;
 - Bug 1407552 - cache l10n values in toolbar
file cache l10n string bugs
 - Bug 1406312 - Lazy loading of tooltip text on hover in Waterfall Timing boxes.
 - Bug 1404130- Cache L10N values to improve status bar
