### Last week

* [Form Fill]
  - [Landed][Bug 1300989] This bug includes the following changes:
    - Implement the form filling part.
    - Handle Enter key and mouse click correctly.
    - Refactor and simplify the architecture of FormAutofillContent.
  - [Low][Bug 1336370] Since bug 1300989 uses another approach, we don't have to fix this issue for Form Fill project. However, it still needs to be fixed once we have resource.
  - [Review][Bug 1333682] Review the architecture refactor patch.
  - [Landed][Bug 1338458] Implement this for simplifying the fieldname style.
  - [r?][Bug 1339721] Move form filling logic to FormAutofillHandler.autofillFormFields.
  - [r?][Bug 1340104] Hide the result which doesn't include the primary label.
  - [New][Bug 1339727] getAllFieldNames with section concept (element.getAutocompleteInfo())
  - [New][Bug 1339731] form filling-in with section concept
  - [New][Bug 1339740] feedback the usage (e.g. last used time) to parent
  - [New][Bug 1339745] sort the result for popup by last used time
  - [New][Bug 1339747] Add mochitest for verifying the form filling value and its relative events
  - [Discussion]
    - Prioritize the items in M1 and M2.
    - Redesign the architecture and consider the process model again.
    - We need Sync team's support to implement the sync feature for FormAutofill.
    - Preview and Highlight feature.
    - Prioritize metric items.
    - Feasibility of Anti-Phishing design.

* [Downloads Panel]
  - [Landed][Bug 1282662] After fixing all issues, it's landed.

* [Password Manager]
  - [Bug 1257078] Pending for waiting Bug 451955.
  - [r?][Bug 451955] Waiting for review.

### This week

* [Form Fill]
  - [Bug 1300989] Working on this bug.

* [Password Manager]
  - [Bug 1257078] Improve selection restoring feature.
  - [Bug 451955] Working on this bug.
