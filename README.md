# A-share Research Dashboard

A personal, local-only research tool for the China A-share market.

## What it does
- Renders daily / weekly / monthly candles from a local parquet data warehouse
- Overlays main-force fund flow and industry heat
- Runs a multi-indicator divergence scan (MACD, RSI, Stochastic, CCI, MOM, OBV, CMF, MFI)

## Data sources
- Local parquet warehouse: adjusted daily OHLCV, industry indices, fund flow
- TDX terminal local files (vipdoc) for indices and US ETFs

## Stack
Python (stdlib HTTP server) + pandas / pyarrow + Lightweight Charts

## Scope
Single user, localhost only. No public access, no data redistribution.
