## Hi there 👋

<!--
**pratts/pratts** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Prateek Sharma

Backend and systems engineer, 10+ years, mostly fintech/crypto, B2B SaaS, and
real-time gaming. I build services and infrastructure where correctness,
reliability, and scale matter more than surface area: API design, data
modelling, workflow orchestration, and the observability to keep it all
honest.

[Site](https://prateeksharma.me) ·
[Resume](https://drive.google.com/file/d/1K3zOHEUgZ6lBQ2ntsQGcQvtzoNFtvk4x/view?usp=sharing) ·
[LinkedIn](https://www.linkedin.com/in/prateeksharma28/) ·
[Email](mailto:prateeksharma.2801@gmail.com)

## What I work on

- **Data & integrations:** parsing and reconciling on-chain data across
  several blockchains, multi-tenant PostgreSQL schema design, full-text
  search, and Excel/S3 ingestion pipelines.
- **Fault-tolerant workflows:** Temporal-orchestrated, idempotent sync jobs
  with reconciliation and validation instead of best-effort scripts.
- **Real-time systems:** poker game and tournament engines handling
  thousands of concurrent players with event-driven, low-latency backends.
- **Platform work:** migrations (PHP to Node.js, services to Django,
  serverless booking engines), RBAC and identity, and observability with
  OpenTelemetry.

## Experience

| Company | Role | Dates |
|---|---|---|
| [CoinTracker](https://prateeksharma.me/experience/cointracker/) | Software Engineer | Sep 2025 – Apr 2026 |
| [Emission Critical](https://prateeksharma.me/experience/emission-critical/) | Lead Software Developer | May 2022 – Mar 2025 |
| [Mind Sports League](https://prateeksharma.me/experience/mind-sports-league/) | Tech Lead | Mar 2021 – May 2022 |
| [Yolobus](https://prateeksharma.me/experience/yolobus/) | Senior Software Engineer | Mar 2020 – Mar 2021 |
| [Adda52 (Delta Corp)](https://prateeksharma.me/experience/adda52/) | Graduate Trainee → Senior Software Engineer | Sep 2014 – Feb 2020 |

Full write-ups, including engineering decisions on each, are on the
[Experience page](https://prateeksharma.me/experience/).

## Selected projects

- **[goroomlib](https://github.com/pratts/goroomlib)**: a thread-safe Go
  library providing a reusable Room-User architecture for real-time systems
  like chat and multiplayer games.
- **[wazirx-connector-go](https://github.com/pratts/wazirx-connector-go)** /
  **[wazirx-connector-java](https://github.com/pratts/wazirx-connector-java)**:
  unofficial REST/WebSocket clients for the WazirX crypto exchange, both
  acknowledged by WazirX's co-founder.
- **[tidylnk](https://admin.tidylnk.com/)**: a self-hosted URL shortener
  with a React admin panel, built with Go, Redis, and PostgreSQL.
- **[tts-study-assistant](https://github.com/pratts/tts-study-assistant)**:
  a Chrome extension for saving and listening to notes from any webpage,
  backed by a Go/Fiber API.
- **[git-why](https://github.com/pratts/git-why)**: a Claude Code skill
  that writes the design reasoning behind non-trivial commits to `git
  notes`, so the "why" survives after the chat that produced it is gone.
- **[video-translator](https://github.com/pratts/video-translator)** +
  **[OpenVoice fork](https://github.com/pratts/OpenVoice)**: a local AI
  dubbing pipeline that transcribes, translates, and re-synthesizes speech
  in a target language, patched to clone short clips on CPU.

More on the [Projects page](https://prateeksharma.me/projects/).

## Open source

- Added missing stats/metrics fields to the official
  [Meilisearch Go](https://github.com/meilisearch/meilisearch-go/pull/621)
  and [Java](https://github.com/meilisearch/meilisearch-java/pull/830)
  clients, closing issues the maintainers had already filed. Merged.
- Audited WazirX's official
  [Postman API collection](https://github.com/WazirX/wazirx-api-postman/pull/7)
  against its live spec and fixed real drift, then turned the process into
  a [reusable Claude Code Skill](https://github.com/WazirX/wazirx-api-postman/pull/8)
  for the maintainers.
- Added missing endpoints to WazirX's official
  [Python connector](https://github.com/WazirX/wazirx-connector-python/pull/19).
- An early [DuckDuckGo Instant Answer](https://github.com/duckduckgo/zeroclickinfo-goodies/pull/1427)
  contribution, merged back in 2015.

Full list, including what's still open, on the
[Open Source page](https://prateeksharma.me/open-source/).

## Currently exploring

Go and systems internals, through small hobby projects: a concurrency-safe
room/user library, exchange API connectors, and a handful of CLI and media
tools.

## Stack

Go · TypeScript · Python · Java · Node.js/NestJS · PostgreSQL · Redis ·
Temporal · AWS · Docker · Kubernetes · OpenTelemetry

---

More detail, including how each project and role broke down technically, is
at [prateeksharma.me](https://prateeksharma.me).
