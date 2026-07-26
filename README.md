<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,100:4A00E0&height=180&section=header&text=Pranav%20Raut&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=8E2DE2&center=true&vCenter=true&width=600&lines=AI+Engineer+%7C+Full-Stack+Developer;Building+local-first%2C+BYOK+LLM+apps;Shipping+the+AI+infra+I+build+with+to+npm;DeFi+%E2%86%92+AI%3A+5%2B+years+in+production)](https://github.com/Pranavraut033)

[![Portfolio](https://img.shields.io/badge/Portfolio-pranavraut.dev-8E2DE2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.pranavraut.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pranav%20Raut-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rautpranav/)
[![npm](https://img.shields.io/badge/npm-pranavraut-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/~pranavraut)
[![Stack Overflow](https://img.shields.io/badge/Stack%20Overflow-6942651-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white)](https://stackoverflow.com/users/6942651/pranav-raut)
[![Email](https://img.shields.io/badge/Email-hello%40pranavraut.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@pranavraut.dev)

![GitHub followers](https://img.shields.io/github/followers/Pranavraut033?label=Follow&style=social)
![GitHub stars](https://img.shields.io/github/stars/Pranavraut033?label=Stars&style=social)
![Profile views](https://komarev.com/ghpvc/?username=pranavraut033&color=8E2DE2)

</div>

I'm an AI engineer with full-stack roots — 5+ years across TypeScript, Node.js, React, and Next.js, now focused on LLM integrations, agentic coding workflows, and multi-provider tooling. I build **local-first, bring-your-own-key LLM products** — apps where your data and API keys never leave your machine — and publish the infrastructure behind them as open-source npm packages. Before that: production systems at scale — on-chain data indexers, microservices, and data pipelines. Currently finishing an M.Sc. in Computer Science in Berlin, with a thesis on human-in-the-loop override policies for AI decision systems.

## 🤖 AI Engineering

**[Udaan — AI Resume Builder](https://github.com/Pranavraut033/resume-builder)** ✈️
Local-first AI desktop app (Next.js 16 + Tauri 2 + SQLite) that reads a job description and generates a tailored, ATS-friendly resume and cover letter. Chat assistant for edits, ATS guidance, and interview prep; an AI humanizer with reviewable diffs; WYSIWYG editing on the rendered document. Runs on a multi-provider abstraction I built (OpenAI, Claude, Gemini, Grok, Perplexity, keyless gateway — or fully offline via local Ollama), with fixture-based testing, token-usage tracking, and AES-256-GCM-encrypted key storage. Prebuilt for macOS, Windows & Linux on the [releases page](https://github.com/Pranavraut033/resume-builder/releases).

**[@pranavraut033/llm-core](https://www.npmjs.com/package/@pranavraut033/llm-core)** — the engine underneath: a client-side, BYOK-first LLM toolkit with a typed provider registry, streaming completion/chat/structured-output controllers, React hooks, and a Handlebars prompt-template system. No server, no lock-in.

**[@pranavraut033/ats-checker](https://www.npmjs.com/package/@pranavraut033/ats-checker)** — npm package that scores resumes for ATS compatibility, so the generated documents actually make it past the bots.

> The pattern: build the AI product, then open-source the infrastructure it runs on.

## 🛠 Tech Stack

<div align="center">

**AI / LLM**

![Claude](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=claude&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-5C2D91?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)

Agentic coding workflows · custom skills & subagents · tool-calling pipelines · RAG · prompt engineering · LLM evaluation & fixture-based testing

**Languages & Frameworks**

[![Skills](https://skillicons.dev/icons?i=ts,js,python,react,nextjs,vue,nuxtjs,tailwind,nodejs,express,fastapi,graphql&theme=dark)](https://github.com/Pranavraut033)

**Apps, Data & Infra**

[![Skills](https://skillicons.dev/icons?i=tauri,postgres,mongodb,sqlite,redis,prisma,docker,aws,githubactions,prometheus,grafana,vercel&theme=dark)](https://github.com/Pranavraut033)

</div>

## 🚀 Things I've Shipped

| Project | What it is |
|---|---|
| **[Portfolio — The Digital Architect](https://www.pranavraut.dev)** | Full-3D portfolio: fly through a synthwave world built with Preact + Three.js, or switch to a plain résumé view |
| **[WebSecScan](https://web-sec-scan.vercel.app)** | Web security scanner with live demo, versioned releases, and CI ([repo](https://github.com/Pranavraut033/WebSecScan)) |
| **[WeatherInsight](https://github.com/Pranavraut033/WeatherInSight)** | German weather data platform: Python/Spark/Airflow pipeline over raw DWD data into MinIO + PostgreSQL, 67 engineered features behind a FastAPI layer with auth & rate limiting, Prometheus/Grafana monitoring — 159 tests, 85% coverage |
| **[Local Media Discovery](https://github.com/Pranavraut033/local-media-discovery-app)** | Privacy-first, local-only media feed: turns your photo/video library into a ranked swipeable PWA — Fastify + Next.js + BullMQ, no cloud, no telemetry |
| **[thetascreener](https://thetascreener-ten.vercel.app)** | Options screener built with Next.js |
| **[telegram-backup](https://github.com/Pranavraut033/telegram-backup)** | Python CLI for backing up Telegram media, with a full CI/release pipeline |

**Professional work** — [DefiEdge](https://app.defiedge.io) (Senior Full-Stack Dev): led the platform revamp for a DeFi protocol managing **$20M TVL and $7.8B+ cumulative volume** — The Graph subgraphs indexing 6+ networks, page loads cut from ~4.5s to ~250ms, monolith split into services (~3s → ~300ms API responses) · **Maple Finance**: Next.js + Contentful marketing site rebrand — content updates went from days to minutes · **Eatabl** (founding engineer @ Rethynk): built from a blank repo to launch with 20+ restaurants and 100+ active users · **ReUseIT**: cross-platform recycling app with TensorFlow image recognition.

**Open-source contributions** — [DefiLlama/DefiLlama-Adapters](https://github.com/DefiLlama/DefiLlama-Adapters) · [Zapper-fi/studio](https://github.com/Zapper-fi/studio) · [CamelotLabs/vaults-list](https://github.com/CamelotLabs/vaults-list) · [delta-hq/l2-lxp-liquidity-reward](https://github.com/delta-hq/l2-lxp-liquidity-reward)

## 📊 Stats

<div align="center">

![Pranav's github stats](https://github-readme-stats.vercel.app/api?username=Pranavraut033&show_icons=true&theme=tokyonight&hide_border=true)
![Streak stats](https://streak-stats.demolab.com?user=Pranavraut033&theme=tokyonight&hide_border=true)

![Pranav's top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Pranavraut033&layout=compact&theme=tokyonight&hide_border=true)

![Pranav's contribution snake](./contribution.svg)

</div>

## 📌 The Rest

**Education** — M.Sc. Computer Science, IU International University of Applied Sciences, Berlin (2024–present) · B.E. Computer Science, MCT's Rajiv Gandhi Institute of Technology, Mumbai (2016–2020)
**Thesis** — Human-in-the-Loop Override Policies for AI-Driven Sequential Decision Loops in Contested Environments: A LAWS Governance Perspective (2026)
**Publication** — [Recognise Object for Visually Impaired Using Computer Vision](https://www.ijrte.org/wp-content/uploads/papers/v8i6/F9579038620.pdf) (IJRTE, 2020)
**Certification** — Practical GitHub Actions (LinkedIn Learning)
**Languages** — English (C1) · Hindi (native) · Gujarati (native) · German (A2)
**Off the keyboard** — cycling · reading · gaming

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:4A00E0,100:8E2DE2&height=100&section=footer)

</div>
