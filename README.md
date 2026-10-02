# 🌟 AI Dost (مالی دوست) — Financial Inclusion Copilot

[![Alibaba Cloud](https://img.shields.io/badge/Alibaba_Cloud-AI_Hackathon_2026-orange.svg)](https://www.alibabacloud.com/)
[![Track](https://img.shields.io/badge/Track-Financial_Inclusion-blue.svg)]()
[![Platform](https://img.shields.io/badge/Platform-Progressive_Web_App_(PWA)-green.svg)]()
[![Accessibility](https://img.shields.io/badge/Voice_Enabled-Urdu_%7C_English-purple.svg)]()
[![Privacy](https://img.shields.io/badge/Privacy-Safe_By_Design-emerald.svg)]()

> **"Financial clarity in the language of the common man."**  
> AI Dost is a lightweight, accessible, voice-enabled AI copilot built to empower Pakistan's unbanked and newly banked population with financial literacy, safe budgeting, fraud prevention, and banking guidance in **Urdu, Roman Urdu, and English**.

---

## 📌 1. Problem Statement (Pakistan's Reality)

In Pakistan today, **over 100 million citizens** remain unbanked or underbanked:
1. **The Jargon Barrier:** Traditional banking apps and financial advisory services use complex English corporate terminology, alienating daily-wage earners, small shopkeepers, and students.
2. **Predatory Loan Traps:** Lack of understanding around interest vs. Islamic banking contracts (*Murabaha, Musharakah, Takaful*) drives vulnerable families toward predatory cash lenders charging 10–20% monthly interest.
3. **Escalating Financial Fraud:** Fraudsters target low-literacy citizens daily via fake BISP 8171 messages, fake lottery alerts, and social-engineering calls requesting SMS OTP codes.
4. **Inflation & Budgeting Anxiety:** High inflation and electricity tariff surges make household budgeting critical, yet most people have never been taught how to calculate a sustainable emergency buffer.

---

## 💡 2. The Solution: AI Dost

**AI Dost** directly bridges this gap by acting as an empathetic, privacy-preserving digital companion that fits in the pocket of every Pakistani citizen:

```
                  ┌────────────────────────────────────────┐
                  │          AI DOST PWA CLIENT            │
                  │   (Installable on Android & iOS)       │
                  └──────────────────┬─────────────────────┘
                                     │
          ┌──────────────────────────┼──────────────────────────┐
          │                          │                          │
          ▼                          ▼                          ▼
┌───────────────────┐      ┌───────────────────┐      ┌───────────────────┐
│   VOICE ENGINE    │      │  BUDGET PLANNER   │      │    SCAM BUSTER    │
│  • Speech-to-Text │      │  • 50/30/20 Rule  │      │  • Real SMS Tests │
│  • Text-to-Speech │      │  • Persona Presets│      │  • Red Flag Alerts│
│  • Urdu & English │      │  • Health Score   │      │  • Rule Playbook  │
└─────────┬─────────┘      └─────────┬─────────┘      └───────────────────┘
          │                          │
          └──────────────────────────┴────────┐
                                              ▼
                         ┌────────────────────────────────────────┐
                         │       HYBRID INTELLIGENCE CORE         │
                         │                                        │
                         │  [Layer 1: Local Knowledge Engine]     │
                         │  • 50+ Pakistani Financial Topics      │
                         │  • 100% Offline, Zero Latency          │
                         │                                        │
                         │  [Layer 2: Alibaba Cloud Model Studio] │
                         │  • Live Qwen Flagship LLM (BYOK)       │
                         │  • Deep Contextual Pakistani Guidance  │
                         └────────────────────────────────────────┘
```

---

## 🚀 3. Key Features

### 1. 🤖 Intelligent Financial Assistant (Voice-Enabled)
- **Pakistani Financial Context:** Pre-trained on 50+ localized topics:
  - *Kameti* (ROSCA / Committee) vs. State Bank-regulated Asaan Savings Accounts.
  - *Raast* Instant Payment System & Free Transfers using mobile numbers.
  - Mobile Wallets (*Easypaisa, JazzCash, SadaPay, NayaPay*) limits, biometric verification, and security.
  - Islamic Banking (*Murabaha, Ijarah, Takaful*) vs. Conventional Interest (*Riba*).
  - Daily wagers & rickshaw driver daily micro-saving ("Gullak") rules.
- **Voice Accessibility:** Tap the microphone icon to speak your question in Urdu or English; tap the speaker icon on any reply to listen to the advice read aloud.
- **Hybrid AI Core:** Runs instantly offline with its embedded knowledge base, or connects directly to **Alibaba Cloud Model Studio (Qwen)** via the built-in BYOK (Bring Your Own Key) settings.

### 2. 📊 Smart 50/30/20 Budget Planner
- **Zero Paperwork:** 3-step slider interface designed for mobile touch screens.
- **Localized Presets:**
  - *Daily Wager / Driver* (Rs. 30,000/mo)
  - *Student / Intern* (Rs. 25,000/mo)
  - *Small Shopkeeper / Karyana* (Rs. 75,000/mo)
  - *Salaried Family* (Rs. 150,000/mo)
  - *Freelancer* (Rs. 120,000/mo)
- **Financial Health Score:** Real-time scoring (0–100) benchmarking Needs (50%), Wants (30%), and Bachat/Savings (20%).

### 3. 🛡️ Financial Safety & Scam Buster
- Interactive quiz testing real Pakistani SMS scams (e.g. fake BISP cash prize alerts, fake bank account block warnings).
- Teaches users the 4 Golden Rules: Never share an OTP, Urgency is the tell, Verify sender ID (8171 vs unknown SIMs), and Call the printed number.

### 4. 🌐 Complete Multilingual Localization
- One-click toggle between **English**, **اردو (Urdu with native RTL Nastaliq typography)**, and **Roman Urdu**.

### 5. 📲 Progressive Web App (PWA) — Install on Any Phone
- Fully compliant with modern PWA standards.
- Works on **Android, iPhone, Mac, and Windows** with zero app store download barriers.
- Offline support enabled via background Service Worker caching.

---

## 🛠️ 4. Technology Stack

- **Frontend:** Semantic HTML5, Vanilla JavaScript (ES6+), Vanilla CSS Design System.
- **PWA Architecture:** Service Worker (`sw.js`), Web App Manifest (`manifest.json`), Maskable PNG/SVG app icons.
- **Voice & Accessibility:** Web Speech API (`SpeechRecognition` & `SpeechSynthesis`).
- **AI Backend:** Hybrid Architecture:
  - **Offline Core:** Embedded Pakistani Financial Knowledge Engine.
  - **Cloud Core:** Alibaba Cloud Model Studio (`dashscope-intl.aliyuncs.com` / Qwen LLM endpoint).
- **Typography:** Google Fonts (`Inter`, `Space Grotesk`, `Noto Nastaliq Urdu`).

---

## 💻 5. How to Run Locally

### Option A: Windows 1-Click (Recommended)
Simply double-click:
```bash
start.bat
```
*(Or run `python serve.py` in your terminal. It will automatically start the server at `http://localhost:8080` and open your default browser).*

### Option B: Node.js / NPM
```bash
npm start
```

### Option C: Any Static Web Server
```bash
# Python 3
python -m http.server 8080

# Or npx serve
npx serve . -l 8080
```
Open `http://localhost:8080` in Chrome, Edge, or Safari.

---

## 📱 6. How to Install as a Mobile App (PWA)

1. Open the website link on your phone (Chrome on Android, or Safari on iOS).
2. Tap the **"Install App"** button in the top navigation bar, or select **"Add to Home Screen"** from your browser menu.
3. The **AI Dost** app icon will appear on your home screen and open full-screen like a native Android/iOS app!

---

## 🏆 7. Hackathon Project Credits

- **Event:** Alibaba Cloud AI Hackathon Pakistan 2026
- **Partners:** Alkhidmat Foundation Pakistan, Bano Qabil Platform
- **Theme:** AI for Pakistan's Future
- **Track:** Financial Inclusion
- **Created By:** AI Dost Project Team
- **License:** MIT License
