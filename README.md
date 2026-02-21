<div align="center">

# ✦ Conference

**A hub for two missions — teach anyone to build with free AI, and help organizations modernize for free.**

[![Learn Guide](https://img.shields.io/badge/🎓_Learn_Guide-live-ff6b9d?style=for-the-badge)](https://learn-guide.vercel.app)
[![Templates](https://img.shields.io/badge/📦_Templates-live-7c4fd0?style=for-the-badge)](https://learn-guide.vercel.app/templates)
[![License](https://img.shields.io/badge/license-MIT-4af0e8?style=for-the-badge)](LICENSE)

</div>

---

## 🗺️ What This Is

```
conference/
│
├── 🎓 Goal 1 — Educational Platform
│   Teach kids, teens & adults to build real projects using free AI tools.
│   No paid APIs. No experience needed.
│
└── 🤝 Goal 2 — Volunteer Platform  (in development)
    Connect volunteers with schools & nonprofits that need
    low-cost database migration using agentic AI.
```

---

## 🌐 Live Sites

| Site | URL | Status |
|------|-----|--------|
| 🎓 Learn Guide | [learn-guide.vercel.app](https://learn-guide.vercel.app) | ✅ Live |
| 📄 Portfolio Basic | [portfolio-basic-woad.vercel.app](https://portfolio-basic-woad.vercel.app) | ✅ Live |
| 🤖 Portfolio AI | [portfolio-ai-liart-seven.vercel.app](https://portfolio-ai-liart-seven.vercel.app) | ✅ Live |
| 🎮 Game Template | [game-template-mocha.vercel.app](https://game-template-mocha.vercel.app) | ✅ Live |
| 💬 Chatbot Template | [chatbot-template-alpha.vercel.app](https://chatbot-template-alpha.vercel.app) | ✅ Live |

---

## 📦 Repositories

| Repo | Description | Link |
|------|-------------|------|
| `conference-learn-guide` | Learn Guide website — kids & adults learning tracks, tutorials, AI setup | [→ GitHub](https://github.com/Momoiroart/conference-learn-guide) |
| `conference-portfolio-builder` | All templates + tutorials in one monorepo, each auto-deployed to Vercel | [→ GitHub](https://github.com/Momoiroart/conference-portfolio-builder) |
| `conference-volunteer-platform` | Volunteer ↔ org matching platform (in development) | [→ GitHub](https://github.com/Momoiroart/conference-volunteer-platform) |

---

## 🎓 Goal 1 — Educational Platform

Teach anyone to build real projects from scratch using only free tools.

### Free Templates — Download & Go

All templates are single HTML files. No install, no framework, no account needed.

| Template | Best For | Live Demo |
|----------|----------|-----------|
| 📄 **Portfolio Basic** | First portfolio, clean & simple | [Try it →](https://portfolio-basic-woad.vercel.app) |
| 🤖 **Portfolio AI** | Portfolio + AI chat assistant | [Try it →](https://portfolio-ai-liart-seven.vercel.app) |
| 🎮 **Game Template** | Simple 2D browser game starter | [Try it →](https://game-template-mocha.vercel.app) |
| 💬 **Chatbot** | AI chatbot base to customize | [Try it →](https://chatbot-template-alpha.vercel.app) |

### Learning Tracks

**[→ Start at learn-guide.vercel.app](https://learn-guide.vercel.app)**

| Track | For | What You Build |
|-------|-----|----------------|
| 🧒 Kids (Ages 10–14) | Total beginners | First game, first portfolio |
| 👤 Adults (Ages 15+) | Career changers, learners | Professional portfolio, chatbot |

```
Install Ollama (free)  →  Try Claude Code (free)  →  Pick a Template  →  Ship It 🚀
```

### Tools We Use (All Free)

| Tool | Purpose | Cost |
|------|---------|------|
| [Ollama](https://ollama.com) | Run AI models locally | $0 |
| [Claude Code](https://claude.ai/code) | AI coding assistant | $0 |
| [Astro](https://astro.build) | Static site framework | $0 |
| [Vercel](https://vercel.com) | Hosting + auto-deploy | $0 |

---

## 🤝 Goal 2 — Volunteer Platform *(in development)*

Connect skilled volunteers with schools and nonprofits that need database modernization — no expensive APIs, everything runs locally with Ollama.

```
Organization           Volunteer            AI (Ollama)
      │                    │                     │
      │── Submit Needs ──→ │                     │
      │← AI Assessment ────│←── Analyzes ───────│
      │── Data Upload ────→│                     │
      │                    │←── Migration Help ──│
      │←── Done! ──────────│                     │
```

**Who we help:** schools, nonprofits, community centers, small businesses with legacy Excel/Access databases.

> Repo: [conference-volunteer-platform](https://github.com/Momoiroart/conference-volunteer-platform)

---

## 💰 Cost: $0

| Component | Traditional Cost | Our Solution |
|-----------|-----------------|--------------|
| AI / LLM API | $100–1,000/mo | **Ollama** — free, local |
| Coding assistant | $20/mo | **Claude Code** — free |
| Hosting | $20/mo | **Vercel** — free tier |
| Database | $50/mo | **SQLite** — free |
| **Total** | **$170+/mo** | **$0 forever** |

---

## 🗂️ Full Project Structure

```
conference/                              ← You are here (hub)
│
├── 📁 portfolio-builder/               ← Goal 1: templates & tutorials
│   └── templates/
│       ├── portfolio-basic/            →  portfolio-basic-woad.vercel.app
│       ├── portfolio-ai/               →  portfolio-ai-liart-seven.vercel.app
│       ├── game-template/              →  game-template-mocha.vercel.app
│       └── chatbot-template/           →  chatbot-template-alpha.vercel.app
│
├── 📁 learn-guide/                     ← Tutorial website
│   └── src/pages/
│       ├── kids/                       →  /kids
│       ├── adults/                     →  /adults
│       ├── templates.astro             →  /templates
│       └── ai-setup.astro              →  /ai-setup
│
└── 📁 ai-volunteer-platform/           ← Goal 2: volunteer matching
    └── src/
        ├── agents/                     ← AI migration agents
        ├── connectors/                 ← Legacy DB readers (Excel, CSV, Access)
        └── dashboard/                  ← Volunteer management
```

---

## 🚀 Development Phases

| Phase | What | Status |
|-------|------|--------|
| 1 — Foundation | Project setup, tool integration | ✅ Done |
| 2 — Templates | 4 templates + learn guide site | ✅ Done |
| 3 — Educational Platform | Kids + adult tracks, tutorials | 🔄 In Progress |
| 4 — Volunteer Platform | AI agents, matching system | 📋 Planned |
| 5 — Launch | Recruit volunteers, onboard orgs | 📋 Planned |

---

## 🤝 Contributing

1. Fork the relevant sub-repo
2. Create a feature branch
3. Submit a pull request

No experience needed — we welcome all skill levels!

---

## 📄 License

MIT — Use anything here however you like.

---

<div align="center">

Built with free tools. Powered by community. For everyone. 🌐

</div>
