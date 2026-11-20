---
title: Support, Car Service Dashboard
---

# Support and questions

If you need help with Car Service Dashboard, or you want to report a problem or ask for a feature, you can [open an issue on GitHub](https://github.com/amolkarnik/car-service-dashboard/issues).

If you're reporting a problem, please include:

- your device and its iOS or macOS version (for example, iPhone 16 Pro on iOS 27);
- the app version, which you can find in Settings;
- the steps that lead to the problem;
- what you expected to happen, and what happened.

## Questions

### Do I need an account or a subscription?

No. You don't need an account, a sign-in or a subscription. The app works on your Apple devices and syncs through your own iCloud account.

### How does iCloud sync work between my iPhone and Mac?

If both devices are signed in to the same Apple Account with iCloud Drive turned on:

- your service records (`CarServiceData.json`) will sync in the background;
- your receipt PDFs and scanned receipts in the `Receipts` folder will sync too;
- if you edit records while you're offline, the app will merge your changes when your devices sync again.

### How do I change a vehicle's color?

1. Open **Home**.
2. On your vehicle's card, click or tap the colored dot next to its name. You can also right-click or long-press the card and choose **Change Vehicle Color...**.
3. Choose one of the preset colors, or choose **Fine-Tune Custom Color** to pick any color.
4. Choose **Save**. The vehicle's card, sidebar dot, timeline badges and charts will use the new color.

### How do I scan a paper receipt?

On iPhone and iPad:

1. Open **Timeline** and tap the **+** button.
2. Choose **Scan Receipt with Camera**.
3. Photograph each page of your receipt. The app will find the edges, straighten the pages and save them as one PDF.
4. Check the details the app read from the receipt, such as the date, provider, mileage, services and total, then save the visit.

### How do I import a folder of invoices?

If you have years of PDF invoices in a folder:

1. Open **Timeline**, choose the **+** button, then choose **Import Folder (Batch Invoices)...**.
2. Choose your folder of PDFs.
3. The app will read each invoice on your device, match it to a vehicle in your garage where it can, and flag invoices you may already have.
4. Check each record and choose which ones to keep, then choose **Import**.

### Do my invoices leave my device?

No. In this release, the app will read your invoices and write their summaries on your device. If Apple Intelligence isn't available, you get a rules-based summary. You can read the details in the [privacy policy](privacy.html).

### What does Ask send, and how do I turn it off?

Ask is off until you turn it on. When you ask a question, the app will send your question to Apple Private Cloud Compute, with each saved visit's date, cost, odometer reading, service provider and service descriptions for the vehicles you have selected, plus your spending totals. Ask does not send your VINs, license plates, notes, receipts or files. The developer does not receive your question or the answer. You can turn Ask off at any time in **Settings > Ask**.

You need iOS 27 or macOS 27 and an internet connection to use Ask. Apple sets a daily limit on questions.

### Where are my records stored, and can I back them up?

Yes, you can back them up. Your records are a readable JSON file (`CarServiceData.json`), and your receipts are standard PDF files in the `Receipts` folder. In **Settings**, you can see where they are stored, or choose **Choose Custom Storage Folder…** to keep them in a folder you pick.

## Other questions

If your question isn't answered here, you can [open an issue on GitHub](https://github.com/amolkarnik/car-service-dashboard/issues).
