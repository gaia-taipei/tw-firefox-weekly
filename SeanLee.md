### Last week

* [Data Sync]
  - [TV&DataSync WW 10/19 ~ 10/23]
  - [10/23] Having a demo at end of WW.
  - [CLOSED][Bug 1212716] Update browser IndexedDB to adapt synced data from places datastores
  - [CLOSED][Bug 1215086] Support same URL being bookmarked twice
  - [CLOSED][Bug 1215482] Support new bookmarks_store format in TV
  - [CLOSED][Bug 1216022] Clear all Bookmark and History records from FxSync when users logout FxAccount in TV Browser.
  - [CLOSED][Bug 1217340] Handle an empty visits array of history record as a valid case
  - [CLOSED][Bug 1217349] Update bookmark records without updating places
  - [CLOSED][Bug 1217352] Write the first visits record into timestamp for Places IndexedDB
  - [CLOSED][Bug 1218303] Check history records by time and export maximum size argument to SyncBrowserDB.getHistory
  - [CLOSED][Bug 1219108] Export more options to getHistory and getHistoryTimestamp function in SyncBrowserDB
  - [CLOSED][Bug 1219162] Improve the sorting order of Bookmark records as the same as Desktop and Fennec.
  - [r+][Bug 1220528] Configure the default build flag FIREFOX_SYNC to ENABLE in v2.5 branch, TV only
  - [CLOSED][Bug 1221472] Show the title for blank title bookmark records with URL.
  - Review couple patches.

* [Cloud Storage]
  - Test FileSystemProviderAPI in Gaia part. The API is still not avalible. Kershaw is investgating this issue.
  - Thinking the next steps of Cloud Storage.
  - Plan the implementation of read-write cloud storage.

* [MAP]
  - [Bug 1218685] getMessageList request is finished after inetgraing with Gecko MAP API.

* [PBAP]
  - [CLOSED][Bug 1200091] After writing unit-test, the patch is landed in v2.2r.

### This week
* [Data Sync]
  - [Bug 1211370] Get "task.target is undefined" error when deleting a history record from Places DataStore.
  - [Bug 1215436] Unit test of data adapter for converting data from Places/Bookmarks store to TV IndexedDB

* [MAP]
  - [Bug 1218685] Implement getMessage, and handling notifications.

## 2015 Q4 Goals
* [Cloud Storage] Help to write Gaia app to retrieve the files from Dropbox.
* [Cloud Storage] Plan the read-write feature of Cloud Storage.
* [Firefox Sync] Implemenet the two-way schronization feature for Bookmarks and History.
* [Firefox Sync] Fix all fxsync related bugs in TV and phone.
* [MAP/PBAP] Verify Gecko API and write reference design in Gaia. Help to fix the verfication issues from partners.(nice to have.)