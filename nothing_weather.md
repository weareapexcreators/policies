# Privacy Policy for Nothing Weather: Warm or Cold

**Effective Date:** 21 February 2026

## 1. Introduction

Welcome to **Nothing Weather: Warm or Cold** (the "App"), developed by **Apex Creators** ("we," "us," or "our"). We value your privacy and are committed to providing a transparent experience for all users.

**Disclaimer:** "Nothing Weather: Warm or Cold" is an independent application developed by Apex Creators. It is **not** affiliated with, endorsed by, sponsored by, or in any way officially connected with **Nothing Technology Limited** or any of its subsidiaries or affiliates. The word "Nothing" in the app name reflects a minimalist design philosophy and does not imply any brand association.

This Privacy Policy explains how information is accessed, used, and stored when you use the App.

## 2. Information We Collect

The App does not collect, transmit, or store any personally identifiable information (PII) such as your name, email address, or phone number on any external server.

The App interacts with your device and third-party services as described below.

## 3. Data Stored Locally on Your Device

The App uses on-device storage (Android SharedPreferences) to save your preferences and cache data for a better experience. The following data is stored **locally on your device only** and is never transmitted to our servers:

*   **Manual city name** (if you manually select a location)
*   **Last known GPS coordinates** (latitude and longitude, cached temporarily for location-change detection to avoid unnecessary API calls)
*   **Cached weather data** (JSON response from the weather API, for offline access and faster load times; expires after 6 hours)
*   **Yesterday's temperature** (cached for the "warmer or colder" comparison feature)
*   **Temperature unit preference** (Celsius or Fahrenheit)
*   **App language preference**
*   **Font style preference**
*   **Daily notification preference** (enabled or disabled)
*   **Onboarding completion status**

All of this data can be cleared at any time by clearing the App's data or uninstalling the App.

## 4. Location Data Usage

The App requests access to your device's location (both `ACCESS_FINE_LOCATION` and `ACCESS_COARSE_LOCATION` Android permissions) to provide weather data for your current position.

*   **GPS Data:** Your precise location is used to fetch weather data from our weather data provider. Your last-known coordinates are cached locally on your device (as described in Section 3) for location-change detection. This data is **not** sent to any server controlled by us.
*   **Manual Location:** If you manually select a city, the city name is saved locally on your device.
*   **User Control:** You can revoke location access at any time through your device's system settings. If location access is disabled, you can still use the App by manually searching for a city.

## 5. Advertising & Third-Party Services

### 5.1 Google AdMob

The App displays interstitial advertisements using **Google AdMob** (via the Google Mobile Ads SDK). The App declares the `com.google.android.gms.permission.AD_ID` permission in its Android Manifest, which allows the Google Mobile Ads SDK to access the Android Advertising ID.

Google AdMob may collect and process data including:
*   **Advertising ID** (Android Advertising ID)
*   **Device information** (device model, OS version, network type)
*   **Ad interaction data** (views, clicks)
*   **App performance and diagnostics data**

For details on what data Google collects and how it is used, please refer to:
*   [Google Privacy Policy](https://policies.google.com/privacy)
*   [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**For users in the European Economic Area (EEA), UK, and Switzerland:**
The App implements Google's **User Messaging Platform (UMP) SDK** to request consent before serving ads, in compliance with the GDPR and ePrivacy Directive. If consent is required, a consent form will be presented when you first open the App. You can manage or revoke your consent at any time via the **"Ad Privacy"** option in the App's Settings screen (this option only appears for users in applicable regions).

### 5.2 WeatherAPI.com

The App uses **WeatherAPI.com** to retrieve weather data. When making a request, the App sends your coordinates (latitude and longitude) or your manually-selected city name to the WeatherAPI.com servers. No other personal information is shared with this provider.
*   [WeatherAPI.com Privacy Policy](https://www.weatherapi.com/privacy.aspx)
*   [WeatherAPI.com Terms of Service](https://www.weatherapi.com/terms.aspx)

## 6. Notifications

The App uses **local notifications only** (via the `flutter_local_notifications` package). These notifications are scheduled and displayed entirely on your device. No push notification service or remote server is involved. You can enable or disable daily morning weather notifications from the App's Settings screen, or disable notifications entirely via your device's system settings.

## 7. Home Screen Widgets

The App provides home screen widgets that display weather information. Widget data (such as temperature, weather description, and location name) is stored locally on your device using the Android widget framework. No data is transmitted externally for widget functionality.

## 8. Data Security

All network requests made by the App (to WeatherAPI.com and Google AdMob) are transmitted over secure **HTTPS** connections. The App does not operate its own backend servers and does not store any user data externally.

## 9. Children's Privacy

We do not knowingly collect personal information from children under 13. The App does not have any age-gating mechanism or user accounts.

## 10. Changes to This Privacy Policy

We may update this Privacy Policy to reflect changes in our practices or applicable regulations. Any changes will be posted on this page with an updated effective date. Continued use of the App after changes are posted indicates acceptance of the revised policy.

## 11. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us:

*   **Website:** [https://apexcreators.co.in](https://apexcreators.co.in)
*   **Email:** info@apexcreators.co.in
