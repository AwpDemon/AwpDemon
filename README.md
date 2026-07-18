### Hi, I'm Ali

MIS student at the University of Georgia ('27), based in Athens / Atlanta, looking for a **Summer 2026 internship** — software engineering, automation/internal tools, or data. I'm the kind of MIS student who runs his own public-facing server: everything below is deployed, tested, and used daily, not portfolio filler.

Day-to-day: **Python, JavaScript/Node.js, SQL** for building; Tableau and Power BI when the deliverable is a dashboard; and a lot of AI-in-the-loop automation on my own infrastructure.

### Things I've built

- **[doctor-patient-portal](https://github.com/AwpDemon/doctor-patient-portal)** — full-stack healthcare portal: Node/Express/SQLite, 30+ REST endpoints, TOTP 2FA, role-based access control (doctor/patient/admin), rate-limited auth, and a 21-test Jest/Supertest suite running green in CI.
- **[wispr-clone](https://github.com/AwpDemon/wispr-clone)** — push-to-talk voice dictation for Windows (Groq Whisper + Llama 3.1 cleanup). The fun part: a VAD watcher speculatively fires partial transcriptions during pauses so the common case lands with near-zero perceived latency. 42 pytest tests.
- **[agent-chat-mcp](https://github.com/AwpDemon/agent-chat-mcp)** + **[agentchattr-remote](https://github.com/AwpDemon/agentchattr-remote)** — cross-machine message broker for AI coding agents. Claude Code instances on my desktop, laptop, and server send each other tasks and context through a central hub via MCP.
- **[homelab](https://github.com/AwpDemon/homelab)** — public services behind a Cloudflare Tunnel with Authentik SSO, a Minecraft server kept online through an L7 attack, and a local LLM endpoint driving my automations. Sanitized configs + a stdlib-only health checker included.
- **[mc-afk](https://github.com/AwpDemon/mc-afk)** — multi-account Minecraft keep-alive bot with a web dashboard, Microsoft OAuth login, auto-reconnect, Discord alerts, and Docker deployment.

### Data & analytics

The stats layer behind the dashboards — backtesting, calibration, significance testing — is where I've put real effort:

- **[catastrophe-loss-analysis](https://github.com/AwpDemon/catastrophe-loss-analysis)** — 67K insurance transactions; headline findings formally tested (Welch's t, bootstrap, chi-squared) plus a 20K-iteration hurricane Monte Carlo sizing a reinsurance layer against a 1-in-100 PML.
- **[insurance-risk-model](https://github.com/AwpDemon/insurance-risk-model)** — hand-tuned actuarial scorecard backtested against logistic regression. Matches on ranking (AUC 0.83), *isn't* calibrated (Brier 0.12 vs 0.07) — and the README explains why and what to overlay.
- **[retail-sql-analytics](https://github.com/AwpDemon/retail-sql-analytics)** — 8-table 3NF Postgres schema, 15 analytical queries (RFM churn, cohort retention, cross-sell lift), reproducible in <30 s via an in-memory DuckDB path.
- **[student-budget-powerbi](https://github.com/AwpDemon/student-budget-powerbi)** — 11 DAX measures, 2-layer anomaly detection, Holt's-linear forecast with bootstrapped 80% prediction intervals.

### Current focus

Shipping more AI-agent infrastructure (the message broker above is growing into a proper multi-agent coordination layer), and deepening the stats that separate "I made a chart" from "I can defend a number in a meeting." Member of Gamma Iota Sigma (risk management & insurance fraternity) at UGA — that's where the insurance-flavored projects come from.

Open to chatting about software, AI automation, data, or self-hosted infrastructure — reach me on [LinkedIn](https://www.linkedin.com/in/aliaskari3284).
