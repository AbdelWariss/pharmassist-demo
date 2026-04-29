<div align="center">

<img src="screenshots/logo.png" 
     alt="Pharm'Assist Logo" 
     width="200"/>

# 🏥 Pharm'Assist

### AI-Powered Pharmacy Search & Medicine Delivery
### for West Africa

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Claude AI](https://img.shields.io/badge/Claude_AI-orange?style=for-the-badge)
![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=google-maps&logoColor=white)

> ⚠️ This is a **showcase repository**.
> Source code is private and available
> upon request for verified clients.

</div>

---

## 📱 Overview

Pharm'Assist is a production-grade cross-platform 
mobile application (iOS & Android) that connects 
patients with nearby pharmacies, enables real-time 
medicine availability search, and provides 
AI-powered health consultation — all in one app.

Built for West African markets where access to 
pharmaceutical information is limited and 
medicine delivery is emerging.

---

## ✨ Key Features

### 👤 User Side
- 🗺️ **Pharmacy geolocation** — Google Maps integration 
  with real-time nearby pharmacy search
- 💊 **Medicine availability** — real-time stock search 
  across multiple pharmacies
- 🤖 **PharmBot AI** — AI health consultant powered 
  by Claude Haiku via Firebase Cloud Functions
- 🚚 **Medicine delivery** — dynamic pricing system 
  (Yango-inspired tariffs stored in Firestore)
- 🔐 **KYC verification** — 5-status verification 
  flow for secure user onboarding

### 💊 Pharmacy Side
- 📦 Stock management in real-time
- 📋 Order management dashboard
- 💰 Earnings tracking

### 🔑 Admin Side
- 👥 User & pharmacy management
- 📊 Analytics dashboard
- ⚙️ Dynamic pricing configuration

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | Flutter / Dart |
| **Backend** | Firebase Cloud Functions |
| **Database** | Cloud Firestore |
| **Authentication** | Firebase Auth |
| **AI** | Claude Haiku API (Anthropic) |
| **Maps** | Google Maps Platform |
| **Storage** | Firebase Storage |
| **Security** | Firebase Secret Manager |
| **State Management** | Riverpod |

---

## 🏗️ Architecture

lib/
├── core/
│   ├── constants/
│   ├── theme/
│   └── utils/
├── data/
│   ├── models/
│   ├── repositories/
│   └── datasources/
├── domain/
│   ├── entities/
│   └── usecases/
└── presentation/
├── screens/
├── widgets/
└── providers/

**Clean Architecture** with clear separation 
of concerns — Data, Domain, and Presentation 
layers fully decoupled.

---

## 📸 Screenshots

<div align="center">

| Splash | Home | Map |
|---|---|---|
| ![Splash](screenshots/splash.png) | ![Home](screenshots/home.png) | ![Map](screenshots/map.png) |

| PharmBot AI | KYC | Delivery |
|---|---|---|
| ![PharmBot](screenshots/pharmbot.png) | ![KYC](screenshots/kyc.png) | ![Delivery](screenshots/delivery.png) |

</div>

---

## 🤖 Med'Assist — AI Health Consultant

Med'Assist is an AI-powered chatbot integrated 
directly into Pharm'Assist, built with:

- **Claude Haiku** (Anthropic) — fast, 
  cost-efficient LLM for health queries
- **Firebase Cloud Functions** — serverless 
  middleware for secure API calls
- **Firebase Secret Manager** — API keys 
  never exposed client-side
- **Structured responses** — JSON-formatted 
  AI outputs for consistent UI rendering

User: "Is ibuprofen safe with paracetamol?"
Med'Assist: [AI-generated medical guidance
with disclaimer]

---

## 💰 Dynamic Delivery Pricing

Inspired by Yango/Uber pricing model:

- Base fare stored in **Firestore** 
  (updateable without app release)
- Distance-based calculation
- Surge multiplier support
- Real-time price display before order

---

## 🌍 Target Market

- **Primary:** West Africa (Senegal, Benin, 
  Côte d'Ivoire, Mali)
- **Secondary:** French-speaking Africa
- **Future:** European diaspora communities

---

## 📊 Project Status

| Component | Status |
|---|---|
| Flutter App | ✅ Complete |
| Firebase Backend | ✅ Complete |
| PharmBot AI | ✅ Complete |
| KYC Flow | ✅ Complete |
| Dynamic Pricing | ✅ Complete |
| App Store Deployment | 🔄 In Progress |
| Play Store Deployment | 🔄 In Progress |

---

## 👨‍💻 Developer

**Abdel Wariss OSSENI**
Founder, CODEXA Solutions 🇸🇳

[![Upwork](https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/abdelwarissosseni)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AbdelWariss)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:warissosseni@yahoo.com)

---

<div align="center">

*Built with ❤️*

</div>
