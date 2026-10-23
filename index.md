---
title: Service Ledger — Private Automotive Maintenance Dashboard
---

# Service Ledger

A fast, tactile, and completely private **iOS and macOS application** for organizing vehicle service records, tracking repair costs, and preserving maintenance history.

Stop digging through gloveboxes, paper folders, and dealer PDFs. Service Ledger transforms cluttered invoices into an interactive, chronological timeline with rich spend analytics and on-device search.

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

- **On-Device Artificial Intelligence:**
  - Leverages Apple's native on-device `FoundationModels` framework on Apple Silicon to extract concise, priority-weighted repair headlines (e.g., highlighting brake replacements over routine courtesy checks).
  - Built-in conversational Assistant for natural language querying across your service history without cloud dependencies.

- **Seamless iCloud Ubiquity Sync:**
  - Background synchronization between your Mac, iPhone, and iPad using Apple's official iCloud Drive Ubiquity Container.
  - Human-readable open JSON storage format (`CarServiceData.json`) and standard PDF attachments. Zero proprietary database lock-in.

- **100% Private by Design:**
  - Zero user accounts, zero logins, zero tracking pixels, and zero third-party telemetry. All OCR, search indexing, and AI processing execute locally on your hardware.

---

*Service Ledger is an independent application. All vehicle manufacturer trademarks are the property of their respective owners and are used purely for vehicle identification purposes.*
