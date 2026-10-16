# Payments Analytics Dashboard

A live payments operations dashboard built by Narasimha Naidu Kilari. It monitors the metrics a payments team watches every day — total volume, transaction counts, authorization/success rate, average ticket, and refund/chargeback rate — with an operations alert feed, gateway and channel breakdowns, and a partner performance table.

**Live demo:** https://narasimha3008.github.io/payments-dashboard/

## Features

- KPI cards with deltas versus the prior period
- Daily volume trend chart (line), channel mix (doughnut), and volume by gateway (bar)
- Operations alerts panel with severity levels and timestamps
- Partner performance table with volume, transactions, success rate, and status
- Working date-range selector (7 / 30 / 90 days) and channel filter — every KPI, chart, and table updates consistently from the same seeded dataset
- Deterministic demo data generated in JavaScript (seeded PRNG), so the numbers are internally consistent on every load
- Responsive dark design built with Tailwind CSS

## Tech

- HTML (single self-contained `index.html`)
- Tailwind CSS (CDN)
- Chart.js (CDN)
- Vanilla JavaScript — no build step, no external data calls

## Note

All data is simulated in the browser for demonstration purposes only. The dashboard is not connected to any live payment system.
