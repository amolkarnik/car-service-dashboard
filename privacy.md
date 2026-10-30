---
title: Privacy Policy — Car Service Dashboard
---

# Privacy Policy for Car Service Dashboard

**Last Updated:** October 2026

Car Service Dashboard is an independent vehicle maintenance and expense tracking application developed by Amol Karnik for iOS and macOS. The developer does not collect or receive your garage records, and the application contains no developer analytics or telemetry. Some Apple platform services described below may process or sync data when you use them.

## 1. Invoice Processing and Apple Private Cloud Compute

Invoice text extraction, OCR, and cleanup run on your device. Invoice summaries use Apple Foundation Models on-device when available. Apple Private Cloud Compute (PCC) is enabled by default as a fallback when an on-device summary cannot fit the model's context limit or local generation fails.

When that fallback is used, the app may send the cleaned invoice text and known garage provider names included in the summary prompt to Apple's PCC service. The app sends this text for summarization; the invoice PDF or scanned page images are not sent through this invoice-summary route. Apple processes PCC requests under Apple's privacy and security practices. The developer does not receive the request or its response.

You can prevent invoice-summary PCC requests in **Settings → Invoice AI Processing → On-device only**. This preference is off by default, so PCC remains enabled when needed. With **On-device only** enabled, summaries remain on-device when Apple Intelligence can complete them; otherwise the app falls back to its rules-based summary. The preference is stored in the app's local settings.

## 2. Other Processing and Diagnostics

The app uses Apple's Vision and VisionKit frameworks for on-device document text recognition and scanning. Search uses a local SQLite index and on-device embeddings. Ask Assistant uses the app's local search and Apple's Foundation Models framework; the invoice-summary PCC preference described above applies to invoice summaries.

The application does not include third-party analytics, advertising, or tracking SDKs and does not send garage data to a developer-operated server. Crash reports or diagnostics collected by Apple are governed by your device settings and Apple's policies.

## 3. Storage and iCloud Synchronization

With the built-in storage location, vehicle records and attached invoice PDFs are stored in the app's Application Support area. You may instead choose a custom folder, whose storage and sync behavior depends on that location.

When iCloud is available and enabled for the app, the vehicle ledger and attached invoice PDFs in the app's iCloud container can sync across your Apple devices through Apple's iCloud services. The developer does not have access to your iCloud account or container. Search indices remain in local app storage and are not part of this sync.

## 4. Hardware Permissions

The app requests camera access on iOS when you choose **Scan Receipt**. The camera is used to capture a paper invoice and create a PDF attachment in your selected garage storage location.

## 5. Local Preferences

The app stores preferences with `UserDefaults`, including appearance choices and the **On-device only** invoice AI preference.

## 6. Third-Party Links

Links to the App Store, support site, or developer repository open external services governed by their own privacy policies.

## 7. Contact

- **Developer:** Amol Karnik
- **Email:** amol.m.karnik@gmail.com
- **Support:** https://amolkarnik.github.io/car-service-dashboard/support
- **Website:** https://amolkarnik.github.io/car-service-dashboard/
