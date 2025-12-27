# dro1d labs

Privacy-first software for iOS & macOS.  
Focused on on-device security, content protection, and user-controlled diagnostics.

We build tools that are:
- Offline by design
- Transparent in behavior
- Safe for production use
- Free from tracking, ads, or data collection

---

## What We Build

### De-Ad
Minimal Safari content blocker focused on privacy and reliability.  
Blocks ads and trackers without inspecting browsing activity.

- Uses Apple’s Content Blocker API only  
- No page access, no telemetry  
- Conservative rules to avoid site breakage  
- Open rule transparency

---

### NuDefndr
Local-only photo scanner and secure vault for sensitive media.

- On-device analysis only  
- No cloud services  
- Strong encryption and isolation  
- Designed for privacy-critical workflows

---

### Defndr
System integrity and environment validation utilities.

- Runtime environment checks  
- Filesystem and process heuristics  
- Defensive diagnostics for iOS & macOS  
- Built to be safe, explainable, and non-invasive

---

## Core Components

### IntegrityKit
Reusable environment and integrity checks shared across products.  
Focused on detection without exploitation.

**Status:** Stable / in production use

---

### VaultKit
Minimal encryption and secure storage primitives.

- AES-based storage
- Small attack surface
- No unnecessary abstractions

**Status:** Active development

---

### Scan Engine
Local-only media traversal and classification engine.

- Designed for high-volume libraries  
- No network access  
- Deterministic, explainable behavior

**Status:** Prototype / internal use

---

## Principles

- **On-device by default**  
  No cloud dependencies. No remote processing.

- **User control over automation**  
  No hidden logic. No silent decisions.

- **Transparency over “smart” behavior**  
  Features must be explainable and auditable.

- **Privacy as architecture, not policy**  
  If data cannot be accessed, it cannot be abused.

---

## Open Source

Where possible, we publish:
- Blocking rules
- Supporting tools
- Documentation and validation logic

Open source is used for transparency and trust, not data collection.

---

## Contact & Support

Issues and discussions are handled per repository.  
No tracking, no support tickets, no marketing funnels.
