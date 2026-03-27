<div align="center">

<img src="./docs/salma-unity-care-hospital.jpg" width="180" alt="Salma Unity Care Hospital">

# Salma Unity Care Hospital
### Live Reference Implementation — Sovereign Telehealth Platform

**A public demonstration of the Unity Care Sovereign (UCH) infrastructure.**  
*What you see here is the open demo layer. The production-grade sovereign platform is licensed separately.*

---

[![Demo](https://img.shields.io/badge/demo-live-brightgreen?style=for-the-badge)](https://unity-care-hospital.vercel.app)
[![Platform](https://img.shields.io/badge/platform-UCH_Sovereign-blue?style=for-the-badge)](https://github.com/Elmahrosa/Unity-Care-Hospital-Sovereign)
[![License](https://img.shields.io/badge/license-MIT_(demo_only)-lightgrey?style=for-the-badge)]()
[![Built By](https://img.shields.io/badge/built_by-Elmahrosa_International-red?style=for-the-badge)](https://teosegypt.com)

[🏥 Live Demo](https://unity-care-hospital.vercel.app) · [📋 Request Full Platform](mailto:ayman@teosegypt.com) · [🔐 UCH Sovereign](https://uch.teosegypt.com)

</div>

---

## What This Is

**Salma** is a public-facing reference implementation built on the Unity Care Hospital (UCH) platform — demonstrating the core patient experience, clinical workflows, and telemedicine interface that institutional buyers evaluate before licensing the full sovereign stack.

This repo is intentionally scoped. It shows **what the platform does**, not how it's hardened or deployed. The production UCH system — with audit logging, RBAC enforcement, air-gapped deployment, and institutional compliance architecture — is available under a separate commercial license.

---

## Platform Capabilities (Demonstrated Here)

| Module | What You'll See |
|--------|----------------|
| 🩺 **Patient Portal** | Registration, profile, appointment booking |
| 📅 **Appointment Scheduling** | Doctor selection, time slot management, status tracking |
| 📹 **Telemedicine Interface** | Video consultation UI, session management |
| 💊 **Pharmacy Module** | Prescription workflow, medication tracking |
| 🛏️ **Bed Management** | Ward allocation, occupancy dashboard |
| 📊 **Clinical Dashboard** | Patient records, vitals, care plans |
| 🤖 **AI Assistant** | Triage chatbot, care orchestration prompts |
| 🔗 **Blockchain Health-Chain** | Medical record notarization (demo mode) |

---

## Live Demo

🌐 **[unity-care-hospital.vercel.app](https://unity-care-hospital.vercel.app)**

Use the demo credentials to explore:

| Role | Email | Password |
|------|-------|----------|
| Patient | `patient@demo.uch` | `Demo1234!` |
| Doctor | `doctor@demo.uch` | `Demo1234!` |
| Admin | `admin@demo.uch` | `Demo1234!` |

> Demo data resets every 24 hours. No real patient data is used.

---

## Architecture Preview

```
salma-demo/
├── frontend/          React UI (patient portal, dashboards)
├── backend/           Express API (demo-scoped, no auth hardening)
├── labs/ai-assistant/ Extended module demos (AR, IoT, blockchain)
└── docs/              Architecture overview, API spec
```

The demo backend runs a simplified version of the UCH API. It intentionally omits:
- Production RBAC enforcement
- Immutable audit logging
- Redis-backed token revocation
- Air-gapped deployment configuration
- Institutional compliance documentation

These are exclusive to the **UCH Sovereign** licensed platform.

---

## Tech Stack (Demo Layer)

- **Frontend:** React 18, Tailwind CSS, i18n (Arabic/English)
- **Backend:** Node.js 20, Express 4, MongoDB
- **Telemedicine:** Agora RTC (video sessions)
- **Blockchain stub:** Web3.js, mock contract interface
- **AR/IoT:** Demo stubs for augmented reality viewer and vital monitors
- **Deployment:** Vercel (frontend) + Railway (API)

---

## From Demo → Production

If you are evaluating UCH for institutional deployment, here is the path:

```
1. Explore this demo  →  Understand the clinical workflow
2. Sign NDA           →  Get access to the full sovereign repo
3. Pilot deployment   →  90-day single-site evaluation ($45K–$65K)
4. License / acquire  →  Full institutional or national stack
```

| Tier | Investment | What You Get |
|------|-----------|-------------|
| Foundation Node | $45K – $65K | Single site, binary build |
| Institutional License | $89K – $120K | Source, audit infrastructure |
| Sovereign Stack | $260K+ | Territorial rights, 12-month support |
| White-Label Partner | $650K+ | Full brand autonomy, national scale |

---

## About the Platform

**Unity Care Sovereign** is developed by **Elmahrosa International** (Cairo, Egypt, est. 2007) — an institutional digital health company specializing in sovereign infrastructure for MENA health ministries, private hospital networks, and restricted deployment environments.

The platform is engineered for institutions that require:
- Full data territoriality (no third-party cloud dependency)
- Compliance-aligned audit infrastructure (HIPAA/GDPR-ready primitives)
- Air-gapped or offline-first operation capability
- Long-term IP ownership rather than SaaS subscription lock-in

---

## Contact

Ready to move beyond the demo?

📧 **[ayman@teosegypt.com](mailto:ayman@teosegypt.com)**  
Include your organization name, country, and deployment scope.

🔐 **[NDA + Full Platform Access](https://uch.teosegypt.com)**  
Sign the NDA online to receive access to the production repository and institutional documentation.

---

## License

This demo repository is released under **MIT** for evaluation purposes.  
The production UCH Sovereign platform is proprietary — see [TESL v2.1](https://github.com/Elmahrosa/Unity-Care-Hospital-Sovereign/blob/main/commercial/COMMERCIAL_LICENSE.md).

---

<div align="center">

*Built in Egypt. Deployed for sovereignty.*  
**[Elmahrosa International](https://teosegypt.com) · [teosegypt.com](https://teosegypt.com)**

</div>
