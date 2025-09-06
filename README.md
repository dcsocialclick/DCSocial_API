<img width="65" height="21" alt="image" src="https://github.com/user-attachments/assets/eaf9fd87-908d-4889-b638-a69883d15ff3" /># DCSocial_API

# DCSocial

- Website:
http://dcsocial.click/
- X:
https://x.com/dcsocialclick
- For Dev:
https://app.daily.dev/dcsocial/posts
- Discord:
https://discord.gg/7BHBCR2MrS
- Medium:
https://medium.com/@dcsocial.click

DCSocial – Decentralized Creator Social Platform

DCSocial is a next-generation social networking dApp designed for creators, leaders, and their communities.
It enables a decentralized attention economy, where influence and engagement are measurable, tradeable, and directly beneficial to those who generate value.

Our mission: Own your audience. Save your audience. Build with them.

🚀 Vision

Traditional platforms monetize creators’ audiences without transparency or shared benefits.
DCSocial flips this model by giving creators and communities the ability to:

Own their audience: direct, verifiable connections with no intermediaries.

Protect their audience: safeguard against spam, low-quality feeds, and algorithmic manipulation.

Build sustainable growth: leverage decentralized scoring and referral mechanics to grow influence and monetize attention ethically.

🔑 Key Features

Decentralized Feed Scoring (DFS)
A transparent algorithm that ranks posts using:

Referral weight (direct connections prioritized).

Engagement metrics (views, likes, shares, comments).

Ethical credit score (trustworthiness & positive contributions).

Time decay (freshness of content).

Referral-Based Growth Engine
Creators invite their audience through unique referral links. Audiences who join are directly connected to their referrer, creating multi-level, non-exploitative referral networks.

Gamified Reputation System

Badges (Founder, Rescued, Top Influencer).

Missions for community growth.

Credit staking to boost content visibility.

Community-First Communication

Group chats with threat-mode protection: max 20 messages/minute, high-score messages prioritized.

Signal-to-noise optimization for meaningful conversations.

Impact Dashboard for Leaders

Track F1/F2/F3 referral growth.

Average audience credit score.

Post performance analytics.

Referral chain visualization.

🏗 System Architecture

Frontend: Next.js + Telegram WebApp integration, PWA for mobile install.

Backend: Modular API with pluggable scoring algorithms.

Database: Flexible (Firebase or MongoDB for MVP, scalable to decentralized storage in production).

Config Layer: Unified config for FE/BE to ensure consistent scoring and logic.

📊 FeedScore Formula

FeedScore = ReferralLevelWeight + EngagementScore + CreditScore - TimeDecay

ReferralLevelWeight: F1 = 100, F2 = 50, F3 = 20

EngagementScore: actions in first 24h (views, likes, comments, shares)

CreditScore: decentralized ethical credit system

TimeDecay: decreasing weight over time

Balancing:

70–80% feed from referral chain

20–30% from outside exposure

High-credit posts can bypass referral order

Experimental boosted posts tested dynamically

🧩 Roadmap

MVP (Centralized backend + Telegram integration)

Secure onboarding via referral links

Feed + explore tabs with scoring

Group chats with threat-mode filtering

Leader dashboard

Phase 2 (Hybrid decentralized)

Smart contract integration for CreditScore

On-chain verification of referrals

Tokenized incentives for creators and audiences

Phase 3 (Full decentralization)

Decentralized hosting & storage

On-chain governance for algorithm updates

Autonomous credit marketplace

👥 Target Users

Leaders / Content Creators / KOLs

Grow their audience through verifiable referrals

Monetize attention with fairness and transparency

Strengthen reputation through credit scoring

Audience Members

Join communities via trusted leaders

Earn recognition badges (e.g., Rescued by [Leader])

Improve personal feed quality by inviting new members

Explorers

Discover leaders and content outside direct referrals

Become new leaders by building their own audience

🛡 Security & Anti-Abuse

API protected with admin keys and rate limits

Anti-fraud mechanisms against fake likes, views, and shares

Cooldowns on high-frequency actions

Validation rules for unique likes, shares, and referral integrity

💡 Why DCSocial?

Unlike legacy platforms, DCSocial aligns incentives between platform, creators, and communities.
No exploitation, no shadow algorithms – just transparent growth, shared value, and sustainable impact.

DCSocial is where attention meets ownership.

📬 Get Involved

Developers: Contribute to open-source modules.

Creators: Onboard early and secure Founder badges.

Community Members: Join, engage, and shape the ecosystem.

📄 License

MIT License – build, fork, and contribute freely.

