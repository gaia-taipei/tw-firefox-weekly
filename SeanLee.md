### Last week

* [Form Fill]
  - [Landed][Bug 1339721] Move form filling logic to FormAutofillHandler.autofillFormFields.
  - [Bug 1333351] Since the heuristic logic is too complex to implement in one bug, so it should be break-down:
    * Phone field
      - Implementation of how to determine a phone field.
    * Email field
      - Implementation of how to determine a email field.
    * Name field
      - Implementation of how to determine a name field relative to .
    * Address field
      - Implementation of how to determine a address field relative to country, street address, address line, state, organization, postal code, etc.
    * Credit Card field
      - Implementation of how to determine a credit card relative field like card number and expiration date (year/month). However, this could be in M3.
    * Heuristic utils
      - Some common logics like finding the label element belongs to an input or the logic cross a single element.
    * The test fixtures for Top 12 site
      - Digest the web pages with forms in these sites and put the html part into our test as the test fixtures.

* [Password Manager]
  - [Bug 1257078] Pending for waiting Bug 451955.
  - [r?][Bug 451955] Waiting for review.

### This week

* [Form Fill]
  - [Bug 1333351] Working on this bug.

* [Password Manager]
  - [Bug 1257078] Improve selection restoring feature.
  - [Bug 451955] Working on this bug.
