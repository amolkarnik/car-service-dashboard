---
title: Car Service Dashboard
---

# Car Service Dashboard

Car Service Dashboard keeps your car's service history, receipts and spending in one place, on iPhone, iPad and Mac. You can scan or import your service invoices, see what was done and when, and ask questions about your garage.

- [Privacy policy](privacy.html)
- [Support and questions](support.html)
- [Report an issue on GitHub](https://github.com/amolkarnik/car-service-dashboard/issues)

## Service history

- You can see every visit in order, with its date, service provider, mileage, cost, services and receipt.
- You can look at one vehicle, or at all your vehicles together.
- You can give each vehicle a color. Its garage card, sidebar dot, timeline badges and charts will use that color.

## Import invoices

- On iPhone and iPad, you can scan a paper receipt with the camera. The app will find the edges, straighten the pages and save them as a PDF.
- You can import one PDF invoice, or a whole folder of them at once.
- You don't have to type in the details. The app will read them from the invoice on your device and match the invoice to your vehicle by VIN, license plate or make and model.
- You check each record before anything is saved. If an invoice or visit is already in your garage, the app will tell you.
- Where Apple Intelligence is available, you also get a short summary of each invoice, written on your device. Otherwise you get a rules-based summary. In this release, the app will not send your invoices to Apple Private Cloud Compute.

## Ask about your garage

- You can ask questions such as "When was my last oil change, and what did it cost?" Apple Private Cloud Compute answers, and you can see the visits each answer used.
- Ask is off until you turn it on. When you ask a question, the app will send your question and, for the vehicles you have selected, each visit's date, cost, odometer reading, service provider and service descriptions, plus your spending totals. Ask does not send your VINs, license plates, receipts or files. You can read the details in the [privacy policy](privacy.html).
- You need iOS 27 or macOS 27 and an internet connection to use Ask.

## Spending

- You can see what you have spent over time, by month and by year.
- You can see your spending by service provider and by service category.

## Your data

- You don't need an account, and there is no tracking or third-party analytics. The developer does not receive your garage data.
- Your records are a readable JSON file (`CarServiceData.json`), and your receipts are standard PDF files in a `Receipts` folder. You can keep them in the app's own storage, in a folder you choose, or in your iCloud.
- If you use iCloud, your records and receipts will sync between your iPhone, iPad and Mac.

*Car Service Dashboard is an independent app. Vehicle manufacturer trademarks belong to their owners and are used only to identify vehicles.*
