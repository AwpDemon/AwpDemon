### Hi, I'm Ali

MIS student at the University of Georgia, graduating 2027. Based in Athens / Atlanta. Chasing a **Summer 2026 internship** in business analytics, risk management, data analytics, or anything AI automation adjacent.

Day-to-day I work in Python and SQL for analysis, Tableau and Power BI for dashboards, and JavaScript / Node.js for anything web-facing. I'm in Gamma Iota Sigma at UGA — the insurance and risk management fraternity — which is where a lot of the insurance-flavored projects come from.

### Selected work

- **[catastrophe-loss-analysis](https://github.com/AwpDemon/catastrophe-loss-analysis)** — 67K insurance transactions × 2 years. Formally tested the three headline findings (Welch's t, bootstrap, chi-squared) and ran a 20K-iteration hurricane Monte Carlo that sizes a reinsurance layer against a 1-in-100 PML of 12.6% of book premium.
- **[insurance-risk-model](https://github.com/AwpDemon/insurance-risk-model)** — hand-tuned actuarial scorecard backtested against a logistic regression. AUC 0.83 = AUC 0.83 on ranking; scorecard is *not* calibrated (Brier 0.12 vs 0.07), and the README explains why and what to overlay.
- **[retail-sql-analytics](https://github.com/AwpDemon/retail-sql-analytics)** — 8-table 3NF Postgres schema, 15 analytical queries, RFM churn + cohort retention + cross-sell lift. Reproducible via Postgres or an in-memory DuckDB path so anyone cloning it runs the full analysis in <30 seconds without installing a database.
- **[student-budget-powerbi](https://github.com/AwpDemon/student-budget-powerbi)** — 11 custom DAX measures, a 2-layer anomaly detector, a Holt's-linear-trend forecast with bootstrapped 80% PIs, and a single-file interactive Plotly dashboard.
- **[homelab](https://github.com/AwpDemon/homelab)** — public services behind a Cloudflare Tunnel, Authentik SSO in front of the private ones, a Minecraft server I kept online through an L7 attack, and a local LLM endpoint I use for automation. Sanitized configs + a stdlib-only health check script are in the repo.

### Current focus

Picking up actuarial / underwriting concepts through GIS and side projects, digging deeper into the analytics stack (dbt, Snowflake, dashboarding patterns beyond the obvious ones), and getting better at the stats layer — backtesting, calibration, stress testing — that separates "I made a chart" from "I can defend a number in a meeting."

Open to chatting about anything data, insurance/risk, or infra.
