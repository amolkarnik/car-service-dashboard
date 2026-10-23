---
title: Privacy Policy — Service Ledger
---

# Privacy Policy

**Effective Date:** October 2026

**Service Ledger (Car Service Dashboard)** ("the App") is a native iOS and macOS application designed to help vehicle owners track service visits, maintenance records, and repair costs. Your automotive records, financial figures, and receipts are deeply personal, and the App is engineered from the ground up to keep your data completely private.

---

## Executive Summary

**The App collects zero personal data, includes zero analytics or telemetry SDKs, displays zero advertisements, and operates zero external servers.** 

All document processing, optical character recognition (OCR), text summarization, and data storage occur strictly on your personal Apple devices and within your private iCloud Drive storage.

---

## What We Do Not Do

- We do **not** collect, store, or transmit your name, email, IP address, device identifier, VIN, license plate, or vehicle service history.
- We do **not** integrate third-party tracking pixels, advertising frameworks, or telemetry tools.
- We do **not** operate any proprietary cloud server, database, or API backend.
- We do **not** sell, license, share, or monetize any user data whatsoever.

---

## Data Storage & iCloud Synchronization

- **On-Device Storage:** Your vehicle records and receipt files are stored locally in your sandboxed application directory using standard, human-readable JSON (`CarServiceData.json`) and standard PDF files.
- **iCloud Drive Ubiquity Sync:** When iCloud is enabled on your Apple device, the App synchronizes your service ledger and receipt attachments seamlessly across your Mac, iPhone, and iPad using Apple's official iCloud Ubiquity container (`iCloud.com.amolkarnik.CarServiceDashboard`).
  - All sync operations are governed by Apple's end-to-end security protocols and tied directly to your personal Apple ID.
  - The developer cannot access, read, or recover your iCloud data.
- **System API Declarations:** In compliance with Apple guidelines, our system usage of `UserDefaults` for lightweight appearance and color preferences is declared under reason code `CA92.1`. No tracking identifiers are stored.

---

## Document Scanning & Optical Processing

- **Camera Scanner (iOS):** The App uses Apple's native VisionKit framework (`VNDocumentCameraViewController`) for scanning physical paper invoices. Document edge detection, perspective correction, and image processing happen 100% on-device in memory.
- **Text & VIN Extraction:** OCR text extraction uses Apple's native `PDFKit` and `Vision` frameworks on your device. Scanned images and PDF receipts are saved directly to your local receipt directory or iCloud Drive container. No documents are ever sent to remote processing servers.

---

## On-Device Artificial Intelligence

- **Apple Intelligence Integration:** The App utilizes Apple's native on-device `FoundationModels` framework (`SystemLanguageModel` and `LanguageModelSession`) for invoice summarization and conversational assistance.
- All AI processing executes locally on Apple Silicon neural engines. Your invoices, prompts, and service notes are never transmitted to external cloud LLM providers.

---

## Children's Privacy

The App does not collect any data from anyone of any age. It is rated **4+** (Made for Everyone).

---

## Changes to This Policy

If this policy is revised, updates will be published at this same URL with an updated effective date. Because the App operates with zero data collection, any future changes will maintain or narrow this strict privacy standard.

---

## Contact & Questions

If you have questions about this Privacy Policy or Service Ledger, please open an issue on our public issue tracker:  
<https://github.com/amolkarnik/car-service-dashboard/issues>
