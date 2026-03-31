 **VrikshaChain: Blockchain-Powered Ayurvedic Herb Traceability**

**From Soil to Soul, Verified.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Flutter](https://img.shields.io/badge/Flutter-3.16+-blue.svg)](https://flutter.dev)
[![Firebase](https://img.shields.io/badge/Firebase-10.0+-orange.svg)](https://firebase.google.com)
[![Polygon](https://img.shields.io/badge/Polygon-EVM-purple.svg)](https://polygon.technology)

---

 Overview

VrikshaChain is a blockchain-based traceability system designed to combat adulteration, ensure authenticity, and promote ethical sourcing in the Ayurvedic herbal supply chain. By leveraging immutable blockchain records, geo-tagging, and AI-powered verification, we create an unbreakable digital bridge from the farmer's field to the consumer's hands.

**The Problem:** The Ayurvedic industry suffers from rampant adulteration, opaque supply chains, and lack of verifiable provenance—eroding consumer trust and harming honest farmers.

**Our Solution:** A permissioned blockchain ecosystem where every critical event (harvest, lab test, transfer) is cryptographically notarized, creating a tamper-proof journey that anyone can verify with a simple QR scan.

---

Key Features

| Stakeholder | Features |
| :--- | :--- |
| **Farmer/Collector** | Batch creation, GPS geo-tagging, offline mode, harvest photo capture, QR code assignment |
| **Lab Technician** | Upload test reports, digital signatures, batch verification, quality threshold checks |
| **Logistics** | QR-based custody transfer, real-time location updates, shipment tracking |
| **Manufacturer/Retailer** | Dashboard with analytics, batch verification, AI anomaly alerts, compliance reporting |
| **Consumer** | QR scan to view complete provenance (map, farmer story, lab certificates) |
| **Regulator** | Tamper-proof audit trails, compliance monitoring, blockchain explorer access |

---

**Data Flow:**
1.  Farmer creates batch → Data stored in Firestore
2.  Cloud Function triggers → Critical data hashed
3.  Hash stored on Polygon blockchain → Immutable proof
4.  Consumer scans QR → Compares Firestore data with blockchain hash → Verification result

---
