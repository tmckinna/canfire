# CanFIRE 🇨🇦 — Early Retirement Planner for Canadians

A free, private, tax-optimized retirement planner for Canadians who want to retire early.
Everything runs in your browser. No sign-up, no server, and your data never leaves your device
(inputs are stored only in your browser's localStorage).

**▶ Live app:** https://YOUR-USERNAME.github.io/canfire/

## Features
- 2026 federal + all provincial/territorial tax brackets, credits, dividend gross-up, capital gains
- CPP (60–70) and OAS (65–70) timing, OAS clawback, 10% OAS boost at 75
- RRSP "meltdown" / bracket-fill, RRIF minimums, pension income splitting, TFSA room tracking, ACB tracking
- Auto-optimizer that tests ~1,000 strategy combinations and recommends the best one
- Monte Carlo simulation, max-spending solver, strategy comparison, year-by-year table, CSV export

## Run locally
Download `index.html` and open it in any modern browser. That's it.

## Updating tax figures
All tax constants live in the `FED` and `PROV` objects near the top of the first `<script>` block in `index.html`.

## Disclaimer
CanFIRE is an educational planning tool, not financial, tax, or legal advice. Figures are estimates;
verify important decisions with a qualified professional (CFP, CPA).

## License
MIT — see `LICENSE`.
