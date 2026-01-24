EchoDeck: The Sovereign Social Reader

<div align="center"> <img src="https://your-logo-url.com/logo.png" alt="EchoDeck Logo" width="120" />


<h3><strong>Break the Walls. Own Your Voice. Bridge the Worlds.</strong></h3> <p>The first censorship-resistant platform bridging the depth of the Open Web (RSS) with the sovereignty of the Social Web (Nostr).</p>

<p> <a href="https://echodeck.io">🌐 Request Access</a> • <a href="#-the-manifesto">📜 Manifesto</a> • <a href="#-architecture--technology">🏗 Architecture</a> • <a href="#-the-invite-protocol">🔑 Invite Codes</a> </p> </div>
📜 The Manifesto: Breaking the Three Walls

EchoDeck was born from a refusal to accept the fractured state of the modern internet. We identified three "Walls" that restrict human potential, and we built EchoDeck to tear them down.
Wall 1: The Wall of Censorship

Centralized platforms have become arbiters of truth, erasing voices at the whim of governments or corporations.

    Our Solution: EchoDeck is built on Nostr, a decentralized, censorship-resistant protocol. Your identity (Private Key) is yours alone. No admin can delete your account. No server can ban your voice.

Wall 2: The Wall of Access

For millions of users in restrictive network environments (e.g., behind the GFW), accessing the free world is technically difficult and legally risky.

    Our Solution: Resilient Relay Proxies. EchoDeck creates a secure tunnel to the decentralized world. We deploy a distributed network of edge-accelerated relays and reverse proxies that allow users to connect to the global Nostr network seamlessly, without the need for complex VPNs or specialized networking knowledge. Information should flow like water.

Wall 3: The Wall of Content

Web3 is sovereign but often shallow. Web2 is deep but walled off. The "Gap" between high-quality blogs (RSS) and social discussion (Social Media) stifles knowledge transfer.

    Our Solution: The Unified Bridge. We treat RSS and Nostr as equals. EchoDeck allows you to consume Web2 content with Web3 sovereignty—and for the first time, migrate value (Zaps/Tips) from the new world back to the old.

🏛 The Two Pillars

EchoDeck is not just a client; it is a fusion engine supported by two massive pillars, enhanced by Artificial Intelligence.
1. The Nostr Feed (The Social Graph)

Experience the world as it actually is, not as an algorithm decides you should see it.

    True Feed: We rebuilt the timeline sorting engine to prioritize temporal reality over engagement hacking. You see the raw, unfiltered pulse of the planet.

    Immutable Interactions: Every Like, Repost, and Reply is cryptographically signed and broadcasted to multiple relays. History cannot be rewritten.

    Value for Value (Zap System): We integrated Bitcoin Lightning (Zaps). Don't just "Like" a deep dive; tip the author. We incentivize depth over clickbait.

    Trend & Discovery: A decentralized Trend module aggregates the hottest topics across the relay network, while our Explore engine allows granular search across the global note repository.

    Smart Following: Discover creators in the feed and follow them instantly. Your social graph is portable—it moves with you, not us.

2. The RSS Reader (The Content Graph)

The depth of the legacy web, modernized for the decentralized era.

All fetches are aggregated into the "Reads" module:

    For You: Curated, high-quality sources selected by the EchoDeck editorial DAO. Free to read, zero setup required.

    My Feed: Your personal, sovereign subscription list.

    Saved: A cross-protocol bookmark system. Save a Nostr Note next to a New York Times article.

The Power Tools:

    Universal Parser (RSSHub Integration): Paste any URL. Our built-in private RSSHub instance attempts to parse it into a readable feed. Twitter profiles, Telegram channels, standard blogs—we bridge them all.

    Nostr Bots for RSS: Every RSS feed you subscribe to is mirrored as a Nostr Bot on our platform. This means you can interact with a static blog post as if it were a social user—reply to it, zap it, and share it.

    Manage Subscriptions: Full OPML import/export support. You own your data.

3. The AI Layer (The Amplifier)

We use LLMs not to generate content, but to filter noise and enhance understanding.

    "Toxic" Summaries: Boring summaries are useless. Our AI reads RSS articles and gives you a sharp, witty, and sometimes "Toxic" TL;DR to help you decide if it's worth your time.

    Quality Grading: AI assigns a "Depth Score" to articles. Skip the fluff, read the insights.

    Anti-Spam Shield: A client-side AI filter that cleans your Nostr feed of bots and crypto-scams without central censorship.

🏗 Architecture & Technology

How do we deliver a seamless, Web2-like experience on top of fragmented Web3 protocols?
The Stack

    Core: Next.js 14 (App Router) for server-side rendering and SEO.

    UI: Tailwind CSS + Shadcn/UI.

    State: Zustand for high-frequency WebSocket state management.

The "Resilient" Infrastructure

To fulfill our promise of breaking the Wall of Access, we engineered a unique networking layer:

    Edge Relay Proxies: We don't just connect you to Damus or Eden. EchoDeck routes WebSocket traffic through a mesh of ephemeral edge functions. This obfuscates the traffic signature, allowing users in restrictive regions to maintain stable connections to global Relays.

    Server-Side RSS Aggregation: Instead of your browser fetching RSS (leaking your IP to publishers), our servers fetch, parse, and normalize the data, delivering it to you via a clean API. Privacy is default.

The Hybrid Database

    PostgreSQL + Prisma: While content lives on Relays, your experience (User Tiers, Quest Progress, Read Status) lives in our high-performance Meta Layer.

    Non-Custodial Auth: We use NIP-07 or local encryption. We verify who you are, but we never hold the keys to become you.

🔑 The Invite Protocol (Gamified Growth)

EchoDeck is currently in Closed Beta. To maintain the quality of the network and prevent the "Eternal September" effect, we utilize a tiered access system based on Proof of Engagement.
Tier 0: The Genesis Nodes

    Who: Industry leaders, top KOLs, and technical contributors.

    Power: Granted 10 Genesis Codes. These codes are immune to decay.

Tier 1: The Citizens

    Who: Users invited by a Genesis Node.

    Initial State: 0 Invites. You are here to consume and learn.

    The Awakening: To unlock the ability to invite others, you must complete the "Awakening Quests":

        Subscribe to 3 RSS Feeds (Curate your input).

        Publish your first Hello World note on Nostr (Prove your voice).

    Reward: Upon completion, the contract unlocks 5 Invite Codes.

Tier 2: The Explorers

    Who: Users invited by Citizens.

    Path: Similar quest structure, ensuring every new member adds value to the network before expanding it further.

This system ensures that EchoDeck grows not through spam, but through active, educated participation.
🗺 Roadmap

    [x] Phase 1: Foundation. Hybrid Feed, RSS Engine, Proxy Network.

    [x] Phase 2: The Bridge. Zap RSS, AI Summaries.

    [x] Phase 3: The Virus. Gamified Invite System.

    [ ] Phase 4: Mobile. Native iOS/Android Apps (React Native).

    [ ] Phase 5: Communities. NIP-72 Groups implementation.

🤝 Feedback & Community

We are building this for the free thinkers, the builders, and the explorers.

    Found a bug? Open an Issue

    Want a feature? Start a Discussion

    Need an Invite? Keep an eye on this repo. We drop Genesis Codes in the comments sporadically.

<div align="center"> <p>Built with ❤️ and ⚡️ for the Sovereign Web.</p> <p>© 2026 EchoDeck Team</p> </div>
