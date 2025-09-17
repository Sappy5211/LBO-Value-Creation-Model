# LBO-Value-Creation-Model

## AquaServe UK — Investment Memo

What this is. A thesis-first, Partner-level LBO for a UK water services platform. It shows how practical operational moves translate into cash, covenant headroom, and equity returns — and tells a commercial story an Investment Committee can buy.

## Why this business, why now

Sector: capital-light services to regulated-adjacent UK water utilities; CPI-linked frameworks; non-cyclical demand.

Timing: the AMP8 cycle forces leakage/efficiency spend over the next five years — exactly the company’s core capability.

Angle: professionalize a credible operator, add tech + routing discipline, and run a tuck-in M&A playbook to build route density.

## What I built (deliverables)

Partner/MD memo: FINAL_MEMO.md (recommendation, thesis, risks, exit).

IC tables (CSV, GitHub-rendered):

Returns by case → tables/headline_returns_by_case.csv

Risk snapshot (LTM leverage & ICR) → tables/base_risk_snapshot_ic.csv

Value-creation bridge (Base) → tables/value_creation_bridge_base.csv

Sensitivity “tornado” data → tables/sensitivity_tornado_base.csv

Lender case (springing DSCR post-Y1) → tables/lender_case_monte_carlo_summary.csv

Term-sheet variant (Lev + ICR only) → tables/term_sheet_variant_lev_icr_only_summary.csv

Headline results (Base / Mgmt / Downside)

Entry: £43.3m EV (8.0× Y1 EBITDA); fund with £25.1m TL (~58%) + £18.8m equity; £12m RCF buffer.

Returns: 23.7% IRR / 2.34× MOIC (Base) · 31.2% / 2.96× (Upside) · 15.0% / 1.75× (Downside).

No multiple expansion in Base — equity is from ops execution + deleveraging.

Headroom: LTM Net Leverage ~4.1× → ~2.3×; ICR (LTM) ≥ ~3×.

What drives value (and the bridge)

Operational levers: leakage↓ (fewer truck rolls), route density↑ (jobs/crew/day), smart meters (read cost↓), energy intensity↓.

Bridge (Base): ~73% of equity value from EBITDA growth, ~27% from deleveraging, 0% from multiple change.

What moves the IRR (tornado summary)

Exit multiple ±1.0×: biggest swing (~±550 bps).

Margin uplift ±100 bps: material (~±210 bps).

Rates ±200 bps / Capex ±10%: secondary at this leverage.

Risk, addressed like a lender

Observed: technical DSCR pressure late in hold from capex/WC timing; ICR remains healthy, leverage steps down.

Fix: standard springing DSCR post-Y1, smoother capex, RCF buffer maintained.

Lender case MC: breach risk materially reduced; term-sheet variant (Leverage + ICR) shows ~0.5% any breach (ICR only).

Exit strategy (not just “someone will buy it”)

Build a scaled, tech-enabled route-dense platform with clean tuck-in integration.

Logical buyers: UK utility services consolidators / environmental strategics needing leakage capability, telemetry, and footprint — supporting 8.0–9.0× exit.

Stack & techniques

Excel logic (replicated in code): integrated LBO (3-statement, WC, capex, debt schedule, sweep, covenants).

Python: scenario engine + Monte Carlo (rates, margin, capex, rev proxy); covenant mapping by quarter.

Power BI-style outputs (CSV): returns by case, value bridge, headroom timeline, tornado sensitivity.

## What this demonstrates

I can link operations to cash and stress-test a capital structure.

I communicate at Partner level: recommendation → thesis → drivers → risk & mitigations → exit.

My work product is IC-ready and stands on its own in a public portfolio.
