# 🔒 Privacy Policy

### **Mini Weather: Cold Or Warm**

| Attribute | Details |
| :--- | :--- |
| **App Store Name** | **Mini Weather: Cold Or Warm** |
| **Home Screen Label** | **Mini Weather** |
| **Developer** | **Abhinav Kumar**, operating as **Apex Creators** ("I", "we", "me", "my") |
| **Contact Email** | [`abhinav.vikash2@gmail.com`](mailto:abhinav.vikash2@gmail.com) |
| **Website** | [`apexcreators.co.in`](https://www.apexcreators.co.in) |
| **Effective Date** | **August 11, 2026** |
| **Compliance** | Apple App Store Review Guidelines (§5.1.1 Data Collection & Storage) |

> [!NOTE]  
> **Privacy-First Architecture:** Mini Weather is engineered with a strict **local-first, zero-tracking design**. There are no user accounts, no sign-ups, no cloud databases, no ads, and no third-party analytics SDKs.

---

## 📑 Table of Contents

1. [Information Handling & Data Collection](#1-information-handling--data-collection)
2. [How Data Is Used](#2-how-data-is-used)
3. [Third-Party Services](#3-third-party-services)
4. [Data Retention & Deletion](#4-data-retention--deletion)
5. [Third-Party Links & Resources](#5-third-party-links--resources)
6. [Children's Privacy (COPPA & Global Standards)](#6-childrens-privacy-coppa--global-standards)
7. [User Rights & Data Control (GDPR / CCPA / Global Laws)](#7-user-rights--data-control-gdpr--ccpa--global-laws)
8. [Security](#8-security)
9. [Changes to This Privacy Policy](#9-changes-to-this-privacy-policy)
10. [Contact Us](#10-contact-us)

---

## Overview

This Privacy Policy explains what information **Mini Weather** ("the App") processes, how it is used, and the privacy controls available to you. It applies to the iOS application distributed on the Apple App Store.

The App complies with Apple's App Store Review Guidelines (Section 5.1.1 — Data Collection and Storage) and accurately reflects the **App Privacy Details** ("Nutrition Label") displayed on the App Store product page.

---

## 1. Information Handling & Data Collection

The developer does **not** operate external servers and does **not** collect, store, or transmit any personal data off your device. Per Apple App Store Data Safety declarations, the App is classified as **"No Data Collected"** because all data processing is performed ephemerally on-device solely to service real-time requests.

| Data Type | Collected Off-Device | Processed (On-Device) | Purpose | Linked to You | Used for Tracking |
| :--- | :---: | :---: | :--- | :---: | :---: |
| **Location (Precise & Coarse)** | ❌ No | ✅ Yes (Ephemeral) | Display local weather forecasts & Air Quality Index (AQI) | ❌ No | ❌ No |
| **Search Queries** | ❌ No | ✅ Yes (Ephemeral) | Resolve city/place searches via Apple geocoding services | ❌ No | ❌ No |
| **Weather & App State** | ❌ No | ✅ Yes (Local Cache) | Store forecasts & snapshots locally for offline access & widgets | ❌ No | ❌ No |
| **User Identifiers** | ❌ No | ❌ No | — | ❌ No | ❌ No |
| **Financial & Purchases** | ❌ No | ❌ No | Handled entirely & securely by Apple App Store | ❌ No | ❌ No |
| **Contacts, Photos, Health** | ❌ No | ❌ No | — | ❌ No | ❌ No |
| **Diagnostics & Analytics** | ❌ No | ❌ No | Zero analytics or telemetry SDKs integrated | ❌ No | ❌ No |
| **Advertising Data** | ❌ No | ❌ No | Zero advertisements or tracking SDKs integrated | ❌ No | ❌ No |

*All data processed on-device is non-identifiable, not linked to your identity, and never used for tracking.*

---

## 2. How Data Is Used

### 2.1 Location Services
The App requests access to your device's location solely to fetch real-time weather conditions for your current coordinate position. Coordinates are transmitted securely via encrypted HTTPS to:
- **Apple WeatherKit** — Primary weather data provider; and
- **WeatherAPI.com** — Air Quality Index (AQI) data provider & fallback source.

> [!TIP]  
> Your location is **never** used to track your movements, is **never** combined with advertising IDs, and is **never** sold or shared. You may grant, modify, or revoke location access at any time via:  
> `iOS Settings → Privacy & Security → Location Services → Mini Weather`  
> If location access is denied, the App seamlessly falls back to your manually selected city.

### 2.2 City Search
When you search for a city, your query string is sent securely to Apple's geocoding service (`CLGeocoder`) to resolve geographical coordinates. Search terms are not stored or retained.

### 2.3 Local Device Storage
The App stores the following data strictly on your device:
- Selected location name and recent search queries.
- Cached weather data & day-over-day temperature snapshots.
- User preferences (*temperature unit, distance unit, language, font style, forecast range, glass opacity, notification settings*).
- Widget state in the shared App Group container (`group.nothing_weather`) for Home & Lock Screen widgets.

**None of this locally stored data is ever transmitted off your device.**

### 2.4 Local Notifications
The optional morning weather briefing is scheduled locally on your device. The App does **not** use remote push notifications, and no notification telemetry is collected.

---

## 3. Third-Party Services

The App transmits only the minimum required non-identifiable parameters (coordinates or city name) over secure HTTPS to the following third-party APIs:

| Provider | Purpose | Privacy Policy |
| :--- | :--- | :--- |
| **Apple WeatherKit** | Primary weather data provider | [Apple Privacy Policy](https://www.apple.com/legal/privacy/) |
| **Apple Geocoding (`CLGeocoder`)** | Resolving city names & country codes | [Apple Privacy Policy](https://www.apple.com/legal/privacy/) |
| **WeatherAPI.com** | Air Quality Index & fallback forecast data | [WeatherAPI.com Privacy Policy](https://www.weatherapi.com/privacy.aspx) |

All communication occurs strictly over encrypted Transport Layer Security (**TLS / HTTPS**).

---

## 4. Data Retention & Deletion

- **Zero Server Retention:** The developer operates no central databases or user servers; therefore, no user data is retained off-device.
- **Local Erasure:** All app data lives locally on your device. You can permanently erase all stored app data at any time by **uninstalling the App** or clearing storage via:  
  `iOS Settings → General → iPhone Storage → Mini Weather → Delete App`
- **No Account Flow Required:** Because Mini Weather does not feature user accounts, Apple's in-app account deletion mandate (Guideline 5.1.1(v)) does not apply.

---

## 5. Third-Party Links & Resources

The App may contain links to external web pages (such as open-source documentation or developer pages). The developer is not responsible for the content or privacy practices of third-party websites. Users are encouraged to review the policies of external sites upon visiting.

---

## 6. Children's Privacy (COPPA & Global Standards)

Mini Weather is rated **4+** and does not knowingly collect, solicit, or store personal information from children under the age of 13 (or 16 in the European Economic Area). Because all processing is conducted locally on-device without personal data collection, no children's data is gathered or shared.

If you believe a child has provided information through the App, please contact the developer, and any such local data will be promptly addressed.

---

## 7. User Rights & Data Control (GDPR / CCPA / Global Laws)

Under global privacy frameworks — including the **GDPR**, **CCPA / CPRA**, **LGPD**, and **PIPEDA** — you maintain full authority over your data:

- 👁️ **Right to Access & Review:** View all cached settings and preferences directly in the App's Settings screen.
- 🗑️ **Right to Erasure / Deletion:** Permanently delete all local data by removing the App or clearing app storage in iOS Settings.
- ⚙️ **Right to Revoke Permissions:** Revoke location access (`iOS Settings → Privacy & Security → Location Services`) or disable notifications at any time.
- 🚫 **Do Not Sell or Share Personal Data:** We do **not** sell, rent, or share personal data under any circumstances.
- ✉️ **Privacy Inquiries:** Send privacy questions directly to the developer contact listed below.

---

## 8. Security

Security is built directly into the App's architecture:
- **No Central Database:** Zero cloud databases or servers to compromise.
- **iOS Sandbox Protection:** All local state is stored inside iOS's sandboxed, encrypted-at-rest container.
- **Encrypted In-Transit:** 100% of network traffic uses TLS 1.3 / HTTPS encryption.
- **In-Context Permissions:** Location access is requested explicitly and can be restricted to *"While Using the App"*.

---

## 9. Changes to This Privacy Policy

This Privacy Policy may be updated periodically to reflect software enhancements or regulatory changes. Revisions will be indicated by the **Effective Date** at the top of this document and published within the App and on the official website.

---

## 10. Contact Us

For any privacy-related questions, feedback, or legal inquiries, please contact:

| Channel | Contact Details |
| :--- | :--- |
| **Developer** | **Abhinav Kumar**, operating as **Apex Creators** |
| **Email** | [`abhinav.vikash2@gmail.com`](mailto:abhinav.vikash2@gmail.com) |
| **Official Website** | [`apexcreators.co.in`](https://www.apexcreators.co.in) |
| **Online Policy Link** | [`weareapexcreators.github.io/policies/mini_weather.md`](https://weareapexcreators.github.io/policies/mini_weather.md) |

---

<p align="center">
  <i>© 2026 Abhinav Kumar / Apex Creators. All rights reserved.</i>
</p>
