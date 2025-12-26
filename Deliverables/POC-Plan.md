# POC Implementation Plan: C-REWARDS Ecosystem

**Document Version:** 1.0  
**Date:** December 26, 2025  
**Prepared for:** C-REWARDS Project Stakeholders  
**Reference Document:** Deliverables/Proposal.md (Phase 1 Scope)

---

## 1. Objective

The primary objective of the **Proof of Concept (POC)** is to **validate the core technology feasibility and business model assumptions** with minimal investment and risk. 

Specifically, we aim to prove that:
1.  **Geolocation:** The app can accurately detect user presence at specific partnership locations using simple geofencing.
2.  **Transaction Flow:** The "Scan-to-Earn" and "Scan-to-Redeem" loop works seamlessly between the Customer App and Partner App.
3.  **Data Integrity:** Points are awarded and deducted correctly without errors.

---

## 2. Detailed Scope of Work (POC Phase)

The POC will focus *only* on the "Happy Path" of the core user journey.

### 2.1 Customer Application (Flutter - iOS/Android)
*   **Authentication:** Basic Sign-up/Login (Email or Phone).
*   **Home Dashboard:** View current point balance and active missions.
*   **Mission Control:** 
    *   View list of available location-based missions.
    *   **Core Feature:** "Check-in" button enabled only when inside the geofenced area.
*   **Profile:** Basic user details (Name, ID).

### 2.2 Partner Application (Flutter - iOS/Android)
*   **Authentication:** Staff login (credentials provided by Admin).
*   **QR Scanner:** 
    *   Scan Customer QR to identify user.
    *   **Action:** "Award Points" (Manual input of amount or selection of pre-set activity).
*   **Transaction History:** View list of recent point awards (today only).

### 2.3 Admin Console (Web - Essential)
*   **Dashboard:** Simple counter of Total Users, Total Points Awarded.
*   **User Management:** List all registered users (View/Block).
*   **Mission Setup:** Basic tool to set Latitude/Longitude and Radius for a mission location.
*   **Partner Management:** Create Partner accounts (Username/Password).

---

## 3. Implementation Roadmap (8-10 Weeks)

| Week | Phase | Key Activities |
| :--- | :--- | :--- |
| **Week 1-2** | **Setup & Research Design** | • Setup Dev Environment<br>• Finalize UI Wireframes (Basic)<br>• **User Research Round 1:** Validate "Proof of Concept" wireframes with 5-10 potential users. |
| **Week 3-4** | **Core Development (Iter 1)** | • **Backend:** API for Auth, Points, Missions<br>• **Mobile:** Implement Geofencing logic & QR Scanner<br>• **Refinement:** Adjust UI based on Round 1 feedback. |
| **Week 5-6** | **Integration & Research Prep** | • Connect Mobile Apps to Real Backend<br>• Deploy Alpha Build to TestFlight<br>• **User Research Round 2:** On-site Usability Test (Contextual Inquiry) with Alpha Build at 1 partner location. |
| **Week 7-8** | **Refinement & Stabilization** | • **Optimization:** Fix usability issues found in Round 2.<br>• Fix critical bugs.<br>• Finalize "Happy Path" for Pilot. |
| **Week 9-10** | **Pilot Run (UAT)** | • Live test with 50-100 users<br>• Monitor logs and feedback<br>• **Closure Report** |

---

## 4. Dependencies (Client Responsibilities)

For the POC to be successful and on-time, we require the following from the Client:

1.  **Pilot Locations:** A list of 3-5 specific physical locations (Name, Address, GPS Coordinates) for testing the geofencing.
2.  **Test Partners:** Designated staff at these locations who will use the Partner App during the Pilot.
3.  **Basic Assets:** Logo files (SVG/PNG) and Brand Colors (Hex Codes) for the UI.
4.  **Test Devices:** If specific legacy devices are required, the client must provide them. (Otherwise, we test on standard modern devices).
5.  **Apple/Google Developer Accounts:** Access to Client's developer accounts for uploading TestFlight/Internal Beta builds.

---

**Approval:**
By signing below, the Client agrees to the defined Scope, Timeline, and Requirements for the POC Phase.

__________________________
[Client Name / Representative]
Date: ____________________

---

## 5. Risks & Concerns

| Risk Category | Risk Description | Mitigation |
| :--- | :--- | :--- |
| **Technical** | **GPS Inaccuracy:** Indoor locations or mall basements may block GPS signals, making check-ins difficult. | Use large geofence radius (50-100m) for POC. Plan for "QR Check-in" backup in future phases. |
| **Operational** | **Staff Training:** Partner staff may not understand how to use the app or may be too busy to scan. | Create a 1-page "Cheat Sheet" PDF guide for staff. Keep the Partner App UI extremely simple (2 buttons). |
| **User Adoption** | **Low Participation:** Test users might not download the app for a short pilot. | Incentivize the 50-100 pilot users with a guaranteed small reward (e.g., Free Coffee) just for completing the test. |

---

## 6. Exclusions & Future Scope (NOT in POC)

The following features are explicitly **EXCLUDED** from this POC to ensure speed and focus. They will be addressed in the MVP or Full Scale phases.

*   **No Reward Redemption:** Users can *earn* points, but building the "Rewards Catalog" and "Coupon Redemption" system is for Phase 2 (MVP).
*   **No Complex Missions:** No "Photo Verification" missions requiring manual admin approval. No "Social Share" missions.
*   **No Tier System:** All users are "Standard" tier. No "Exclusive" or "VIP" logic.
*   **No Advanced Fraud Prevention:** We will not implement AI fraud detection or strict device fingerprinting yet. (Trust-based pilot).
*   **No Public App Store Release:** The app will be distributed via **TestFlight (iOS)** and **APK / Internal Testing (Android)** only. NOT on the public App Store.
*   **No Analytics Dashboard:** No advanced graphs, charts, or retention metrics. Only raw data tables.
