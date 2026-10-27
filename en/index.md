---
title: Bilexis - Privacy Policy
permalink: /en/
---

<div style="position: fixed; top: 16px; right: 16px; z-index: 100;">
  <a href="{{ '/tr/' | relative_url }}" style="text-decoration: none; padding: 6px 14px; border: 1px solid #ccc; border-radius: 6px; font-size: 14px; color: #333; background: #fff;">🇹🇷 Türkçe</a>
</div>

# Privacy Policy

Effective Date: 2026-03-02
Last Updated: 2026-10-27

This Privacy Policy explains the approach of **Bilexis: İngilizce Öğren** application ("Application") regarding user privacy.

## Quick Summary
- The Application allows users to create accounts (or continue as a guest) and **syncs your progress and preferences** to our secure servers.
- We collect basic **identity information** (such as email) for account creation, login, and password resetting.
- Progress and preference information (e.g., selected language, completed lessons) is **stored on our servers** to ensure a seamless experience across devices.
- In speaking exercises, your **voice is processed to recognize what you said**. When you are online, audio is streamed to our speech recognition provider (ElevenLabs); when offline, recognition happens on your device. We do not store your audio recordings.
- The Application uses **third-party services** for authentication (Google, Apple), content delivery (embedded YouTube videos), **speech recognition (ElevenLabs)**, **subscriptions and in-app purchases (Adapty)**, **product analytics (Firebase Analytics)**, **crash reporting (Firebase Crashlytics)**, **push notifications (Firebase Cloud Messaging)**, and **advertising (Google AdMob)**.
- The Application **shows advertisements**, including personalized ads based on your advertising identifier (IDFA/GAID), subject to your consent choice (see "Advertising and Tracking" below).
- We **do not sell** your personal data to third parties.

## Scope
This policy covers privacy impacts that may arise due to how the Application operates.
If a link or embedded content in the Application redirects to a third-party service (e.g., YouTube), the relevant service's own privacy policy applies.

## Data We Collect
The Application collects the following data categories to provide its core functionality:
- **Identity Information:** Email address and password (if registering directly), or basic profile information (name, email) provided by third-party authentication services (Google Sign-In, Apple Sign-In). Guest users can use the Application without providing identity information.
- **User ID:** An internal account identifier used to associate your progress, preferences, and subscription status with your account.
- **App Usage & Progress Data:** In-app progress status (e.g., completed lessons, exercise answers and results, study time, streaks) and application preferences (e.g., selected language, selected level). Feature usage is also measured via Firebase Analytics to improve the Application.
- **Voice Data (Speaking Exercises):** When you use the microphone in a speaking exercise, your voice is converted to text. If you are online, the audio is streamed directly from your device to our speech recognition provider (ElevenLabs) and is not stored on our servers; if you are offline, your device's built-in speech recognition is used. The recognized text is saved as your exercise answer.
- **Speech Recognition Diagnostics:** Technical information about each listening session (e.g., which recognition engine was used, audio signal level, connection timing, how the session ended, device model, operating system version, and app version) to detect and fix recognition problems. This does not include audio recordings.
- **Crash and Diagnostic Data:** If the Application crashes or encounters an error, Firebase Crashlytics collects a crash report (e.g., stack trace, device model, operating system version, app version) to help us fix the problem.
- **Advertising Identifier:** Your device's advertising identifier (IDFA on iOS, advertising ID on Android) is used by Google AdMob to show and measure advertisements, including personalized ads if you consent.
- **Device Identifier:** A platform-provided device identifier (Android ID on Android, identifierForVendor on iOS) is used to prevent abuse of the in-app referral/invite system (e.g., detecting the same device claiming multiple referral rewards). Our servers store only a one-way hashed form of this value.
- **Push Notification Token:** A Firebase Cloud Messaging token that allows us to send notifications to your device.
- **Purchase History:** Subscription and purchase status, managed through our subscription provider (Adapty), used to unlock premium features and restore purchases across your devices.
- **Device Information:** Secure tokens used for authentication and session management, and your time zone (used to calculate daily study limits and reminder times).

The Application **does not collect**:
- Precise or coarse location data
- Financial information such as card numbers (payments are processed by Apple/Google and our subscription provider; we do not receive or store your card details)
- Health/sensitive personal data
- Contacts, photos/media, or files
- Audio recordings (your voice is processed for recognition only and is not stored)

## How We Use Data
The data we collect is used strictly for the following purposes:
- Creating and managing your user account (including authentication and password reset).
- Maintaining and syncing your learning progress and preferences across your devices.
- Ensuring application features work correctly and personalizing your learning experience.
- Evaluating your answers in speaking exercises and improving speech recognition quality.
- Communicating with you regarding your account (e.g., password reset emails) and sending lesson reminders.
- Measuring app usage, diagnosing crashes, and improving the Application through aggregated analytics.
- Selling, managing, and restoring subscriptions and in-app purchases.
- Showing advertisements to support the free version of the Application, and preventing fraud in the referral/invite system.

## Advertising and Tracking
The Application displays ads through **Google AdMob** to support free access to the Application. Some ads may be personalized based on your advertising identifier (IDFA on iOS, advertising ID on Android).

- On iOS, the Application requests your permission via Apple's App Tracking Transparency (ATT) framework before using the IDFA for personalized advertising. If you decline, you will still see ads, but they will not be personalized based on your device's advertising identifier.
- Where required by law (e.g., in the European Economic Area and the United Kingdom), the Application asks for your consent through Google's consent message before showing personalized ads.
- You can review or change your ad tracking preference at any time in your device settings (iOS: Settings → Privacy & Security → Tracking; Android: Settings → Privacy → Ads).
- A rewarded ad format also lets you voluntarily watch an ad in exchange for additional study time; this is optional and initiated by you.
- Premium subscribers do not see ads.

## Subscriptions and Purchases
Premium features are offered through **auto-renewable subscriptions** (Bilexis Premium: monthly, quarterly, and yearly plans), processed by Apple App Store / Google Play and managed on our behalf by **Adapty**.

- The title, length, and price of each subscription are shown in the Application before purchase.
- Payment is charged to your Apple ID / Google Play account when you confirm the purchase.
- Subscriptions renew automatically at the end of each period unless cancelled at least 24 hours before the end of the current period. Your account is charged for renewal within 24 hours before the end of the current period.
- If a free trial is offered, any unused portion of the trial is forfeited when you purchase a subscription.
- You can manage or cancel your subscription in your App Store or Google Play account settings. Deleting the Application does not cancel your subscription.
- Terms of Use: on iOS, the [Apple Standard End User License Agreement (EULA)](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/) applies; on Android, the [Google Play Terms of Service](https://play.google.com/about/play-terms/) apply.

We do not directly process or store your payment card details. Adapty receives your purchase/subscription status to unlock premium features and keep them in sync across your devices.

## Data Sharing / Transfer
- The Application **does not sell** personal data to third parties.
- Your progress and profile data are sent to and securely stored on our cloud servers to provide the Application's core services.
- Limited data is shared with the service providers listed under "Third-Party Services and SDKs" below, solely to provide their respective functionality (speech recognition, analytics, crash reporting, notifications, advertising, subscriptions, authentication).

## Third-Party Services and SDKs
The Application uses the following third-party services:
- **Authentication Providers:** Google Sign-In and Apple Sign-In (for alternative login methods).
- **Content Providers:** YouTube (for embedded educational videos in lessons). When viewing embedded videos, YouTube may collect data according to its own Privacy Policy.
- **Speech Recognition:** ElevenLabs, for converting your voice to text in speaking exercises while you are online.
- **Advertising:** Google AdMob, for displaying banner, interstitial, rewarded, and app-open ads, including personalized ads where consent is given.
- **Analytics:** Firebase Analytics, for understanding feature usage and improving the Application.
- **Crash Reporting:** Firebase Crashlytics, for collecting crash reports.
- **Push Notifications:** Firebase Cloud Messaging, for delivering notifications.
- **Subscriptions:** Adapty, for managing auto-renewing subscriptions and in-app purchases across platforms.

Each of these providers may process data according to their own privacy policies:
- Google AdMob / Firebase: [https://policies.google.com/privacy](https://policies.google.com/privacy)
- ElevenLabs: [https://elevenlabs.io/privacy-policy](https://elevenlabs.io/privacy-policy)
- Adapty: [https://adapty.io/privacy](https://adapty.io/privacy)

## Permissions
The Application requires **Internet access** to connect to our servers, fetch learning materials, sync your progress, and serve advertisements. The Application may also request:
- **Microphone and Speech Recognition** access, used only for speaking exercises; if denied, the rest of the Application continues to work normally.
- **Notification** access, used for lesson reminders and account-related updates.
- **App Tracking Transparency (iOS)**, used to ask your permission before using the advertising identifier for personalized ads.

The Application does not use permissions to access your photos, contacts, or external storage to collect personal data.

## Data Retention Period
- Your account information, progress, and preferences are retained securely on our servers as long as your account is active.
- If you request to delete your account, your personal data and progress will be permanently removed from our servers in accordance with our retention policies.
- If you signed in with Apple, deleting your account also revokes the "Sign in with Apple" connection associated with your account.
- Locally cached data on your device is removed if you uninstall the application or clear the app's data.

## Data Security
We take appropriate security measures to protect your data. Authentication tokens are stored in the device's secure storage. Communications between the Application, our servers, and our service providers are encrypted. However, please note that no system or transmission over the internet can be guaranteed to be 100% secure.

## Children's Privacy
- The Application is **not designed for children under 13 years of age**.
- We do not knowingly collect personal data from anyone under 13 years of age.

If you believe a child under 13 has provided us with personal information, please contact us at the address below so we can take steps to delete such information.

## Your Rights and Options
Since the Application stores your account and progress data on our servers, you have the following rights:
- **Access and Correction:** You can view and update your profile information and preferences (such as language and level) within the application.
- **Account Deletion:** You can request the deletion of your account and all associated data by contacting us or using the in-app deletion feature (Settings → Delete Account).
- **Ad Tracking Choice:** You can opt out of personalized advertising at any time through your device's privacy settings.
- **Microphone and Notifications:** You can revoke microphone or notification access at any time in your device settings.
- **Local Data:** You can remove locally cached data by uninstalling the application.

## Changes to This Policy
This policy may be updated as needed. The current version is published on this page and within the application.
If there are significant changes to how we handle your personal data, we aim to inform you via the application or email.

## Contact
For questions about privacy, or to request account deletion, contact: info@bilexis.com
