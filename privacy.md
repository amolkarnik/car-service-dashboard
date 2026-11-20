---
title: Privacy Policy, Car Service Dashboard
---

# Privacy Policy for Car Service Dashboard

**Last Updated:** November 2026

Car Service Dashboard is an independent app for tracking your car's maintenance and expenses, developed by Amol Karnik for iOS and macOS. The developer does not collect or receive your garage records, and the app has no developer analytics or telemetry. When you use some Apple services, described below, they process or sync your data.

## 1. Ask and Apple Private Cloud Compute

You can use Ask to ask questions about your service history and spending. Ask uses Apple Private Cloud Compute (PCC), Apple's server-based Apple Intelligence service.

Ask is off until you turn it on. Before you turn it on, you can see what Ask will send. You can turn it off at any time in **Settings > Ask**. While Ask is off, the app will not send anything for Ask.

When you ask a question, the app will send these to Apple's PCC service:

- your question;
- for the vehicles you have selected, each saved visit's date, cost, odometer reading, service provider and service descriptions;
- your spending totals for those vehicles.

Ask does not send your VINs, license plates, notes, receipts, invoice files or file names. Your provider and service text is sent as you saved it, so anything you typed into those fields is included.

Each question you ask is sent on its own. Your earlier questions and answers are not sent again. Apple processes PCC requests under Apple's privacy and security practices. The developer does not receive your question or the answer.

## 2. Invoice processing

When you import an invoice, the app will read its text, pick out the details and clean them up on your device. Where Apple Foundation Models are available on your device, you also get a summary of the invoice, written on your device. Otherwise you get a rules-based summary. In this release, the app will not send your invoices or invoice text to Apple Private Cloud Compute.

## 3. Other processing and diagnostics

When you scan a document, the app will use Apple's Vision and VisionKit frameworks to scan it and recognize its text on your device. The app will also index your garage records on your device, using SQLite and on-device embeddings.

The app does not include third-party analytics, advertising or tracking SDKs, and it will not send your garage data to a server run by the developer. Crash reports and diagnostics that Apple collects follow your device settings and Apple's policies.

## 4. Storage and iCloud sync

If you use the built-in storage location, your vehicle records and attached invoice PDFs are stored in the app's Application Support folder. You can choose a custom folder instead. Then storage and sync depend on the folder you choose.

When iCloud is available and you have turned it on for the app, your vehicle records and attached invoice PDFs in the app's iCloud container will sync across your Apple devices. The developer has no access to your iCloud account or container. The search index stays in the app's local storage and does not sync.

## 5. Camera

On iPhone and iPad, the app will ask for camera access when you choose **Scan Receipt with Camera**. You use the camera to capture a paper invoice, and the app will save it as a PDF attachment in your garage storage location.

## 6. Local preferences

The app will store your preferences on your device with `UserDefaults`, including your appearance setting, the Ask switch and whether you have accepted the Ask disclosure.

## 7. Third-party links

When you open a link to the App Store, the support site or the developer's repository, you leave the app for an external service with its own privacy policy.

## 8. Contact

- **Developer:** Amol Karnik
- **Email:** amol.m.karnik@gmail.com
- **Support:** https://amolkarnik.github.io/car-service-dashboard/support
- **Website:** https://amolkarnik.github.io/car-service-dashboard/
