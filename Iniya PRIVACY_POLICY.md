# Privacy Policy for Iniya

**Last updated:** June 19, 2026

## Overview

Iniya ("the App") is a Tamil festival greeting card maker developed for Android. This Privacy Policy explains how the App collects, uses, and protects your information. By using the App, you agree to the practices described in this policy.

## Information We Collect

### Information You Provide
- **Your Name:** When you enter your name to personalize greeting cards, it is stored locally on your device only. It is never transmitted to any server.

### Information Collected Automatically
- **Advertising Data:** The App uses Google AdMob to display advertisements. Google AdMob may collect device identifiers, IP address, and ad interaction data. This data is collected and processed by Google under their privacy policy.
- **Ad Consent Preferences:** Your consent choices for personalized advertising are stored locally and shared with Google's User Messaging Platform.
- **Analytics:** The App does not use any analytics or tracking services beyond what is included in the Google AdMob SDK.

### Information We Do NOT Collect
- We do not collect personal information such as email, phone number, or location.
- We do not collect photos, contacts, or any data from your device.
- We do not have user accounts or authentication.
- We do not transmit any user data to our servers (the App works entirely offline for its core functionality).

## Third-Party Services

The App uses the following third-party services:

### Google AdMob
- **Purpose:** To display banner, interstitial, native, rewarded, and app open advertisements.
- **Data Collected:** Device advertising ID, IP address, device information, ad interaction data.
- **Privacy Policy:** [Google Privacy Policy](https://policies.google.com/privacy)
- **Ad Personalization:** Users can opt out of personalized ads through their device settings (Settings > Google > Ads > Opt out of Ads Personalization).
- **Rewarded Ads:** Certain premium templates can be unlocked by watching a rewarded advertisement. This is entirely voluntary and no personal data is collected by the App during this process.

### Google User Messaging Platform (UMP)
- **Purpose:** To obtain consent for personalized advertising in compliance with GDPR and other privacy regulations.
- **Data Collected:** Consent preferences.
- **Behavior:** If consent is not granted, the App will not initialize the advertising SDK and no ads will be shown.

## Data Storage

All data is stored locally on your device. We do not operate any servers or cloud storage. Specifically:

- **User preferences** (name, font choice, color choice) are stored using Android SharedPreferences.
- **Notification settings** (enabled/disabled toggles, quiet hours, last app open timestamp) are stored using Android SharedPreferences.
- **Unlocked template records** (IDs of templates unlocked via rewarded ads) are stored using Android SharedPreferences.
- **Ad frequency data** (daily ad count, last ad show timestamp) is stored using Android SharedPreferences to enforce responsible ad frequency caps.
- **Greeting card templates** are bundled within the App and loaded from local storage.
- No data is stored on external servers.

## Notifications

The App may send local notifications in the following categories:

- **Daily Thirukkural Quotes:** A daily wisdom quote from Thirukkural, delivered in the morning.
- **Festival Reminders:** Countdown notifications before major Tamil festivals (up to 7 days in advance, and on the festival day).
- **New Template Alerts:** Notifications about newly available greeting card templates.
- **Re-engagement Reminders:** Gentle reminders if you have not used the App for 3 or more days. This category is disabled by default and automatically stops after 30 days of inactivity.

All notifications are generated locally on your device using Android WorkManager. No push notification service or external server is used. Notifications respect quiet hours (configurable in the App) and are capped at 2 per day across all categories.

You can:
- Disable any notification category individually in the App's Settings screen.
- Disable all notifications at once using the master toggle in Settings.
- Revoke the notification permission entirely through Android system settings.

## Children's Privacy

The App is not directed at children under 13. We do not knowingly collect personal information from children under 13. If you believe a child under 13 has provided personal information through the App, please contact us so we can take appropriate action. The App displays advertisements that comply with Google AdMob's policies for general audiences.

## Permissions

The App requests the following Android permissions:

- **Internet (`INTERNET`):** Required for loading advertisements and displaying the ad consent form.
- **Network State (`ACCESS_NETWORK_STATE`):** Required to check network connectivity before attempting to load ads.
- **Notifications (`POST_NOTIFICATIONS`, Android 13+):** Required to send local notifications. You can deny this permission and still use all other features of the App normally.
- **Boot Completed (`RECEIVE_BOOT_COMPLETED`):** Required to reschedule local notifications after your device restarts. No data is sent anywhere during this process.
- **Storage (`WRITE_EXTERNAL_STORAGE`, Android 9 and below only):** Required to save greeting cards to your photo gallery on older Android versions. On Android 10 and above, the App uses scoped storage and does not need this permission.

## Data Sharing

We do not sell, trade, or share your personal data with any third parties. The only third-party data sharing occurs through the Google AdMob SDK as described above, and only when you have provided consent (or when consent is not required in your region).

When you use the share feature to send a greeting card, the App uses Android's standard sharing mechanism to pass the generated image to your chosen messaging app (such as WhatsApp, Telegram, or others). The App does not retain or transmit any information about your sharing activity.

## Your Rights

### For All Users
You can:
- **Delete your data:** Uninstalling the App removes all locally stored data (preferences, unlocked templates, notification settings, and ad frequency data).
- **Clear app data:** Through Android Settings > Apps > Iniya > Clear Data to reset all preferences without uninstalling.
- **Opt out of personalized ads:** Through your Android device settings (Settings > Google > Ads > Opt out of Ads Personalization).
- **Disable notifications:** Through the App's Settings screen or Android system settings.
- **Withdraw ad consent:** You can reset your consent choices by clearing the App's data through Android Settings.

### For Users in the European Economic Area (EEA)
Under the General Data Protection Regulation (GDPR), you also have the right to:
- **Access:** Request information about data processed by the App.
- **Rectification:** Correct any inaccurate data (you can edit your name directly in the App).
- **Erasure:** Delete all your data by uninstalling the App or clearing its data.
- **Restriction of processing:** Opt out of personalized ads and disable notifications.
- **Object:** Object to data processing for advertising purposes through your device settings.
- **Data portability:** Since all data is stored locally on your device, you already have full control over it.

The legal basis for processing data through the AdMob SDK is your consent, which is obtained through the Google User Messaging Platform consent form before any ads are loaded.

## Data Retention

All data is stored locally on your device for as long as the App is installed. Uninstalling the App or clearing its data permanently removes all stored information. We do not retain any data on servers.

## Security

The App does not transmit personal data over the internet. All user data is stored locally using Android's standard SharedPreferences mechanism, which is sandboxed to the App and not accessible by other applications. The App enforces `usesCleartextTraffic="false"` to ensure all network communication (for ads) uses encrypted HTTPS connections.

## Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected in the "Last updated" date at the top of this page. We encourage you to review this policy periodically.

## Contact Us

If you have questions about this Privacy Policy or wish to exercise your data rights, please contact us at:

**Email:** sandhya@beforethemachines.in

---

*This privacy policy applies to the Iniya app available on Google Play Store.*
