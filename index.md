---
title: Car Service Dashboard — Private Automotive Maintenance Dashboard
---

# Car Service Dashboard

A fast, tactile, and completely private **iOS and macOS application** for organizing vehicle service records, tracking repair costs, and preserving maintenance history.

Stop digging through gloveboxes, paper folders, and dealer PDFs. Car Service Dashboard transforms cluttered invoices into an interactive, chronological timeline with rich spend analytics and on-device search.

---

### Quick Links
- 🔒 [Privacy Policy](privacy.html)
- 🛠️ [Support & FAQ](support.html)
- 🐛 [Report an Issue on GitHub](https://github.com/amolkarnik/car-service-dashboard/issues)

---

### Key Highlights

- **Interactive Spend Trajectory & Multi-Car Timeline:**
  - View your entire service history chronologically with line item details, category tags, odometer readings, and attached invoice documents.
  - Interactive Swift Charts track repair spend trajectories over time, with automatic temporal padding and monthly trend breakdowns.
  - Multi-car visualization colors data points and line markers by vehicle, paired with an accessible bottom legend.

- **Vehicle Garage Customization & Theming:**
  - Personalize each vehicle in your garage with a custom accent color using 10 curated automotive palette presets or a native fine-tuning color picker.
  - Colors are subtly reflected across garage cards, sidebar status dots, and timeline records.

- **Optical Document Ingestion (OCR):**
  - **VisionKit Camera Scanner (iOS):** Scan multi-page physical repair receipts with automatic edge detection and perspective correction.
  - **Batch PDF Folder Import (macOS):** Ingest entire folders of historical PDF invoices with bounded multi-worker concurrency.
  - **6-Tier Vehicle Matching:** Intelligently attributes invoices to vehicles via VIN, license plate, and make/model tokens.
  - **Intelligent Deduplication:** Auto-heals and prevents duplicate visits within batches and across your garage.

- **Private Invoice AI with Cloud Control:**
  - Uses Apple's Foundation Models on-device for invoice summaries, with Apple Private Cloud Compute enabled by default as a fallback when needed. This fallback sends cleaned invoice text and known garage provider names to Apple, rather than the PDF or scanned images.
  - Turn on **Settings → Invoice AI Processing → On-device only** to prevent invoice-summary cloud requests. If local AI cannot complete a summary, the app uses a rules-based summary.
  - Built-in conversational Assistant uses local search and Apple Foundation Models to answer questions about your service history.

- **Seamless iCloud Ubiquity Sync:**
  - Background synchronization between your Mac, iPhone, and iPad using Apple's official iCloud Drive Ubiquity Container.
  - Human-readable open JSON storage format (`CarServiceData.json`) and standard PDF attachments. Zero proprietary database lock-in.

- **100% Private by Design:**
  - Zero user accounts, zero logins, zero tracking pixels, and zero third-party telemetry. OCR and search indexing run locally. Optional invoice-summary processing through Apple Private Cloud Compute is described in the [Privacy Policy](privacy.html); the developer does not receive your garage data.

---

*Car Service Dashboard is an independent application. All vehicle manufacturer trademarks are the property of their respective owners and are used purely for vehicle identification purposes.*
