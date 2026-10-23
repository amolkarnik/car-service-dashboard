---
title: Support — Car Service Dashboard
---

# Support & FAQ

**Car Service Dashboard** is an independent application for tracking vehicle maintenance and expenses. For assistance, common questions, or bug reports, please consult the guide below.

---

## Reporting a Bug or Requesting a Feature

To report an issue or suggest an enhancement, please open a ticket on our public issue tracker:  
👉 **[Open an Issue on GitHub](https://github.com/amolkarnik/car-service-dashboard/issues)**

When filing a bug report, please include:
- **Device & OS Version** (e.g. iPhone 16 Pro running iOS 27, Mac Studio running macOS 26)
- **App Version** (found in Settings)
- **Steps to reproduce** the issue
- **Observed behavior vs. expected behavior**

---

## Frequently Asked Questions (FAQ)

### Does Car Service Dashboard require an account or subscription?
**No.** Car Service Dashboard requires zero user accounts, zero logins, and zero recurring subscription fees. It operates directly on your Apple devices and syncs through your existing iCloud account.

### How does iCloud sync work between my Mac and iPhone?
Car Service Dashboard uses Apple's native iCloud Drive Ubiquity Container. As long as both devices are signed in to the same Apple ID with iCloud Drive enabled:
- Your service history ledger (`CarServiceData.json`) synchronizes automatically in the background.
- Any attached receipt PDFs or scanned camera documents in your `Receipts/` folder replicate automatically across your devices.
- File coordination (`NSFileCoordinator`) and automatic conflict resolution ensure changes merge cleanly even if you edit records offline.

### How do I customize a vehicle's accent color?
1. Open the **Home** (My Garage) tab.
2. In the card for your car, click or tap the **colored circle dot** next to the car's name (or right-click / long-press the card and select **"Change Vehicle Color..."**).
3. Select from 10 curated automotive preset colors (Azure Blue, Sunset Amber, Emerald Green, Electric Purple, Ruby Crimson, etc.) or tap **Fine-Tune Custom Color** to pick any custom shade.
4. Tap **Save**. Your chosen color will instantly update the garage card stripe, sidebar/menu dots, timeline visit badges, and timeline spend trajectory chart.

### How do I scan paper repair orders or receipts?
On iOS:
1. Tap the **"+" (Add)** button in the navigation bar or floating action button.
2. Select **"Scan Invoice Document"**.
3. Use the document camera to photograph all pages of your receipt. The app automatically detects edges, straightens angles, and creates a multi-page PDF.
4. The on-device OCR engine extracts the service date, facility name, VIN, mileage, line items, and total cost for your review.

### How does Batch Folder Import work on Mac?
If you have accumulated years of PDF invoices in a folder:
1. In the **Timeline** toolbar menu on macOS, select **"Import Folder (Batch Invoices)..."**.
2. Select your folder of repair PDFs.
3. The app scans and processes invoices concurrently on-device, automatically matching invoices to cars in your garage, filtering dealership noise, and flagging potential duplicates.
4. Review the itemized summary and tap **Import** to merge the records into your ledger.

### Where is my data stored? Can I access or back it up manually?
Yes. Your data is never trapped in a proprietary database:
- Your service ledger is stored as a clean, human-readable JSON file (`CarServiceData.json`).
- All attached invoices are stored as standard, uncompressed PDF files in the `Receipts/` subfolder.
- In macOS **Settings**, you can view the active storage path or choose a custom folder location on your drive.

---

## Direct Inquiries

For additional questions or support inquiries, please open a ticket on GitHub:  
<https://github.com/amolkarnik/car-service-dashboard/issues>
