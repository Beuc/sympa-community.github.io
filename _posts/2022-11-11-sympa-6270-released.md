---
assets:
  - created_at: 2022-11-10T11:49:30Z
    name: sympa-6.2.70.tar.gz
    size: 13033808
    updated_at: 2022-11-10T11:49:38Z
    url: https://github.com/sympa-community/sympa/releases/download/6.2.70/sympa-6.2.70.tar.gz
  - created_at: 2022-11-10T11:49:30Z
    name: sympa-6.2.70.tar.gz.md5
    size: 54
    updated_at: 2022-11-10T11:49:30Z
    url: https://github.com/sympa-community/sympa/releases/download/6.2.70/sympa-6.2.70.tar.gz.md5
  - created_at: 2022-11-10T11:49:30Z
    name: sympa-6.2.70.tar.gz.sha256
    size: 86
    updated_at: 2022-11-10T11:49:30Z
    url: https://github.com/sympa-community/sympa/releases/download/6.2.70/sympa-6.2.70.tar.gz.sha256
  - created_at: 2022-11-10T11:49:29Z
    name: sympa-6.2.70.tar.gz.sha512
    size: 158
    updated_at: 2022-11-10T11:49:30Z
    url: https://github.com/sympa-community/sympa/releases/download/6.2.70/sympa-6.2.70.tar.gz.sha512
created_at: 2022-11-10T11:41:43Z
prerelease: 0
published_at: 2022-11-11T10:58:33Z
tag_name: 6.2.70
title: Sympa 6.2.70 released
---

## What's Changed
* Remind name of the opened list in the notification by @ldidry in https://github.com/sympa-community/sympa/pull/1313
* 🚸 — Add anchors to prefs to ease linking (like in FAQ, etc.) by @ldidry in https://github.com/sympa-community/sympa/pull/1328
* Bugs injected by PR#1286 by @ikedas in https://github.com/sympa-community/sympa/pull/1344
* Merging #1098 by @ikedas in https://github.com/sympa-community/sympa/pull/1357
* ✨ — Add "bouncers reset", "bouncers del" and "bouncers [--status] review" commands to sympa.pl by @ldidry in https://github.com/sympa-community/sympa/pull/1098
* 🐛 — Missing some id on input tags by @ldidry in https://github.com/sympa-community/sympa/pull/1358
* Protect email addresses in archive search (#1312) by @ikedas in https://github.com/sympa-community/sympa/pull/1363
* 🐛 — Protect email addresses in archive search by @ldidry in https://github.com/sympa-community/sympa/pull/1314
* WWSympa: "Synchronize ... with data sources" button is not shown (#1355) by @ikedas in https://github.com/sympa-community/sympa/pull/1356
* Fix #533 — Prevent the use of the list address as subscriber by @ikedas in https://github.com/sympa-community/sympa/pull/1366
* Fix #533 — Prevent the use of the list address as subscriber by @ldidry in https://github.com/sympa-community/sympa/pull/1343
* WWSympa: File paths of archived messages may be exposed in the result of arcsearch (#1364) by @ikedas in https://github.com/sympa-community/sympa/pull/1365
* Bugs injected by PR#1286 (2) by @ikedas in https://github.com/sympa-community/sympa/pull/1375
* Break sympa_wizard.pl to "sympa config…" commands by @ikedas in https://github.com/sympa-community/sympa/pull/1370
* tidyallrc was not included in source dist by @ikedas in https://github.com/sympa-community/sympa/pull/1382
* When closed list is restored, subscribers won't be restored (#1380) by @ikedas in https://github.com/sympa-community/sympa/pull/1381
* Add unit/socket files to make use of multiwatch by @ikedas in https://github.com/sympa-community/sympa/pull/1362
* blocklist sensitive to spurious whitespace (#1377) by @ikedas in https://github.com/sympa-community/sympa/pull/1385
* WWSympa: Adding owner/moderator with non-default options does not work (#1329) by @ikedas in https://github.com/sympa-community/sympa/pull/1379
* More fixes for #1329 by @ikedas in https://github.com/sympa-community/sympa/pull/1387
* Addition to #1370 by @ikedas in https://github.com/sympa-community/sympa/pull/1389
* Remove user menu entries showing only information (#1393) by @racke in https://github.com/sympa-community/sympa/pull/1395
* Revert changes for #1186 "Improving data source synchronization performance" by @ikedas in https://github.com/sympa-community/sympa/pull/1398
* Unable to set custom attribute using the SOAP API (if none already set) (#1401) by @ikedas in https://github.com/sympa-community/sympa/pull/1402
* The owner sees the pop-up stating a message is waiting for moderation even if moderators are defined separately (#1406) by @ikedas in https://github.com/sympa-community/sympa/pull/1409
* sympa_soap_client.pl fails if SOAP call returns hash result. by @ikedas in https://github.com/sympa-community/sympa/pull/1415
* SympaSOAP: Result by setCustom with parameter including non-ASCII characters is broken (#1407) by @ikedas in https://github.com/sympa-community/sympa/pull/1413
* File names in incoming spool can be truncated (#1410) by @ikedas in https://github.com/sympa-community/sympa/pull/1411
* Missing dependency Pod::Usage by @ikedas in https://github.com/sympa-community/sympa/pull/1417
* CLI: Only the first loading of sympa.conf used the --config option by @ikedas in https://github.com/sympa-community/sympa/pull/1425
* Fix some typos (#1432) by @ikedas in https://github.com/sympa-community/sympa/pull/1436
* Fix some typos by @fingolfin in https://github.com/sympa-community/sympa/pull/1433
* Crash with the broken message with "multipart/signed" MIME type (#1454) by @ikedas in https://github.com/sympa-community/sympa/pull/1455
* Additional fix to #1379 (#1329) by @ikedas in https://github.com/sympa-community/sympa/pull/1462
* Update translation for 6.2.70 by @ikedas in https://github.com/sympa-community/sympa/pull/1472
* Use new domain name and list addresses for Sympa in the source by @ikedas in https://github.com/sympa-community/sympa/pull/1463
* Update translation by @ikedas in https://github.com/sympa-community/sympa/pull/1490
* Release 6.2.70 by @ikedas in https://github.com/sympa-community/sympa/pull/1384

## New Contributors
* @fingolfin made their first contribution in https://github.com/sympa-community/sympa/pull/1433

**Full Changelog**: https://github.com/sympa-community/sympa/compare/6.2.68...6.2.70