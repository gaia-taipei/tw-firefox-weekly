# 1/8 ~ 1/12
-   A/B Testing Survey https://docs.google.com/document/d/1oMSIboyLEF9iz_zztbXyCJToU6dSltDT5RvKVyPFu8g/edit?usp=sharing
-   Triage: General ~ 20 bugs
-   1417255	Use Espresso for UI Testing - r?maliu
-   1427771	Blank screen when youtube exists from full-screen in custom tabs - ni?snorp
-   1423587 PWA with expired security certificate should open in browser - landed
-   1403754 Crash in java.lang.NullPointerException:  - r?maliu
-   1405192 Crash in java.lang.IllegalStateException:  - r?maliu


# 1/3 ~ 2/6
-	Survey React Native with Native Android Studio repo : https://github.com/cnevinc/ReactNativeHybrid/tree/master
-   Triage: Metrics. General, AwesomeSceen ~ 40 bugs
-   1424179 A2HS badge is shown on site with broken HTTPS (Follow Up) - Uplift
-   1419245 A2HS badge is shown on site with broken HTTPS - Uplift
-   1417255	Use Espresso for UI Testing - r?maliu
-   1423587 PWA with expired security certificate should open in browser - r?maliu


# 10/26 ~ 11/25
Leanplum
-	1421149	[PWA] Icons in the "Add to Home screen" overlay should not have outline & dropshadow - r+landed
-	1419245	A2HS badge is shown on site with broken HTTPS - r?walkingice
-	1421946	Make Switchboard accept duplicated experiment names - landed
-	1420055	[Leanplum] Drop an event when user finish first run on-boarding. - landed
-	1418193	[Leanplum] Display device id in about:config for easy debugging - landed
-	1380950	(Leanplum) Deeplinks should not be triggered through content or other apps - landed
-	1411064	Expand Leanplum to deu and zho locales - landed


GeckoView / PWA / Custom Tab
-	1405236	Custom Tabs Switch under Settings -> General - landed
-	1403566	Web Apps - Login auto-complete isn't working, with multiple logins saved  - landed
-	1419320	PWA - icon and onboarding image update - wip
-	1409264	PWA Badge and Onboarding - Should we hide the badge when the web site is already added ? - open
-	1390454	Apply Banner fix for Leanplum SDK - landed
-	1409303	Enable PWA by default - landed
-	1410343	PWA Badge and Onboarding - Improve pre-fetch/install Manifest mechanism - open
-	1409191	The "Add to home screen" prompt doesn't appear to use manifest values - landed


Testing
-	1417255	Use Espresso for UI Testing - wip
-	1420346	[Errno 61] Connection refused when running robocop test - invalide


General
-	1422266	Replace Google Play Service dependency used by Adjust SDK - WIP
-	1421859	Notification area icon uses old shape - file
-	1411827	Crash in java.lang.NullPointerException: Attempt to invoke interface method ''android.view.MenuItem android.view.MenuItem.setChecked(boolean)'' on a null object reference at org.mozilla.gecko.BrowserApp.onPrepareOptionsMenu(BrowserApp.java) (Android O) - invalid
-	1366629	When clicking on a label attached in Gallery or Photos and Camera to a File Upload field, it no longer works to upload a file. - open
-	1286698	Distribution leaks a Context - open
-	1401444	write front end test for PWA - open
-	1402805	Create test for install app shortcut - dup
-	1397174	Fix scale issue for icons like AdaptiveIconDrawable in Android O - open
-	1372040	Make Fennec support AdaptiveIconDrawable in Android O - open 
-	1322973	Adding YouTube as a search engine after opening a video does not work properly - open
-	1377819	Crash in java.lang.ClassCastException: interface org.mozilla.gecko.tabs.TabsPanel$TabsLayout cannot be cast to android.view.View at java.lang.Class.asSubclass(Class.java) - closed
-	1357377	Limit intent filters and check incoming intents against whitelist - open
-	1392538	Remove unused Kinto settings - landed
-	1382589	Enable hyphenation dictionary runtime download - open
-	1413240	Support webext language packs in Fennec - wip
-	1399014	Allow 'enable tracking protection in normal browsing' for release and beta channel. - landed
-	1413520	Telemetry data upload disabled in about:telemetry - open

Bookmark
-	1413114	Enable Fennec Bookmark Management - landed
-	1411607	Should hide Experimental features section when there are no experiments - landed
-	1421174	Remove old AddToHomeScreenPromotion - open
-	1412823	Fennec Bookmark Management: wrong message displayed when removing folders - landed


Photon
-	1398362	(Photon) Image/logo size in onboarding screen is incorrect on API 16 & 17 - landed
-	1410338	[Photon] Incorrect color for History Panel message - landed




# 10/6 ~ 10/25
Leanplum
- 1390454	Update Leanplum SDK for Banner	not in sprint, 
    POC
- 1411064	Expand Leanplum to de and zh-tw locales	
    reply comment
- 1411066	Expand Leanplum in en from 10% to 50% of our Android users	
    pending
- 1397188	[LeanPlum] - Push Notifications also received for active users	
    VERIFIED
- 1399388	[LeanPlum]: Top Sites panel open instead of Bookmarks Panel	
    pending
    RESOLVED
- 1400150	Use Swtichboard to enable Leanplum debugging	
    RESOLVED
- 1396714	Remove for Gecko Pref for Leanplum	
    RESOLVED
- 1397184	Move MMA doc to firefox-source-docs.mozilla.org	
    RESOLVED

GeckoView / PWA / Custom Tab
- 1405236	Custom Tabs Switch under Settings -> General	
    RESOLVED
- 1409303	Move PWA setting to Setting - General	
    VERIFIED
- 1395841	implement change for separating “add to home screen” & “add page shortcut”	
    RESOLVED
- 1409296	Support minimal context menu functionality in GeckoView-based PWA	
    RESOLVED
- 1365868	Support minimal context menu functionality in GeckoView-based custom tabs	
    RESOLVED
- 1409191	The "Add to home screen" prompt doesn't appear to use manifest values	
    VERIFIED
- 1393672	PWA Badge and Onboarding - Main workflow	
    VERIFIED
- 1409403	Update badge icon for PWA	VERIFIED
- 1380950	(Leanplum) Deeplinks should not be triggered through content or other apps	rebased, 
    r+, waiting to land
- 1410343	PWA Badge and Onboarding - Improve pre-fetch/insall Manifest mechanism	
    pending
- 1409268	PWA Badge and Onboarding - Add telemetry	
    RESOLVED
- 1410842	Play with Pull to refresh layout	
    WIP, POC
- 1407961	PWA Badge and Onboarding - Show home after creating PWA shortcut when API >26	
    RESOLVED
- 1368024	Web Apps - Fall back to 'name' when 'short_name' is missing	
    VERIFIED
- 1409264	PWA Badge and Onboarding - Should we hide the badge when the web site is already added ?	
    reply comment
- 1409261	PWA Badge and Onboarding - Add localization comments for pwa_add_to_launcher_badge	
    RESOLVED
- 1409279	Reimplement custom tabs telemetry from 55 to 57	
    RESOLVED

Fullscreen
- 1317242	Location Bar Spoofing Risk using the Fullscreen mode and a new tab loaded using the alert()	
    RESOLVED

General
- 1411607	Should hide Experimental features section when there are no experiments	
    reply comment
- 1397174	Fix scale issue for icons like AdaptiveIconDrawable in Android O	
    pending
- 1406671	Implement a better closeAllTabs method	
    pending
- 1331290	Refactor the code about closing all opening tabs	
    RESOLVED
- 1377819	Crash in java.lang.ClassCastException: interface org.mozilla.gecko.tabs.TabsPanel$TabsLayout cannot be cast to android.view.View at java.lang.Class.asSubclass(Class.java)	
    RESOLVED
- 1264221	Correctly scale/modify home screen shortcut icons	
    reply comment
- 1331000	Validate signature of downloadable content catalog and switchboard configuration	
    pending
- 1388300	Try to remove unnecessary dependencies	
    RESOLVED
- 1356596	Spoof page in full screen mode Firefox Android with "scroll"	
    RESOLVED
- 1389343	Missing/tiny icons for history, bookmark items	
    VERIFIED
- 1391342	Toolbar can get stuck partially-visible when focusing a text field in fullscreen mode	
    RESOLVED
- 1405287	Change Splash Screen image	
    VERIFIED
- 1402882	(Onboarding) Firstrun Images for Nightly, Beta, Release	


Onboarding
- 1401505	Make Onboarding Portrait Only	
    pending

Photon
- 1398362	(Photon) Image/logo size in onboarding screen is incorrect on API 16 & 17	
    RESOLVED
- 1410338	[Photon] Incorrect color for History Panel message	
    VERIFIED
- 1405853	About screen still shows old Firefox logo	
    VERIFIED
- 1403132	Orange color when tapping "Get started" button	
    VERIFIED
- 1403728	Additional margin at top and bottom of tabs tray in non-compact portrait mode	
    VERIFIED
- 1403980	Splash screen displayed in new tab opened from the search widget	
    RESOLVED
- 1400804	(photon) First run tour - the Sync button is not visible, or squished, in landscape	
    VERIFIED
    
   
