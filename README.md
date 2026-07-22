# Privacy Policy

**Last updated: July 2026**

## Overview

ScrollEarn ("we", "our", or "the app") respects your privacy. This policy explains what data we collect, how we use it, and your rights.

## Data We Collect

### Accessibility Service Data
ScrollEarn uses Android's Accessibility Service solely to:
- Detect which app is currently in the foreground (package name only)
- Track time spent in monitored apps
- Perform back-button actions when your scroll budget is exhausted

**We do NOT read screen content, keystrokes, passwords, credit card numbers, or any other sensitive data.**
**We do NOT transmit any data read via the Accessibility Service off your device.**

### Activity Recognition
With your permission, we access the step counter sensor to calculate walking-based earn. This data is processed entirely on-device.

### Usage Data Stored On-Device
All data is stored locally on your device using Room database and DataStore preferences:
- Scroll sessions (app package names, timestamps, duration)
- Earn actions (focus/walking sessions, timestamps, points earned)
- Daily totals and streaks
- App settings and preferences

### Crash Reporting (Firebase Crashlytics)
ScrollEarn uses Firebase Crashlytics for crash reporting. When the app crashes, the following non-personal data may be transmitted:
- Crash trace and device state (OS version, device model, app version)
- No personal information, user IDs, or usage data is included

This requires the `INTERNET` permission. Crash reporting is enabled only in release builds.

## How We Use Data

- To calculate your scroll budget and time remaining
- To track your earn activities and streaks
- To show you statistics about your phone usage
- To enforce time limits on monitored apps

## Data Sharing

We do not sell, trade, or share your personal data with third parties. The app uses Firebase Crashlytics (Google) solely for crash reporting in release builds. No analytics, advertising, or tracking SDKs are included.

## Data Retention

Data is retained on your device indefinitely until you uninstall the app or clear app data. There is no cloud backup or sync.

## Your Rights

Since all data is stored locally, you can:
- View all your data within the app's Stats screen
- Delete all data by clearing app storage or uninstalling

## Children's Privacy

This app is not directed at children under 13. We do not knowingly collect data from children.

## Changes to This Policy

We may update this policy. Changes will be posted here with an updated date.

## Contact

For questions about this policy, email: scrollearnapp@gmail.com

## Google Play Required Disclosures

### Accessibility Service
- **Purpose**: ScrollEarn uses the Accessibility Service exclusively to detect foreground app changes for scroll time tracking. The service reads only the package name of the currently focused app. No screen content, user input, or personal data is accessed.
- **Data handling**: All data read by the Accessibility Service (package names, timestamps) is stored locally on-device only. No data is transmitted, shared, or uploaded.
- **User consent**: Explicit consent is obtained during onboarding before the service can be enabled. Users can disable the service at any time via system Settings > Accessibility.

### Usage Stats Permission (PACKAGE_USAGE_STATS)
- **Purpose**: Used as a backup to detect the foreground app if the Accessibility Service is unavailable on some devices. Only the current foreground package name is read.
- **Data handling**: Queried locally; no data is transmitted off-device.
- **User control**: Users must grant this permission manually via system Settings > Apps > Special app access > Usage access. It can be revoked at any time.

## Data Safety Section (Google Play)

- **App info and performance (Crash logs)**: Firebase Crashlytics collects crash traces and device state for crash fixing.
- **No personal data collected**: No names, emails, or identifiers are collected or transmitted.
- **Third-party SDKs**: Firebase Crashlytics (Google) for crash reporting only.
- **INTERNET permission**: Used exclusively for Firebase Crashlytics crash reports in release builds.
- **All scroll/earn data remains on-device**: No usage data is transmitted off your device.
