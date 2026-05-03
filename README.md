# ScribeShare Privacy Policy

**Last Updated:** March 22, 2026

## Overview

ScribeShare ("the Extension," "we," "us," or "our") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, share, and protect your information when you use ScribeShare.

ScribeShare is a Chrome extension designed to help students summarize Canvas course content and organize follow-up actions using Google Calendar reminders and Google Drive folders. This Privacy Policy applies to all aspects of the Extension, including its installation, use, and any features or services it provides.

---

## 1. Data Collection

### 1.1 Information We Collect

ScribeShare collects the following types of user data:

#### Authentication Data
- **Google Account Information:** Email address, display name, and profile picture obtained through the Chrome Identity API and Google OAuth 2.0 authentication
- **Authentication Tokens:** OAuth access tokens used to authenticate API requests to Google services

#### Canvas Course Information
- **Course Context:** Course names, course IDs, and course URLs detected from Canvas pages you visit
- **Course Content:** Text and context from Canvas pages used for summarization workflows

#### Calendar and Reminder Data
- **Calendar Events:** Event titles, descriptions, dates, times, and associated reminders that you create through ScribeShare
- **Reminder Settings:** Reminder timing preferences and notification configurations

#### Drive Organization Data
- **Folder Structure:** Names and IDs of Google Drive folders created by ScribeShare to organize your course materials
- **Folder References:** Links and metadata associated with Drive folders

#### Browser Storage Data
- **Local Extension Storage:** Connection status flags, user preferences, selected courses, and UI navigation state stored in Chrome's local storage

### 1.2 Data We Do Not Collect

- Financial or payment information
- Health information
- Precise geolocation data
- Password information
- Unnecessary browsing history beyond Canvas pages you actively interact with

---

## 2. How We Use Your Data

### 2.1 Primary Purposes

We use the collected data exclusively to provide ScribeShare's core functionality:

1. **Authentication & Account Management:** Verify your identity and maintain your account session
2. **Canvas Summarization:** Process Canvas course content to generate study summaries upon your request
3. **Google Calendar Integration:** Create calendar events and manage reminders for your course deadlines and tasks
4. **Google Drive Organization:** Create and organize folders in your Google Drive to store course-related materials
5. **Local Preferences:** Save your navigation state, selected courses, and configuration preferences within the extension

### 2.2 Limited Use Compliance

ScribeShare adheres to the Chrome Web Store Limited Use Policy. We limit our use of data in the following ways:

- **Single Purpose:** Data is used exclusively to provide the summarization, calendar, and Drive organization features described in the extension listing
- **No Secondary Uses:** We do not use your data for advertising, analytics, affiliate programs, credit determination, or any purpose unrelated to the extension's core functionality
- **No Third-Party Sharing:** Data is not shared with advertisers, data brokers, or other third parties, except as necessary to communicate with Google APIs to provide requested features
- **No Human Review:** Your data is not read by humans except when necessary for security investigations or as required by law

---

## 3. Data Sharing

### 3.1 Third-Party Services

Your data is shared with the following third parties only to provide the extension's advertised functionality:

#### Google Services (via OAuth and APIs)
- **Google Identity:** Handles your authentication. We share your email and basic profile information
- **Google Drive API:** Receives your authentication token and folder creation requests. Google stores the folders and files you create
- **Google Calendar API:** Receives your authentication token and event/reminder data. Google stores the calendar events and reminders you create
- **Firebase (Optional Backend):** If enabled, your user profile and event sync data may be stored on Google's Firebase servers for cross-device synchronization

#### Canvas (Instructure)
- **Course Detection:** ScribeShare accesses Canvas pages in your browser using the content script. Canvas receives only the standard requests your browser makes; no additional data is sent to Canvas by the extension

### 3.2 Data Sharing Limitations

- Data is only transferred to the parties listed above when necessary to provide requested features
- Transfer occurs only over encrypted (HTTPS) connections
- We do not sell, rent, or transfer your data to advertisers, data brokers, or marketing partners
- We do not share data in connection with affiliate programs or incentive schemes

### 3.3 Legal and Security Exceptions

We may disclose your data if required by law, court order, or government request, or to:
- Protect against fraud, security threats, or abuse
- Investigate violations of this Privacy Policy or extension terms
- Comply with applicable legal obligations

---

## 4. Data Storage and Security

### 4.1 Where Data is Stored

- **Local Storage:** Most of your data (preferences, selected courses, event records) is stored locally in your browser using Chrome's Storage API. This data is encrypted at rest by your browser and device
- **Google Services:** Data transmitted to Google (authentication info, Drive folders, Calendar events) is stored according to Google's data handling and security practices
- **Firebase (if used):** User profile and sync metadata may be stored on Google Firebase servers with encryption in transit and at rest

### 4.2 Security Measures

- All communication with Google APIs uses modern cryptography (TLS/HTTPS)
- Authentication tokens are stored securely and never transmitted without encryption
- The extension does not hardcode sensitive information or expose credentials
- Source code is minified but not obfuscated, allowing for transparent security review

### 4.3 Data Retention

- **Local Data:** Remains in your browser's storage until you manually delete it or uninstall the extension
- **Google Drive Folders & Files:** Persist in your Google Drive indefinitely until you delete them
- **Calendar Events & Reminders:** Persist in your Google Calendar indefinitely until you delete them
- **Authentication Tokens:** Are cached locally and cleared when you sign out or uninstall the extension

---

## 5. Your Rights and Control

### 5.1 Access and Deletion

You have the right to:
- **Access:** View all data ScribeShare stores locally by checking Chrome's Developer Tools (F12 > Application > Storage)
- **Delete:** Remove individual calendar events, Drive folders, or course selections through the extension UI
- **Revoke Access:** Remove the extension entirely from Chrome, which deletes all local data and revokes its access to your Google account

### 5.2 Managing Permissions

- You can review and revoke ScribeShare's access to your Google Account through [your Google Account security settings](https://myaccount.google.com/permissions)
- You can adjust which permissions the extension requests in your browser's extension settings

### 5.3 Cookies and Tracking Technologies

- ScribeShare does not use cookies, pixels, or other tracking technologies for analytics, advertising, or behavioral profiling
- Google services you integrate with (Drive, Calendar) may use their own tracking and analytics features, subject to their privacy policies

---

## 6. Google API Limited Use Disclosure

**Important:** ScribeShare's use of information received from Google APIs adheres to the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies#protecting-user-privacy), including the Limited Use requirements. ScribeShare will not transfer user data to third parties except:

- As necessary to provide the features described (Drive folder creation, Calendar event management)
- To comply with applicable law
- As part of a merger, acquisition, or sale of assets, with your prior explicit consent

Your data is not used for personalized advertising, credit/lending decisions, or any purpose unrelated to providing the summarization, calendar, and Drive organization features.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy to reflect changes in our practices or applicable law. If we make material changes, we will notify you by:
- Updating the "Last Updated" date at the top of this policy
- Sending an email notification to your registered Google account (if applicable)
- Posting a notice in the extension

Your continued use of ScribeShare after changes constitute your acceptance of the updated policy.

---

## 8. Contact & Support

If you have questions about this Privacy Policy, your data, or ScribeShare's privacy practices, please contact:

**Developer:** ScribeShare
**Email:** \[Placeholder\]
**Repository:** [ScribeShare GitHub](https://github.com/antoine-mcm/ScribeShare)

For additional privacy resources:
- [Chrome Web Store Privacy FAQ](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google Workspace Privacy Notice](https://workspace.google.com/terms/privacy.html)

---

## 9. Compliance

This privacy policy complies with:
- **Chrome Web Store Developer Program Policies**, including Limited Use and data handling requirements
- **GDPR** (General Data Protection Regulation) principles for EU users
- **CCPA** (California Consumer Privacy Act) principles for California residents
- Industry best practices for extension privacy and security

---

**By installing and using ScribeShare, you acknowledge that you have read, understood, and agreed to this Privacy Policy.**
