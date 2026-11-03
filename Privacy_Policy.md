# Comprehensive Privacy Policy for Closed Testing

**Effective Date:** November 4, 2026  
**Last Updated:** November 4, 2026  
**Application Name:** Closed Testing  
**Android Package Name:** `com.testers.closedtesting`  
**Operating Entity / Developer:** Testers Area Team ("Company", "we", "us", or "our")  
**Official Contact / Grievance Email:** testersareaofficial@gmail.com  

---

## Table of Contents
1. [Introduction and Scope](#1-introduction-and-scope)
2. [Legal Definitions and Interpretations](#2-legal-definitions-and-interpretations)
3. [Nature and Operational Model of the Service](#3-nature-and-operational-model-of-the-service)
4. [Legal Bases for Data Processing (GDPR, CCPA, DPDP Act)](#4-legal-bases-for-data-processing)
5. [Information We Collect (Categories and Sources)](#5-information-we-collect)
   * 5.1 Account and Profile Data (Google OAuth 2.0)
   * 5.2 Android Sensitive System Permissions & Foreground Tracking
   * 5.3 Technical, Network, and Device Telemetry
   * 5.4 User-Generated Content and Verification Proofs
   * 5.5 Notification and Messaging Data
6. [Explicit Restrictions: What We Strictly Do NOT Collect](#6-explicit-restrictions-what-we-strictly-do-not-collect)
7. [Third-Party SDKs, API Integrations, and Sub-Processors](#7-third-party-sdks-api-integrations-and-sub-processors)
   * 7.1 Google Play Services & Google Identity
   * 7.2 Google AdMob & Mobile Ads SDK
   * 7.3 Supabase Cloud Infrastructure and Database
8. [Purposes of Data Processing](#8-purposes-of-data-processing)
9. [Anti-Fraud, Bot Detection, and Streak Verification Protocols](#9-anti-fraud-bot-detection-and-streak-verification-protocols)
10. [Data Sharing, Disclosure, and Third-Party Access](#10-data-sharing-disclosure-and-third-party-access)
11. [Cross-Border Data Transfers](#11-cross-border-data-transfers)
12. [Data Storage, Encryption, and Information Security](#12-data-storage-encryption-and-information-security)
13. [Data Retention and Account Deletion Policy](#13-data-retention-and-account-deletion-policy)
    * 13.1 Right to Erasure
    * 13.2 In-App Deletion Workflow
    * 13.3 Web / Email Deletion Request Procedure
    * 13.4 Scope of Deleted Data vs. Audit Retentions
14. [Global Privacy Rights](#14-global-privacy-rights)
    * 14.1 European Economic Area (EEA) and UK (GDPR)
    * 14.2 California Consumer Privacy Act (CCPA / CPRA)
    * 14.3 Indian Digital Personal Data Protection Act (DPDP Act 2023)
15. [Third-Party Applications and Developer Content Disclaimer](#15-third-party-applications-and-developer-content-disclaimer)
16. [Statutory Disclaimer Regarding Google LLC](#16-statutory-disclaimer-regarding-google-llc)
17. [Children's Online Privacy Protection (COPPA / Age Restrictions)](#17-childrens-online-privacy-protection)
18. [Governing Law, Jurisdiction, and Dispute Resolution](#18-governing-law-jurisdiction-and-dispute-resolution)
19. [Modifications to this Privacy Policy](#19-modifications-to-this-privacy-policy)
20. [Data Protection Officer (DPO) and Contact Information](#20-data-protection-officer-dpo-and-contact-information)

---

## 1. Introduction and Scope

This Comprehensive Privacy Policy ("Privacy Policy") governs the collection, processing, storage, transfer, and protection of personal and technical data by **Testers Area Team** in connection with the mobile application **Closed Testing** (Package Name: `com.testers.closedtesting`), including all associated APIs, online services, backend systems, and community platforms (collectively, the "Service").

We recognize that data privacy is a fundamental human right. This document has been prepared to comply with:
* **Google Play Developer Program Policies** (specifically the *User Data Policy*, *Permissions and APIs that Access Sensitive Information Policy*, and *Account Deletion Policy*);
* The **European Union General Data Protection Regulation (EU GDPR 2016/679)** and the **United Kingdom GDPR**;
* The **California Consumer Privacy Act of 2018 (CCPA)**, as amended by the **California Privacy Rights Act of 2020 (CPRA)**;
* The **Digital Personal Data Protection Act, 2023 (DPDP Act - India)**; and
* Applicable international data protection and privacy statutes worldwide.

By downloading, installing, launching, authenticating through, or interacting with the Closed Testing application, you confirm that you have read, understood, and agree to the data collection and processing practices described herein. If you do not agree with any provision of this Privacy Policy, you must immediately uninstall the application and discontinue use of all associated services.

---

## 2. Legal Definitions and Interpretations

For the purposes of this Privacy Policy:
* **"Application"** or **"App"** refers to Closed Testing, packaged under the unique Android bundle identifier `com.testers.closedtesting`.
* **"Company"**, **"We"**, **"Us"**, or **"Our"** refers to Testers Area Team, the software development and publishing entity responsible for operating the Service.
* **"User"**, **"Tester"**, **"Developer"**, **"You"**, or **"Your"** refers to any individual, developer, or authorized representative accessing or utilizing the Application.
* **"Personal Data"** (or **"Personally Identifiable Information" / PII**) means any information relating to an identified or identifiable natural person who can be identified, directly or indirectly, in particular by reference to an identifier such as a name, an identification number, location data, an online identifier, or to one or more factors specific to physical, physiological, genetic, mental, economic, cultural, or social identity.
* **"Usage Data"** refers to telemetry data collected automatically either generated by the use of the Service or from the Service infrastructure itself (for example, the duration of a foreground testing session).
* **"Partner Application"** or **"Test App"** refers to a third-party Android application published by an enrolled community developer that is listed on our platform for closed testing validation.
* **"Usage Access"** refers specifically to the privileged Android system permission `android.permission.PACKAGE_USAGE_STATS`.
* **"Supabase"** refers to Supabase Inc., our cloud database, authentication handler, and backend infrastructure provider.
* **"Google Identity"** refers to the OAuth 2.0 authentication architecture provided by Google LLC for single sign-on user verification.

---

## 3. Nature and Operational Model of the Service

Closed Testing operates as a specialized peer-to-peer reciprocal testing community platform tailored for indie Android mobile developers. 

Under Google Play Console policies enforced since November 2023, developers with newly created personal Google Play Console accounts are mandated to test their applications with a minimum of **twenty (20) opt-in testers continuously for at least fourteen (14) consecutive days** before qualifying to apply for production release access.

The core utility of Closed Testing is to:
1. Provide a community exchange marketplace where developers list their testing tracks and volunteer testers install and test partner apps;
2. Verify that community testers honor their commitment by measuring active daily foreground interaction time (e.g., minimum 60 seconds foreground execution per day);
3. Record consecutive 14-day testing streaks; and
4. Allocate internal, non-monetary community utility credits ("Tester Points") to reward diligent testers, enabling them to solicit testing for their own submitted applications.

Because the integrity of Google Play's Closed Testing program relies upon authentic human engagement, our Service utilizes precise device foreground session measurements while maintaining strict firewalls to safeguard user privacy.

---

## 4. Legal Bases for Data Processing

In accordance with Article 6 of the EU/UK GDPR and comparable international privacy statutes, we process your Personal Data only when a valid legal basis exists:

1. **Explicit Consent (Art. 6(1)(a) GDPR):**  
   You provide voluntary, affirmative consent when authenticating via Google Sign-In, granting optional runtime Android permissions (such as Notifications and Photo Picker), and agreeing to these terms on the login consent screen.
2. **Contractual Performance (Art. 6(1)(b) GDPR):**  
   Processing your User ID, test streaks, and active test time is necessary to perform our contract with you—namely, maintaining your tester profile, syncing your testing streaks, and calculating earned tester points.
3. **Legitimate Interests (Art. 6(1)(f) GDPR):**  
   We process technical telemetry, device identifiers, and anti-tamper signals to protect our platform against automated bot networks, click-farms, emulator fraud, malicious APK uploads, and technical abuse.
4. **Legal Compliance (Art. 6(1)(c) GDPR):**  
   We may process and retain certain records to comply with applicable statutory legal obligations, law enforcement requests, tax/accounting audits, and Google Play Developer Program requirements.

---

## 5. Information We Collect

### 5.1 Account and Profile Data (Google OAuth 2.0)
Closed Testing exclusively utilizes Google Sign-In to streamline authentication and eliminate vulnerable username/password schemes. When you authorize our Application using Google Sign-In, we collect:
* **Full Name / Display Name:** Stored to identify your tester profile and display your nickname on community leaderboards and test task logs.
* **Google Account Email Address:** Used as your unique primary account identity, for transactional account notices, and to verify enrollment in Google Play Closed Testing opt-in Google Groups.
* **Profile Avatar URL:** A web reference to your Google account avatar picture, used purely for in-app interface rendering.
* **Unique System UUID:** An internal, cryptographically random identifier assigned by our Supabase backend to index your testing history, registered applications, and points balance without exposing raw credentials.

### 5.2 Android Sensitive System Permissions & Foreground Tracking
To maintain an authentic testing exchange, the Application requires specific Android runtime permissions:

* **Package Usage Stats (`android.permission.PACKAGE_USAGE_STATS`):**
  * **Functionality:** This permission provides access to Android's `UsageStatsManager` system service.
  * **Strict Purpose:** It is queried **exclusively** to verify whether a registered Partner Application is currently running in the device foreground and to calculate the cumulative active foreground duration (in seconds) spent inside that specific application during a 24-hour cycle.
  * **Verification Threshold:** Once the required daily foreground threshold (e.g., 60 seconds) is reached, further usage tracking for that application ceases for that calendar day.
  * **Negative Scope:** Under no circumstances does this permission allow us to read screen contents, capture keystrokes, intercept network packets, or monitor personal activity.

* **Compliant Package Visibility (No Broad Querying):**
  * Closed Testing **does not** request or declare the broad `android.permission.QUERY_ALL_PACKAGES` permission.
  * Discovery and verification of partner applications are conducted strictly via targeted Android Intent queries (`ACTION_MAIN`, `CATEGORY_LAUNCHER`) matching explicitly enrolled package identifiers.

* **Photo Library / Storage Access (System Photo Picker):**
  * When a user voluntarily chooses to upload a test feedback screenshot or bug report, access is mediated exclusively via Android's photo picker (`image_picker`).
  * The Application receives temporary, read-only URI access **solely to the individual image file you explicitly tap and select**. The Application never scans, indexes, browses, or uploads your broader photo library, camera roll, or device filesystem.

* **Push Notifications (`android.permission.POST_NOTIFICATIONS`):**
  * Requested on Android 13 (API Level 33) and higher to send localized notifications regarding daily 1-minute test reminders, streak milestone alerts, and account status updates.
  * You can revoke this permission at any time through Android System Settings without affecting core testing functionality.

### 5.3 Technical, Network, and Device Telemetry
During normal interaction with our servers, our infrastructure automatically logs certain non-personally identifiable diagnostic telemetry:
* **Device Characteristics:** Manufacturer, hardware model, Android OS version, SDK build level, system language, and display resolution.
* **Network & Connection Metadata:** IP address (used temporarily for geolocation classification at the country level and anti-bot rate-limiting), network operator type (Wi-Fi vs. Cellular), and standard HTTP user-agent headers.
* **Diagnostic & Crash Logs:** Application performance metrics, stack traces generated during runtime crashes, and API latency measurements.

### 5.4 User-Generated Content and Verification Proofs
* Information you voluntarily submit, such as developer application submission records (Package Name, Google Play Opt-in URL, App Title, Description), bug reports, feedback messages in community task cards, and attached verification screenshots.

### 5.5 Notification and Messaging Data
* Internal transaction logs recording when test reminders, streak completion pings, or administrative announcements were dispatched and received.

---

## 6. Explicit Restrictions: What We Strictly Do NOT Collect

To maintain absolute transparency and eliminate privacy ambiguity, we provide the following explicit negative pledges:

* **WE NEVER ACCESS OR READ PERSONAL APPS:** We never monitor, inspect, log, or store data regarding your interactions with personal applications, including but not limited to WhatsApp, Telegram, Signal, Gmail, Outlook, Banking/Financial Apps, Cryptocurrency Wallets, Web Browsers (Chrome, Firefox), Gallery/Photos, Dating Apps, or Social Media (Instagram, Facebook, X/Twitter, TikTok).
* **WE NEVER ACCESS SENSITIVE HARDWARE SENSORS:** We do not request, access, or record device microphones, audio inputs, video cameras, Bluetooth beacons, biometric scanners, or GPS precise location coordinates.
* **WE NEVER ACCESS COMMUNICATION LOGS:** We do not read, intercept, or access contacts, SMS/MMS messages, phone call history, or clipboard contents.
* **WE NEVER ACCESS LOCAL STORAGE FILES:** We do not browse, index, or harvest non-selected documents, audio files, downloads, or local app data from your internal device storage or SD card.

---

## 7. Third-Party SDKs, API Integrations, and Sub-Processors

We partner with established, industry-standard third-party service providers who assist in powering our authentication, advertising, and cloud infrastructure. Below is a detailed disclosure of each sub-processor, their operational purpose, and links to their privacy disclosures:

| Service / SDK Provider | Purpose in Closed Testing | Data Shared / Processed | Official Privacy Reference |
| :--- | :--- | :--- | :--- |
| **Google Play Services & Google Identity** (Google LLC) | User authentication (OAuth 2.0 single sign-on) and Android platform runtime support. | Google Name, Email, Profile Picture URL, Device Identifiers. | [Google Privacy Policy](https://policies.google.com/privacy) |
| **Google AdMob** (Google LLC) | Delivery of in-app advertisements (banner, interstitial, rewarded, app-open) to fund backend servers. | Android Advertising ID (GAID), IP address, coarse location, ad interaction and viewability metrics. | [AdMob Privacy & Terms](https://support.google.com/admob/answer/6128543) |
| **Supabase Cloud Infrastructure** (Supabase Inc.) | Primary cloud backend: database hosting, API endpoints, Row-Level Security (RLS), and encrypted file storage. | Account records, tester credits, test streaks, encrypted image proofs, telemetry logs. | [Supabase Privacy Policy](https://supabase.com/privacy) |

All third-party sub-processors are bound by strict data processing agreements and are prohibited from utilizing personal data for any purpose other than providing their contracted services to Closed Testing.

---

## 8. Purposes of Data Processing

We process collected information strictly for specified, explicit, and legitimate business purposes:

1. **Authentication and Profile Management:** To authenticate your identity via Google Sign-In, create and maintain your account, and prevent unauthorized account takeover.
2. **Mutual Testing Verification:** To compute daily foreground testing time inside enrolled Partner Applications, verify active test participation, and record 14-day continuous streaks.
3. **Credit Economy & Incentive Allocation:** To accurately credit your profile with internal tester points, enabling you to list your own applications for community testing.
4. **Fraud Prevention & Integrity Enforcement:** To detect and neutralize automated bots, auto-clickers, emulators, duplicate accounts, and fraudulent activity that undermines Google Play Console requirements.
5. **Infrastructure Maintenance & Ad Delivery:** To serve advertisements via Google AdMob that cover cloud hosting, bandwidth, and database maintenance costs.
6. **Customer Support and Dispute Resolution:** To investigate bug reports, troubleshoot synchronization failures, and resolve disputed test streaks between developers and testers.
7. **Legal Compliance and Policy Enforcement:** To enforce our Terms of Service and respond to lawful government, regulatory, or judicial requests.

---

## 9. Anti-Fraud, Bot Detection, and Streak Verification Protocols

The credibility of our platform depends upon authentic, human-driven app testing. To maintain this integrity:

* Our Application employs automated algorithmic verification checks that analyze session continuity, foreground timestamps, and hardware sensor telemetry to ensure testing is executed by real humans on genuine physical Android devices.
* **Prohibited Environments:** Use of headless Android emulators, virtualized sandbox clones, macro clickers, auto-tap scripts, rooted device hooks (e.g., Xposed/Frida designed to spoof `UsageStatsManager`), or simulated clock manipulation is strictly detected.
* Detection of automated fraud triggers immediate account suspension, forfeiture of accrued credits, and blacklisting of associated Google accounts and hardware signatures.

---

## 10. Data Sharing, Disclosure, and Third-Party Access

### 10.1 Absolute Prohibition on Data Commercialization
**We do not sell, rent, monetize, lease, or trade your Personal Data to data brokers, marketing agencies, or any commercial third parties.**

### 10.2 Community Visibility (Public Data)
When participating in community testing tasks:
* Your public tester display name and avatar may be displayed in test task cards and completion leaderboards so community developers can confirm who is actively testing their application.
* Your private email address and device identifiers are **never** displayed publicly to other community users.

### 10.3 Legal Disclosures and Law Enforcement
We may disclose your information if required to do so by applicable law, regulation, subpoena, search warrant, or valid court order, or if we determine in good faith that such disclosure is reasonably necessary to:
* Comply with legal process or governmental requests;
* Enforce our Terms of Service and investigate potential violations;
* Protect the rights, property, personal safety, or security of Testers Area Team, our users, or the public; or
* Detect, prevent, or address security, technical, or fraud issues.

---

## 11. Cross-Border Data Transfers

Our backend infrastructure and databases are hosted through Supabase Inc. across secure cloud data center facilities located in the United States and the European Union. 

If you are accessing the Application from outside these regions (including the European Economic Area, United Kingdom, India, or Asia-Pacific), please be aware that your data may be transferred to, stored, and processed in jurisdictions where data protection standards may differ from those in your country. 

Where international transfers occur from the EEA or UK, we ensure appropriate safeguards are implemented in accordance with Article 46 of the GDPR, including executing the European Commission's Standard Contractual Clauses (SCCs).

---

## 12. Data Storage, Encryption, and Information Security

We implement rigorous technical, administrative, and physical security measures designed to safeguard your Personal Data against unauthorized access, destruction, loss, alteration, or disclosure:

* **Encryption in Transit:** All communication between the Closed Testing mobile client, backend APIs, and external servers is encrypted exclusively using Transport Layer Security (TLS 1.2 / TLS 1.3) over HTTPS.
* **Encryption at Rest:** Sensitive database records, authentication credentials, and user media files stored within Supabase are encrypted at rest using industry-standard AES-256 encryption.
* **Access Control:** Production databases and administrative consoles are protected via strict Role-Based Access Control (RBAC), multi-factor authentication (MFA), and automated audit logging.
* **Vulnerability Monitoring:** We perform ongoing dependency audits and patch management to mitigate security vulnerabilities.

However, no method of transmission over the Internet or method of electronic storage is 100% secure. While we strive to use commercially acceptable means to protect your data, we cannot guarantee its absolute security.

---

## 13. Data Retention and Account Deletion Policy

### 13.1 Right to Erasure
In full compliance with Google Play Developer Program Policies (specifically the mandatory Account Deletion requirement) and international privacy laws, you possess the absolute right to request the permanent deletion of your account and all associated Personal Data at any time.

### 13.2 In-App Deletion Workflow
Users with the Application installed can initiate instantaneous account deletion:
1. Open the **Closed Testing** app.
2. Tap the **Settings** icon on the bottom navigation bar.
3. Scroll to the **Legal & Compliance** section.
4. Tap **"Delete Account & Data"**.
5. Read the confirmation warning and tap **"Proceed to Request"**.
6. The deletion request is immediately transmitted, your active authentication session is invalidated, and your profile is scheduled for purging.

### 13.3 Web / Email Deletion Request Procedure
If you have uninstalled the Application or are unable to access your device:
* You can access our dedicated web deletion resource: [Account Deletion Portal](https://testersarea.github.io/closed-testing/delete-account.html)
* Alternatively, send an email directly from your registered Google email account to:  
  **testersareaofficial@gmail.com**  
  **Subject Line:** `Delete My Closed Testing Account`  
  **Email Body:** State your registered Google email address and request the complete erasure of your account and personal records.

### 13.4 Scope of Deleted Data vs. Audit Retentions
Upon processing a verified deletion request:
* **Permanently Purged Within 7 to 30 Days:**
  * Your Google account identity records (Name, Email address, Avatar URL);
  * Your unique User ID and authentication tokens;
  * Your entire active testing history, streak records, and daily usage logs;
  * Your accrued tester points and credits balance;
  * Any applications you listed on the community testing market; and
  * Any uploaded feedback screenshots, bug attachments, or verification media.
* **Limited Retention Exceptions:**  
  Non-identifiable, aggregated technical metrics and cryptographically hashed anti-fraud blacklist signatures (e.g., device hashes associated with banned bots or malicious APK distributors) may be retained strictly to prevent re-registration by abusive actors and fulfill statutory legal obligations.

---

## 14. Global Privacy Rights

Depending on your geographic location, you possess specific statutory rights regarding your Personal Data:

### 14.1 European Economic Area (EEA) and UK (GDPR)
Under Articles 15–22 of the GDPR, European and UK residents have:
* **Right of Access (Art. 15):** The right to request copies of your Personal Data held by us.
* **Right to Rectification (Art. 16):** The right to request correction of inaccurate or incomplete data.
* **Right to Erasure (Art. 17):** The right to request the deletion of your Personal Data ("Right to be Forgotten").
* **Right to Restriction of Processing (Art. 18):** The right to request that we restrict processing of your data under certain conditions.
* **Right to Data Portability (Art. 20):** The right to receive your data in a structured, commonly used, machine-readable format.
* **Right to Object (Art. 21):** The right to object to our processing of your Personal Data based on legitimate interests.
* **Right to Lodge a Complaint:** The right to file a complaint with your local Data Protection Supervisory Authority.

### 14.2 California Consumer Privacy Act (CCPA / CPRA)
If you are a California resident, you possess the right to:
* Know what categories of personal information we have collected, disclosed, or shared in the preceding 12 months;
* Request the deletion of your personal information;
* Correct inaccurate personal information;
* **Non-Discrimination:** Receive equal service and pricing even if you exercise your privacy rights;
* **"Do Not Sell or Share My Personal Information":** We do not sell your personal information. If you wish to opt out of third-party targeted advertising delivered via AdMob, you can reset your Android Advertising ID or opt out via device settings: `Settings > Google > Ads > Delete Advertising ID`.

### 14.3 Indian Digital Personal Data Protection Act (DPDP Act 2023)
If you reside in the Republic of India:
* You have the right to access summaries of personal data being processed;
* You have the right to correction, completion, and erasure of personal data;
* You have the right to readily accessible grievance redressal through our designated Grievance Officer at `testersareaofficial@gmail.com`; and
* You have the right to nominate an individual to exercise your rights in the event of death or incapacity.

---

## 15. Third-Party Applications and Developer Content Disclaimer

Closed Testing acts solely as an intermediary communications and tracking platform connecting independent app developers with voluntary testers. 

* **Independent Developer Builds:** Applications submitted by community developers for testing are hosted on Google Play Console or external channels. **We do not author, build, compile, or inject code into third-party partner applications.**
* **User Discretion:** When installing and testing partner applications, you are subject to each individual developer's privacy policy and terms. We strongly encourage testers to exercise standard digital prudence when testing external pre-release software.
* **Report Violations:** If you discover that any community partner application listed on our platform contains malware, spyware, unauthorized data harvesters, or violates Google Play policies, please report it immediately to `testersareaofficial@gmail.com` for expedited removal and developer ban.

---

## 16. Statutory Disclaimer Regarding Google LLC

**Closed Testing** is an independent community utility engineered and operated exclusively by **Testers Area Team**. 

* **Non-Affiliation Notice:** Closed Testing is **NOT** affiliated with, associated with, sponsored by, endorsed by, authorized by, or in any way officially connected with **Google LLC**, Alphabet Inc., Google Play, or any of their subsidiaries or affiliates.
* **Trademark Acknowledgement:** "Google", "Android", "Google Play", "Google Play Console", and their respective logos are registered trademarks of Google LLC. All references to Google LLC and its products within our Service and documentation are made strictly for descriptive and nominative identification purposes under fair use doctrine.
* **No Guarantee of Production Track Approval:** Closed Testing assists developers in fulfilling the technical criteria of testing apps with 20 opt-in testers for 14 continuous days. However, **Closed Testing makes no guarantee, promise, or representation that Google Play Console review teams will approve your application for production access.** Final production approval decisions rest exclusively with Google LLC.

---

## 17. Children's Online Privacy Protection (COPPA / Age Restrictions)

Our Service is exclusively designed and marketed for software developers, QA professionals, and independent testers aged **13 years and older** (or 16 years for residents of the European Economic Area). 

* We do not knowingly solicit, collect, or process Personal Data from children under the age of 13.
* If we discover that an individual under the age of 13 has registered an account or provided Personal Data to our Service, we will immediately initiate procedures to permanently purge all associated data from our servers.
* If you are a parent or legal guardian and believe that your child has provided us with Personal Data without your consent, please contact our Data Protection Officer immediately at `testersareaofficial@gmail.com`.

---

## 18. Governing Law, Jurisdiction, and Dispute Resolution

* **Governing Law:** This Privacy Policy, its interpretation, and any disputes arising out of or related to the Service shall be governed by and construed in accordance with the laws of India, without regard to its conflict of law principles.
* **Amicable Negotiation:** In the event of any controversy, claim, or dispute arising out of or relating to this Privacy Policy, the parties agree to first attempt in good faith to resolve the matter through informal consultation and negotiation by contacting `testersareaofficial@gmail.com`.
* **Jurisdiction:** If informal resolution fails, any legal proceedings shall be subject to the exclusive jurisdiction of the competent courts located in India.

---

## 19. Modifications to this Privacy Policy

We reserve the right to amend, update, or replace this Privacy Policy at our sole discretion to reflect changes in our operational practices, technical architecture, or legal/regulatory requirements.

* **Notice of Updates:** When updates occur, we will revise the "Last Updated" date at the top of this Privacy Policy.
* **Material Changes:** For significant modifications that substantially alter your rights or how we handle personal data, we will provide prominent in-app notification alerts or push notices prior to the changes taking effect.
* **Binding Acceptance:** Your continued use of the Closed Testing application following the posting of an updated Privacy Policy constitutes your binding acknowledgement and acceptance of the revised terms. We encourage you to review this page periodically.

---

## 20. Data Protection Officer (DPO) and Contact Information

If you have questions, comments, grievances, or requests concerning this Privacy Policy, or if you wish to exercise any of your statutory privacy rights, please reach out to our dedicated Data Protection and Grievance Officer:

* **Application Name:** Closed Testing
* **Android Package Name:** `com.testers.closedtesting`
* **Developer Team:** Testers Area Team
* **Designated Privacy Officer:** Data Protection & Compliance Lead
* **Primary Contact Email:** [testersareaofficial@gmail.com](mailto:testersareaofficial@gmail.com)
* **Website / Legal Portal:** [https://testersarea.github.io/closed-testing/](https://testersarea.github.io/closed-testing/)
* **Account Deletion Request:** [https://testersarea.github.io/closed-testing/delete-account.html](https://testersarea.github.io/closed-testing/delete-account.html)

---
*Copyright &copy; 2026 Closed Testing (Testers Area Team). All Rights Reserved.*
