### Last week

* [Homescreen]
  - [CLOSED][Bug 1154649] scoped css always override app's css. The inline style can avoid this issue, so the solution is in Javascript.

* [Contacts]
  - [PENDING][Bug 1159180] Invalid N type can not be exported as vCard v3 spec, but a vcard without Ntype is valid in vCard v4 spec. Put it into backlog.

* [Cloud Storage]
  - [CLOSED] QuotaExceededError of MSE is caused by a non-fragmented MP4 file when appending buffer. Appenging any video fragment larger than 75MB (defined in Gecko) will throw QuotaExceededError from Gecko.
  - [CLOSED] Create MozCloudStorage organization in Github.
  - [WIP][CSManagerApp] Implement a Gaia app for file managing and storage managing.

* [New Architecture]
  - Study Service Worker.

### This week

* [STK]
  - [WIP][Bug 1100218] Provide a patch to use IAC for icc.data. We still need to refactor icc.application and provide a command queue.

* [Settings]
  - [WIP][Bug 1131552] Implementing the patch for v2.2/v3.0.

* [FTU]
  - [WIP][Bug 1144584] I need the confirmation of Reporter's STR.

* [Cloud Storage]
  - Verify FUSE in Gecko and Cache Manager in JSM can work together and achieve the goal of Cloud Storage.
  - [CSManagerApp] Implement the app to switch Cloud Storage and provide Access Token to gecko.
