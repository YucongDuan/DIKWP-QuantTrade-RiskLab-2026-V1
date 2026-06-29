# DIKWP QuantTrade RiskLab 2026 V1

Offline-first prototype for AI-era quantitative trading research, backtesting, paper-trading governance, model risk, and compliance preparation.

## Positioning

This system is **not** an investment adviser, live-trading platform, broker connector, or order execution system. It is a research, education, risk-review, and paper-trading governance workbench.

## Workflow

Strategy Purpose Contract → Market Evidence Ledger → 3-No data diagnostics → DIKWP quant loop → strategy backtest → walk-forward validation → portfolio risk and stress tests → execution/order gate → AI model governance → program trading compliance gate → Action Tickets → paper trading → Quant Research Passport.

## Quick start

Open `index.html` in a modern browser. It runs fully offline using synthetic market data.

Optional CLI:

```bash
python tools/run_quant_research.py examples/sample_strategy_config.json --out outputs
```

## Prohibited uses

- no live trading
- no broker or exchange API connection
- no account credentials
- no investment recommendations
- no guaranteed returns
- no client suitability decision
- no hidden telemetry
- no claims of regulatory approval or exchange compliance

## Design lineage

The package follows the DIKWP pattern used across prior reference systems: Evidence Ledger, Residual, Action Ticket, Human Review, Kill/Recovery, and Static Boundary Audit.
