This is the central place for my security advisories. Also published over at https://seclists.org/fulldisclosure/.

## Advisories with CVE
| CVE            | Title                                                                                                                                                            |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| CVE-2022-0779 | User Meta “um_show_uploaded_file” Path Traversal / Local File Enumeration                                                                                        |
| CVE-2021-42063 | SAP Knowledge Warehouse <= 7.50 “SAPIrExtHelp” Reflected XSS                                                                                                     |
| CVE-2021-40149 | Reolink E1 Zoom Camera <= 3.0.0.716 Unauthenticated Private Key Disclosure                                                                                       |
| CVE-2020-25204 | God Kings "com.innogames.core.frontend.notifications.receivers.LocalNotificationBroadcastReceiver" Improper Authorization Allowing In-Game Notification Spoofing |
| CVE-2020-25203 | Frame Preview "com.framer.viewer.FramerViewActivity" Arbitrary URL Loading                                                                                       |
| CVE-2020-16171 | Acronis Cyber Backup <= v12.5 Build 16341 Full Unauthenticated SSRF                                                                                              |
| CVE-2020-12827 | MJML <= 4.6.2 mj-include "path" Path Traversal                                                                                                                   |
| CVE-2020-11882 | o2 Business for Android "canvasm.myo2.SplashActivity" <= 1.2.0 Open Redirect                                                                                     |
| CVE-2019-12517 | SlickQuiz for Wordpress 1.3.7.1 "/wp-admin/admin.php?page=slickquiz" Multiple Stored XSS                                                                         |
| CVE-2019-12516 | SlickQuiz for Wordpress 1.3.7.1 "/wp-admin/admin.php?page=slickquiz-*" Multiple Authenticated SQL Injections                                                     |
| CVE-2019-11604 | Quest KACE Systems Management Appliance <= 9.0 kbot_service_notsoap.php METHOD Reflected Cross-Site Scripting                                                    |
| CVE-2018-7841  | Schneider Electric U.Motion Builder <= 1.3.4 track_import_export.php object_id Unauthenticated Command Injection                                                 |
| CVE-2017-14956 | AlienVault USM v5.4.2 "/ossim/report/wizard_email.php" Cross-Site Request Forgery leading to Sensitive Information                                               |
| CVE-2017-14955 | Check_mk v1.2.8p25 save_users() Race Condition leading to Sensitive Information Disclosure                                                                       |
| CVE-2016-6914  | Ubiquiti UniFi Video v3.7.3 (Windows) Local Privileges Escalation via Insecure Directory Permissions                                                             |
| CVE-2016-6913  | AlienVault USM/OSSIM 5.2 conf/reload.php "back" DOM-based Cross-Site Scripting                                                                                   |
| CVE-2016-5005  | Apache Archiva 1.3.9 admin/addProxyConnector_commit.action connector.sourceRepoId Persistent Cross-Site Scripting                                                |
| CVE-2016-4469 | Apache Archiva 1.3.9 Multiple Cross-Site Request Forgeries                                                                                                       |
| CVE-2015-5956  | Typo3 Core sanitizeLocalUrl() Non-Persistent Cross-Site Scripting                                                                                                |
| CVE-2014-7216  | Yahoo! Messenger emoticons.xml Multiple Key Value Handling Local Buffer Overflow                                                                                 |
| CVE-2014-2206  | GetGo Download Manager HTTP Response Header Buffer Overflow Remote Code Execution                                                                                |
| CVE-2014-2087  | Free Download Manager CDownloads_Deleted::UpdateDownload() Buffer Overflow Remote Code Execution                                                                 |
| CVE-2013-6356 | Avira Secure Backup v1.0.0.1 Multiple Registry Key Value Parsing Local Buffer Overflow Vulnerability                                                             |
| CVE-2013-5702  | Watchguard Server Center v11.7.4 Multiple Non-Persistent Cross-Site Scripting Vulnerabilities                                                                    |
| CVE-2013-5701  | Watchguard Server Center v11.7.4 wgpr.dll Insecure Library Loading Local Privilege Escalation Vulnerability                                                      |
| CVE-2013-4695 | WinAmp v5.63 gen_ff.dll links.xml Value Parsing Invalid Pointer Dereference                                                                                      |
| CVE-2013-4694  | WinAmp v5.63 gen_jumpex.dll and ml_local.dll Multiple Buffer Overflows                                                                                           |
| CVE-2013-3934  | Kingsoft Office Writer v2012.8.1.0.3385 Buffer Overflow                                                                                                          |
| CVE-2012-6042  | GPSMapEdit 1.1.73.2 - '.lst' Denial of Service                                                                                                                   |
| CVE-2012-5200 | HP Intelligent Management Center v5.1 E0202 topoContent.jsf Non-Persistent Cross-Site Scripting                                                                  |
| CVE-2012-5002  | Ricoh DC Software DL-10 FTP Server (SR10.exe) <= 1.1.0.6 Remote Buffer Overflow Vulnerability                                                                    |
| CVE-2012-4259  | C4B XPhone UC Web 4.1.890S R1 - Cross Site Vulnerability                                                                                                         |
| CVE-2012-3845  | LAN Messenger v1.2.28 - Denial of Service Vulnerability                                                                                                          |
| CVE-2012-3238  | Astaro Security Gateway <= v8.304 Persistent Cross-Site Scripting Vulnerability                                                                                  |

## Advisories without CVE
The following vulnerabilities don't have a CVE assigned (I've been too lazy sometimes)

| ID        | Release Date                                                                                                        | Title                                                                                                                  | 
|-----------|---------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| NO-CVE-29 | 18 Jan 2017 | Mattermost <= 3.5.1 "/error" Unauthenticated Reflected Cross-Site Scripting / Content Injection                         |
| NO-CVE-28 | 21 Nov 2016 | Atlassian Confluence AppFusions Doxygen 1.3.x Information Disclosure |
| NO-CVE-27 | 20 Nov 2016 | AppFusions Doxygen for Atlassian Confluence v1.3.2 renderContent() Persistent Cross-Site Scripting                      |
| NO-CVE-26 | 20 Nov 2016 | AppFusions Doxygen for Atlassian Confluence v1.3.0 getTemporaryDirectory() tempId Path Traversal/Remote Code Execution  |
| NO-CVE-25 | 23 Feb 2016 | Ubiquiti Networks UniFi v3.2.10 Generic CSRF Protection Bypass                                                          |
| NO-CVE-24 | 11 Sep 2016 | XenForo ToggleME 3.1.2 "/admin.php?options/list/Add mortoggleME" Multiple Persistent Cross-Site Scriptings              |
| NO-CVE-23 | 23 May 2016 | XenAPI v1.4.1 for XenForo Multiple Unauthenticated SQL Injections                                                       |
| NO-CVE-22 | 21 May 2016 | Postfix Admin v2.93 Generic POST Cross-Site Request Forgeries                                                           |
| NO-CVE-21 | 3 May 2016  | Swagger Editor v2.9.9 "description" Key DOM-based Cross-Site Scripting                                                  |
| NO-CVE-20 | 19 Feb 2014 | VideoCharge Studio v2.12.3.685 cc.dll CHTTPResponse::GetHttpResponse() Buffer Overflow Remote Code Execution            |
| NO-CVE-19 | 19 Mar 2013 | Photodex ProShow Producer v5.0.3310 ScsiAccess Local Privilege Escalation                                               |
| NO-CVE-18 | 16 Feb 2013 | Photodex ProShow Producer v5.0.3297 PXT File title Value Handling Buffer Overflow                                       |
| NO-CVE-17 | 23 Feb 2013 | Photodex ProShow Producer v5.0.3297 Insecure Library Loading Vulnerability                                              |
| NO-CVE-16 | 14 Feb 2013 | Photodex ProShow Producer v5.0.3297 ColorPickerProc() Memory Corruption                                                 |
| NO-CVE-15 | 14 Jan 2013 | Serva v2.0.0 DNS Server Remote Denial of Service                                                                        |
| NO-CVE-14 | 14 Jan 2013 | Serva v2.0.0 HTTP Server GET Remote Denial of Service                                                                   |                                                                           |
| NO-CVE-13 | 16 Sep 2012 | NCMedia Sound Editor Pro v7.5.1 MRUList201202.dat File Handling Local Buffer Overflow                                   |
| NO-CVE-12 | 24 Aug 2012 | Aoop CMS 0.3.6 SQL Injection / Cross Site Scripting                                                                              |  
| NO-CVE-11 | 2 Jul 2012  | Photodex ProShow Producer v5.0.3256 Local Buffer Overflow Vulnerability                                                 |
| NO-CVE-10 | 30 Mar 2012 | Bitsmith PS Knowbase 3.2.3 - Buffer Overflow Vulnerability                                                              |
| NO-CVE-9  | 8 Mar 2012  | Ilient SysAid v8.5.05 - Multiple Web Vulnerabilities                                                                    | 
| NO-CVE-8  | 8 Mar 2012  | Pitrinec MacroToolworks 7.5 - Buffer Overflow Vulnerability                                                             |
| NO-CVE-7  | 8 Mar 2012  | Enterasys SecureStack Switch v6.x - Multiple Vulnerabilities                                                            |
| NO-CVE-6  | 11 Apr 2012 | Crystal Office Suite v1.43 - Buffer Overflow Vulnerability                                                              |
| NO-CVE-5  | 10 Apr 2012 | FileStream Turbo Browser v11.6 - Buffer Overflow                                                                        |
| NO-CVE-4  | 8 Apr 2012  | AnvSoft Any Video Converter 4.3.6 - Multiple Buffer Overflow Vulnerabilities                                            |
| NO-CVE-3  | 1 Apr 2012  | BulletProof FTP Client 2010 - Buffer Overflow Vulnerability                                                             |
| NO-CVE-2  | 26 Feb 2012 | Socusoft Photo2Video 8.05 - Buffer Overflow Vulnerability                                                               |
| NO-CVE-1  | 21 Feb 2012 | DAMN Hash Calculator 1.5.1 Heap Overflow                                                                                |
