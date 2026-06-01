# Privacy Policy 🔒

<div align="center">
  <h3>NetPulse — Network Data Tracker</h3>
  <p><strong>Last Updated: June 1, 2025</strong></p>
  <p><strong>Effective Date: June 1, 2025</strong></p>
</div>

---

## Overview

This Privacy Policy describes how **NetPulse** ("the App", "we", "us", or "our") handles your information. NetPulse is developed and maintained by a single independent developer.

> **Short version:** NetPulse does not collect, store, transmit, or share any personal data. Everything stays on your device.

---

## 1. Information We Collect

### 1.1 Data We Do NOT Collect

NetPulse does **not** collect, transmit, or store any of the following:

- Personal identification information (name, email, phone number, etc.)
- Location data
- Device identifiers (IMEI, advertising ID, etc.)
- Browsing history or internet activity
- Contacts, messages, or media
- Crash logs or analytics
- Any data from third-party services

### 1.2 Data Accessed On-Device

NetPulse reads the following information **locally on your device only**, solely to provide its core functionality:

| Data Accessed | Purpose | Leaves Your Device? |
|---------------|---------|-------------------|
| Per-app network usage statistics | Display data consumption per app | ❌ Never |
| Installed app names and icons | Identify apps in the usage list | ❌ Never |
| Active network connection type (WiFi / Mobile) | Determine which network is in use | ❌ Never |
| SIM slot information (dual-SIM devices) | Attribute usage to the correct SIM | ❌ Never |

All data accessed by NetPulse is read from Android's system APIs, processed in memory, and displayed to you. **None of this data is written to external servers, cloud services, or shared with any third party.**

---

## 2. Permissions Explained

NetPulse requests the following Android permissions. Each permission is used solely for the purpose described below:

### `PACKAGE_USAGE_STATS`
- **What it does:** Allows the app to read per-app network usage statistics from Android's `NetworkStatsManager`.
- **Why it's needed:** This is the core permission required to show you how much data each app has consumed.
- **How it's used:** Data is read locally and displayed in the app. It is never transmitted anywhere.

### `READ_PHONE_STATE`
- **What it does:** Allows the app to detect the active SIM and mobile network state.
- **Why it's needed:** Required on dual-SIM devices to correctly attribute mobile data usage to the right SIM slot.
- **How it's used:** Only the network subscription ID is read. No call logs, phone numbers, or IMEI are accessed or stored.

### `ACCESS_NETWORK_STATE`
- **What it does:** Allows the app to check whether the device is connected to WiFi or mobile data.
- **Why it's needed:** Used to display the current connection type and apply the correct filter in the dashboard.
- **How it's used:** The connection state is read in real time and never stored or transmitted.

### `POST_NOTIFICATIONS` *(Android 13+ only)*
- **What it does:** Allows the app to send local notifications.
- **Why it's needed:** Used exclusively to alert you when your data usage approaches a threshold you have configured.
- **How it's used:** All notifications are generated locally. No notification content is sent to any server.

> ⚠️ **NetPulse does not request the `INTERNET` permission.** It is architecturally incapable of sending any data off your device.

---

## 3. Data Storage

All data displayed in NetPulse — including your configured thresholds, display preferences, and cached usage summaries — is stored exclusively in your device's local storage using Android's Room database (SQLite).

- No cloud sync is performed.
- No remote database is used.
- Uninstalling the app permanently deletes all locally stored data.

---

## 4. Third-Party Services

NetPulse does **not** integrate any third-party SDKs, analytics platforms, advertising networks, or crash reporting tools. The following are explicitly not used:

- Google Analytics / Firebase Analytics
- Facebook SDK
- Crashlytics or any crash reporting service
- AdMob or any advertising SDK
- Any other third-party data collection service

---

## 5. Children's Privacy

NetPulse does not knowingly collect any personal information from anyone, including children under the age of 13. Since the app collects no personal data whatsoever, it poses no privacy risk to users of any age.

---

## 6. Security

Since NetPulse does not transmit any data over a network, there is no risk of interception or data breach through network communication. All locally stored preferences and cached data reside in your device's sandboxed private storage, accessible only to the app itself.

---

## 7. Your Rights

Because NetPulse does not collect or store any personal data on external servers, there is no user profile, account, or database entry associated with you anywhere outside your device.

- **Right to Access:** All data is already on your device — you can view it in the app at any time.
- **Right to Deletion:** Uninstalling NetPulse removes all app data permanently from your device.
- **Right to Portability:** Not applicable, as no data is held externally.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by updating the **Last Updated** date at the top of this document. Continued use of the app after any changes constitutes acceptance of the updated policy.

We encourage you to review this policy periodically. Significant changes will also be noted in the app's release notes on the Google Play Store.

---

## 9. Open Source & Transparency

NetPulse's source code is available for review. You are welcome to inspect how network data is accessed, processed, and displayed to verify the claims made in this privacy policy.

---

## 10. Contact

If you have any questions, concerns, or requests regarding this Privacy Policy, please reach out:

- **Developer:** Independent Developer (Ayush Aryan)
- **Email:** ayusharyan.online@gmail.com
- **Twitter:** https://x.com/hypfridie

We aim to respond to all privacy-related inquiries within **7 business days**.

---

## 11. Governing Law

This Privacy Policy is governed by the laws of India. By using NetPulse, you agree to the jurisdiction of courts located in India for any disputes arising from this policy.

---

<div align="center">
  <p>NetPulse respects your privacy. No accounts. No servers. No tracking.</p>
  <p><strong>Your data stays on your device — always.</strong></p>
</div>
