### Last week

* [Data Sync]
  - [Bug 1168185] Waiting for review.
  - [Bug 1191773] Integrate the latest SyncEngine. Resolve the merging and sync-up issues. one-way function can merge every history record when the sync request is triggered.
    - pushing new records. the code is finished, but I am invesgating an Syncto error (operation not support).

* [PBAP]
  - [Bug 1200091] Put the patch in review process.

### This week
* [Data Sync]
  - [Bug 1168185] Fernando will follow my work. I can focus on History Adapter.
  - [Bug 1191773] Prepare the code which provides read-only feature for reviewing.
    - Create a follow up issue to implement push feature:
      - Create a new record (done)
      - Update an existed record (developing)
    - Test push feature (POST/PUT) of Syncto with History Adapter

* [PBAP]
  - [Bug 1200091] Update the PR based on reviewer's comments.
