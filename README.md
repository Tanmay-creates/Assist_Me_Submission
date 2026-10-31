# Assist Me · Voice AI Elder Care Platform

---

## 🌟 Overview

**Assist Me** is an AI-powered voice assistance and care coordination platform designed to empower older adults to live independently while keeping their families connected and in control.

Elderly users often struggle with complex apps, small fonts, or navigation hurdles. **Assist Me** simplifies this into a seamless 3-step loop:
1. **Speak / Tap**: The elder asks for what they need using natural voice or 1-tap quick buttons.
2. **Family Approves**: Family members (e.g. Daughter Sarah) review safety, verify medicine prescriptions, and approve costs.
3. **Helper Delivers**: Trusted local helpers (e.g. Neighbor Alex) accept tasks, track progress, and deliver items to the elder's doorstep.

---

## 💡 Key Features & Innovations

- 🎙️ **Voice AI with Web Speech API**: Real-time voice recognition and natural speech synthesis narration.
- 💊 **Medicine Safety Gate**: Automatic NLP detection for medication requests, requiring explicit family verification before fulfillment.
- 👥 **Multi-Role Live Coordination**:
  - **👵 Elder (Mary)**: Accessible UI, text size zoom (Normal / Large / Extra Large), voice assistant, 1-tap quick help (*Groceries, Ride, Home, Medicine*), and emergency family calling modal.
  - **👩 Family (Sarah)**: Approval queue, custom rejection reasons, cost transparency, and dashboard statistics.
  - **🚴 Helper (Alex)**: Task marketplace, step-by-step progress tracking (*Accept &rarr; On The Way &rarr; Picked Up &rarr; Delivered*).
- 🗄️ **Zero-Config SQLite Database**: Built-in persistent storage (`assist_me.db`) for requests, audit trails, and user profiles.
- ⚡ **Zero-Flicker Real-Time Sync**: Instant state synchronization across tabs and devices.
- ⚡ **1-Click Demo Presets for Judges**: Test grocery delivery, medicine safety checks, and clinic rides with single clicks.

---

## 🛠️ Tech Stack

- **Backend**: Python 3, Flask 3, SQLite, Context-managed transactions
- **Frontend**: HTML5, Modern React architecture, Tailwind CSS, Lucide Icons, Web Speech API, Web Audio API
- **NLP**: Rule-based text parsing, entity extraction, and safety classification
- **API**: Full REST API (`/api/requests`, `/api/requests/active`, `/api/parse`, `/api/users`, `/api/stats`)
