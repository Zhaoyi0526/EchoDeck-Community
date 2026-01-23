# EchoDeck Community & Feedback

<div align="center">
  <img src="https://your-logo-url.com/logo.png" alt="EchoDeck Logo" width="120" />
  <h1>EchoDeck</h1>
  <p><strong>The Gamified, Hybrid Social Reader for the Decentralized Web.</strong></p>
  
  <a href="https://echodeck.io">🌐 Official Website</a> | 
  <a href="https://github.com/your-org/echodeck-community/issues">🐛 Report Bug</a> | 
  <a href="https://github.com/your-org/echodeck-community/discussions">💡 Request Feature</a>
</div>

---

## 👋 Welcome to the EchoDeck Community

This repository serves as the central hub for the **EchoDeck community**. While the core codebase of EchoDeck remains closed-source during our Beta phase to protect our unique anti-spam and growth mechanisms, we believe in building *with* the community, not just for it.

Use this repository to submit feedback, track public roadmap items, and discuss the future of the Nostr ecosystem.

---

## 💎 Product Philosophy: The "Dual-Track" Design

EchoDeck is not just another Nostr client. It is an experiment in bridging the gap between the polished UX of Web2 and the sovereignty of Web3.

We built EchoDeck on a **Dual-Track Architecture**:

### Track A: The Protocol Layer (Decentralized)
* **Sovereignty First:** Your private keys never leave your device (encrypted local storage or extension).
* **Censorship Resistance:** All social content (Notes, Articles, Zaps) is fetched directly from and published to Nostr Relays. EchoDeck does not "own" your social graph.
* **Portability:** If EchoDeck disappears tomorrow, your identity and followers remain safe on the protocol.

### Track B: The Meta Layer (Curated)
To solve the "Cold Start" problem and the "Spam" issues plaguing decentralized networks, we introduced a server-side **Meta Layer**:
* **The Viral Loop:** A gamified invitation system that rewards "Proof of Engagement." Users must contribute value (posting, curating) to earn the right to invite others.
* **Hybrid RSS Engine:** A server-assisted fetcher that bridges the legacy web (RSS/Atom) into the Nostr ecosystem, allowing you to subscribe to blogs and news outlets directly alongside your social feed.
* **Quest System:** An onboarding engine that guides new users from "Zero" to "Hero" through interactive tasks.

---

## 🏗 Technical Architecture

EchoDeck is built for performance, leveraging the latest React ecosystem while maintaining a lightweight footprint.

### The Stack
* **Frontend framework:** [Next.js 14](https://nextjs.org/) (App Router) for server-side rendering and optimal SEO.
* **UI System:** [Tailwind CSS](https://tailwindcss.com/) + [Shadcn/UI](https://ui.shadcn.com/) for a pixel-perfect, accessible interface.
* **State Management:** [Zustand](https://github.com/pmndrs/zustand) to handle the high-frequency updates of WebSocket streams without re-render fatigue.
* **Editor:** A customized [Tiptap](https://tiptap.dev/) implementation supporting Markdown shortcuts and client-side image compression.

### Infrastructure & Deployment
* **Edge-Ready:** Deployed on serverless infrastructure to ensure low latency globally.
* **Database:** A managed PostgreSQL cluster handles the "Meta Layer" (User Tiers, Quests, Invite Trees) with strict Row Level Security (RLS).
* **Nostr Engine:** We use a custom lightweight wrapper around `nostr-tools` to manage subscription lifecycles and event deduplication efficiently.

---

## 🛡️ Security & Privacy

* **Non-Custodial:** We do not store your `nsec` (private key) on our servers. Login is handled client-side.
* **NIP-07 Support:** We strongly recommend using browser extensions (like Alby or nos2x) for the highest security level.
* **Metadata:** Only public signals (public keys, task completion status) and subscription preferences are synced to our Meta Layer to enable cross-device synchronization.

---

## 🗺️ Public Roadmap

We are currently in **Closed Beta (Phase 1)**.

- [x] **Core Social:** Feed, Profiles, Long-form Articles (NIP-23).
- [x] **RSS Integration:** Subscribe to any Web2 URL.
- [x] **Viral Invite System:** Tiered access and invite codes.
- [x] **Pro Membership:** Stripe integration for power users.
- [ ] **Mobile App:** Native wrapper (PWA/React Native).
- [ ] **AI Agents:** Smart content summarization and personalized discovery.
- [ ] **Community Communities:** NIP-72 support.

---

## 🤝 How to Contribute

We value your input! Here is how you can help:

1.  **Bug Reports:** Found a glitch? Open an [Issue](https://github.com/your-org/echodeck-community/issues).
2.  **Feature Requests:** Have a cool idea? Start a [Discussion](https://github.com/your-org/echodeck-community/discussions).
3.  **Spread the Word:** Share your invite codes (if you have unlocked them!) and help us grow the network responsibly.

---

<div align="center">
  <p>Built for the <strong>Nostr</strong> Protocol.</p>
  <p>© 2026 EchoDeck Team</p>
</div>
