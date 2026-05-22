### Mimo Dashboard

Web3 multi-wallet automation dashboard.

> **Credits / Attribution**
> - Originally based on [SoundnessLabs/testnet-vapps](https://github.com/SoundnessLabs/testnet-vapps) — Soundness Layer testnet vApps submission scaffold.
> - Licensed under MIT, © 2025 Sound Layer (see `LICENSE`).
> - This repo is a personal deployment / fork by [@reziookk](https://github.com/reziookk).

---

### Soundness Layer Testnet vApps (upstream README)

Verify GitHub ownership and submit vApp and zkApp proposals for Soundness Layer testnet access.

[![Discord](https://img.shields.io/discord/1234567890?label=Discord&logo=discord)](https://discord.gg/soundnesslabs)
[![PRs](https://img.shields.io/github/issues-pr/soundlayer/testnet-vapps?label=Submissions)](https://github.com/SoundnessLabs/testnet-vapps/pulls)

## Quick Start

1. Fork this repository
2. Copy `TEMPLATE.md` to `submissions/{category}/{your-github-username}.md`
3. Fill out your vApp proposal
4. Create Pull Request
5. Join [Discord](https://discord.gg/soundnesslabs) and use `/submit-vapp` command

## Categories

- **identity** - Authentication, credentials, reputation
- **defi** - Finance, trading, payments  
- **social** - Community, content, messaging
- **gaming** - Games, NFTs, entertainment
- **infrastructure** - Tools, analytics, monitoring
- **other** - Innovative ideas

## Requirements

- Valid GitHub username (must match PR author)
- Discord ID for verification
- Technical architecture with SL integration
- Realistic development timeline

## Process

1. **Submit PR** → Automated validation
2. **Team review** → 2-3 business days  
3. **Approval** → Sound_dev Discord role
4. **Build PoC** → Testnet access

## Resources

- [X](https://x.com/SoundnessLabs)
- [Discord](https://discord.gg/soundnesslabs)



**Ready to build?** [Submit Your vApp](/TEMPLATE.md) • [Join Discord](https://discord.gg/soundnesslabs)

---

## Web3 Multi-Wallet Automation Dashboard

A production-grade multi-wallet automation dashboard built with Next.js 14, Shadcn UI, and ethers.js v6.

### Features
- **Dashboard** — Worker node table with live status, KPI cards, and master controls (Start All / Pause All / Stop All)
- **Live Log Viewer** — Real-time log stream with level filtering (info / warn / error / success), auto-scroll, drag-to-resize, and .log download
- **Script Generator** — Paste ABI/docs, select network + script type, generate full ethers.js v6 multi-wallet automation script via MiMo LLM (simulated)
- **Worker Nodes** — Full management page with search, network/status filters, and Add Wallet dialog
- **Proxy & RPC** — CRUD management for RPC endpoints and proxies with latency monitoring

### Stack
- Next.js 14 (App Router) · TypeScript · Tailwind CSS · Shadcn UI · ethers.js v6 · Zustand

### Run Locally

```bash
pnpm install
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000).

### Build

```bash
pnpm build
```
