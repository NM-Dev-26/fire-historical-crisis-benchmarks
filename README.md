# FIRE Historical Crisis & Monte Carlo Benchmarks (1929–2008)

**Live Interactive Studio:** **[https://novaplanner.app](https://novaplanner.app)**

This repository provides open-source historical sequence-of-returns benchmark cohorts and simulation methodology used in **[NovaPlanner](https://novaplanner.app)** — a free, privacy-first interactive retirement and FIRE (Financial Independence, Retire Early) planning studio.

---

## Why Standard 4% Rule Calculators Fail

Deterministic compound-interest calculators assume a smooth average return (e.g., `7%` real per year). In practice, early retirees fail due to **Sequence-of-Returns Risk (SORR)**—suffering deep real drawdowns or stagflation during the first 5–10 years of withdrawals.

### Historical Crisis Cohorts Included (`historical_crises.json`)

| Crisis Cohort | Years | Key Macro Mechanism | Interactive Simulator |
| :--- | :--- | :--- | :--- |
| **1929 Great Depression** | Years 1–10 | `-86%` nominal equity crash followed by deflationary spiral | [Run 1929 Stress Test](https://novaplanner.app) |
| **1966 Stagflation Cohort** | Years 1–16 | Flat nominal equities + compounding CPI inflation (`7%–13%/yr`) — the worst historical 30-year cohort for the 4% rule | [Run 1966 Stress Test](https://novaplanner.app) |
| **1973–1974 Oil Shock** | Years 1–10 | `-48%` real drawdown + double-digit inflation | [Run 1973 Stress Test](https://novaplanner.app) |
| **2000 Dot-Com & Lost Decade** | Years 1–12 | Three consecutive negative S&P 500 years (`2000–2002`) followed by `2008` GFC | [Run 2000 Stress Test](https://novaplanner.app) |
| **2008 Global Financial Crisis** | Years 1–6 | `-37%` Year-1 equity crash + multi-year recovery | [Run 2008 Stress Test](https://novaplanner.app) |

---

## Free Interactive Calculators & Software Comparisons

All calculators run 100% client-side with automatic local persistence, `?plan=...` URL sharing, live World Bank CPI vs. Central Bank inflation toggles across 8 currencies (`USD`, `EUR`, `GBP`, `CHF`, `CAD`, `AUD`, `SAR`, `AED`), and year-by-year CSV ledger exports:

* **[NovaPlanner Interactive Retirement & FIRE Studio](https://novaplanner.app)** — 500-Run Monte Carlo (`P10`/`P50`/`P90`), Historical Crises (`1929`–`2008`), Dynamic Spending Guardrails, and Draggable Timeline Milestones.
* **[NovaPlanner Welcome Hub](https://novaplanner.app/welcome/)** — Multilingual overview (`EN`, `FR`, `DE`, `AR`).
* **[UK SIPP Pension & Tax Relief Calculator](https://novaplanner.app/welcome/sipp-calculator/)** — Models 20% automatic HMRC basic-rate relief top-ups, 40%/45% Self-Assessment rebates, and £60,000 Annual Allowance limits.
* **[Best Free ProjectionLab Alternative (2026)](https://novaplanner.app/welcome/projectionlab-alternative/)** — Side-by-side comparison of NovaPlanner vs. ProjectionLab ($108–$140/yr).
* **[Best Free Boldin (NewRetirement) Alternative (2026)](https://novaplanner.app/welcome/boldin-newretirement-alternative/)** — Side-by-side comparison of NovaPlanner vs. Boldin PlannerPlus ($144/yr).
* **[Best Free Finary Alternative (2026)](https://novaplanner.app/welcome/finary-alternative/)** — Privacy-first European & global FIRE simulator without mandatory bank login syncing.
* **[Meilleure Alternative Gratuite à Finary (FR — 2026)](https://novaplanner.app/welcome/alternative-finary-gratuite/)** — Simulateur Retraite & FIRE gratuit en français sans connexion bancaire.
* **[Best Free UK Voyant & Timeline Cashflow Modelling Alternative](https://novaplanner.app/welcome/voyant-cashflow-alternative/)** — Institutional cashflow stress testing for DIY UK SIPP & ISA investors.
* **[Modern Visual Alternative to cFIREsim & FIRECalc](https://novaplanner.app/welcome/cfiresim-firecalc-alternative/)** — Interactive Monte Carlo & crisis cohorts vs. legacy 1990s form calculators.
* **[Privacy-First Empower (Personal Capital) Retirement Planner Alternative](https://novaplanner.app/welcome/empower-personal-capital-alternative/)** — Run Monte Carlo retirement projections without linking bank credentials or getting advisor sales calls.

---

## License

MIT License — Open benchmark data for personal finance researchers and DIY retirees.
