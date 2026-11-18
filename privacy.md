---
title: Privacy Policy, Car Service Dashboard
---

# Privacy Policy for Car Service Dashboard

**Last Updated:** November 2026

Car Service Dashboard is an independent app for tracking vehicle maintenance and expenses, developed by Amol Karnik for iOS and macOS. The developer does not collect or receive your garage records, and the app has no developer analytics or telemetry. Some Apple services described below process or sync data when you use them.

## 1. Ask and Apple Private Cloud Compute

Ask answers questions about your service history and spending. It uses Apple Private Cloud Compute (PCC), Apple's server-based Apple Intelligence service.

Ask is off until you turn it on. The app shows what Ask sends before you turn it on, and you can turn it off at any time in **Settings > Ask**. When Ask is off, the app does not send anything for Ask.

When you ask a question, the app will send to Apple's PCC service:

- your question;
- for the vehicles you have selected, each saved visit's date, cost, odometer reading, service provider and service descriptions;
- spending totals for those vehicles.

Ask does not send VINs, license plates, notes, receipts, invoice files or file names. Provider and service text is sent as saved, so anything you typed into those fields is included.

Each question is sent on its own. Earlier questions and answers are not sent again. Apple processes PCC requests under Apple's privacy and security practices. The developer does not receive the request or the answer.

## 2. Invoice processing

Invoice text recognition, field extraction and cleanup run on your device. Invoice summaries use Apple Foundation Models on your device when available, with rules-based summaries as a fallback. In this release, the app does not send invoices or invoice text to Apple Private Cloud Compute.

## 3. Other processing and diagnostics

The app uses Apple's Vision and VisionKit frameworks for document scanning and text recognition on your device. The app also indexes garage records on your device using SQLite and on-device embeddings.

The app does not include third-party analytics, advertising or tracking SDKs, and it does not send garage data to a server run by the developer. Crash reports and diagnostics collected by Apple follow your device settings and Apple's policies.

## 4. Storage and iCloud sync

With the built-in storage location, vehicle records and attached invoice PDFs are stored in the app's Application Support folder. You can choose a custom folder instead. Its storage and sync then depend on that location.

When iCloud is available and turned on for the app, the vehicle records and attached invoice PDFs in the app's iCloud container sync across your Apple devices through iCloud. The developer has no access to your iCloud account or container. The search index stays in local app storage and does not sync.

## 5. Camera

On iOS, the app asks for camera access when you choose **Scan Receipt**. The camera captures a paper invoice and creates a PDF attachment in your garage storage location.

## 6. Local preferences

The app stores preferences on your device with `UserDefaults`, including appearance, the Ask switch and whether you have accepted the Ask disclosure.

## 7. Third-party links

Links to the App Store, the support site or the developer's repository open external services, which have their own privacy policies.

## 8. Contact

- **Developer:** Amol Karnik
- **Email:** amol.m.karnik@gmail.com
- **Support:** https://amolkarnik.github.io/car-service-dashboard/support
- **Website:** https://amolkarnik.github.io/car-service-dashboard/
