<div align="center">

<img src="assets/banner.png" alt="banner" width="100%" />

# 💸 ProofPay

**Trustless task payment platform — prove your work, get paid automatically on the XION blockchain**

[![React Native](https://img.shields.io/badge/React%20Native-Expo-0EA5E9?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![XION](https://img.shields.io/badge/XION-Blockchain-6B46C1?style=for-the-badge)](https://xion.burnt.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge)](LICENSE.md)

🏆 Checkpoint 1 Winner — XION Proof of Concept Hackathon (selected from 2000+ participants)

</div>

<br/>

ProofPay is a trustless task payment platform supporting Soft, zkTLS, and Hybrid proof systems on the XION blockchain. Create tasks, submit verifiable proofs, and get paid automatically — cryptographic verification for objective work, manual review for subjective work, and a hybrid approach for complex scenarios.

## ✨ Features

- **Soft Proofs** — manual review for subjective work (content creation, design, consulting)
- **zkTLS Proofs** — cryptographic verification of API responses via the XION Dave SDK (instant, zero human review)
- **Hybrid Proofs** — zkTLS verification plus a manual review window with auto-release timer for complex tasks
- **Abstraxion wallet auth** — seamless XION wallet connection and smart contract interaction
- **Real-time updates** — live task status changes via Supabase Realtime
- **Push notifications** — OneSignal integration for mobile alerts on task updates
- **Evidence uploads** — signed URL secure file storage for photo and document proofs

## 🎥 Demo

[![Watch Demo](https://img.shields.io/badge/YouTube-Watch%20Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=j0CIWGTbssI)

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | React Native + Expo Router |
| Language | TypeScript |
| Blockchain | XION (smart contract integration) |
| Wallet | Abstraxion (XION wallet auth) |
| Verification | XION Dave SDK (zkTLS) |
| Backend | Supabase (PostgreSQL + Realtime) |
| Notifications | OneSignal |

## 🚀 Getting Started

```bash
npm install
```

Copy `.env.example` to `.env` and fill in your values, then:

```bash
npx expo start
```

Open in Expo Go by scanning the QR code, or press `i` for iOS / `a` for Android.

### Demo mode (one command)

```bash
npm run demo:setup
```

Starts the blockchain indexer (port 3001), mock zkTLS verifier (port 3002), the React Native app with test data, and Supabase Realtime sync. Full walkthrough in [DEMO.md](DEMO.md).

## 📄 License

MIT — see [LICENSE.md](LICENSE.md) for details.
