### Hi, I'm James Dye 👋
**AI-orchestrating systems builder — Columbus, OH · remote**

I take a problem in a domain I've never touched, attack the knowledge gap first, and come back with working software. The method *is* the product: I run several AI models against each other to cover their blind spots, keep the architecture and the failure modes under my own hands, and try to break everything I build before I'll call it finished.

Almost all of the work below was built in 2026 — nights and weekends, around a full-time field job. I'm now doing this full-time for clients.

---

#### Selected work

**🛠 PackSmith** — a Unity Editor QA tool that scans imported asset packs, flags what will break, and applies rollback-safe fixes with proof. Taken to v0.1.0 with a green release-readiness gate and a live in-app update channel. → [repo](https://github.com/Xyloth/packsmith) · [site](https://www.xyflowinnovations.com/packsmith)

**📍 Boundary XYQ** — a near-launch iOS field app for land surveyors: CSV/DXF import, a COGO constraint/proof engine, MapKit rendering. Build 18, release gate green, validated against an 845-scenario geometry gauntlet. → [overview](https://www.xyflowinnovations.com/boundary-xyq)

**📄 SourceDeck** — a local-first "evidence command center" that turns messy records into source-chained cards with exact quotes and page anchors, then exports verified-only packets. Passes a **63-case hostile-input gauntlet** (prompt-injection, redaction-leak, signed-manifest trust) with zero failures. → [repo](https://github.com/Xyloth/SourceDeck)

**🛰 XPRIZE Quantum (rare-event QAE)** — a benchmark harness for an XPRIZE Quantum Applications submission on rare-event collision-risk estimation: classical baselines, stress regimes, and Phase-II quantum resource estimates. Published with a DOI. → [repo](https://github.com/Xyloth/xpqa-rare-event-qae) · [DOI](https://doi.org/10.5281/zenodo.18816742)

**🌐 GNSS Clock Pipeline** — a production-style Python ETL over 8 years of multi-constellation GNSS + space-weather data. I'll point you straight at the part most people hide: the [results writeup](https://github.com/Xyloth/gnss-clock-pipeline) where the ML prediction goal *didn't* pan out, and says so. Honest negative results are part of how I work.

*Also: a zero-dependency local-first writing app ([Generation Engine](https://github.com/Xyloth/Generation-Engine)), a multi-agent research harness ([Attractor Observatory](https://github.com/Xyloth/Attractor-Observatory)), two Unity game prototypes, and a couple of vertical SaaS prototypes. ~18 repos, all this year.*

---

#### How I build
The thing that separates this from "I vibe-coded a demo": I ship with adversarial test gauntlets and I write down what fails. A 50/50 release-readiness gate on the Unity tool. 845 scenarios on the survey app. 63 hostile inputs on the evidence system. When an approach loses — like the GNSS model, or an AI image-compositing pass that scored 4/10 — that goes in the log too. Verified beats impressive.

#### Stack
`Python` · `TypeScript` (React / Node / React Native) · `C#` (.NET + Unity) · iOS / MapKit · RAG & LLM orchestration (Claude Code, Codex, the Anthropic & OpenAI APIs) · Parquet/Arrow data pipelines · `git`

---

#### Work with me
If my path looks non-traditional, the fastest way to see how I work is to put me on it. I'll take a small, fixed-price, time-boxed build — you get a working artifact and a teardown at the end. If it lands, we keep going. If it doesn't, you keep the work.

📫 **founder@xyflowinnovations.com** · [xyflowinnovations.com](https://www.xyflowinnovations.com) · [LinkedIn](https://www.linkedin.com/in/xyflow)
