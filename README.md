# InventoryHub

A real time multi warehouse inventory dashboard, with one source of truth for stock across warehouses.

> **Status:** Building now. Not shipped. Not live with users.

## Contents

- [What it is](#what-it-is)
- [Stack](#stack)
- [Milestones](#milestones)

## What it is

InventoryHub is a real time multi warehouse inventory dashboard. A distribution business loses track of stock across warehouses when spreadsheets never match. This app gives every warehouse one source of truth, with stock movements, discrepancy reports, and alerts.

## Stack

- React, TypeScript, Node with Express, PostgreSQL, Docker, Git, and CI/CD
- MVC adapted for web apps: models in the database layer, React views, thin Express controllers, and a service layer for inventory, warehouses, and auth services
- Tests with each milestone
- Docs with each milestone

## Milestones

Work one milestone at a time, in order. Test with each milestone, and commit per milestone. Fake data only. No secrets, no real personal data, no employer code, no university coursework code.

| Milestone | Focus | Hours |
| --- | --- | --- |
| M0 | Setup and repo hygiene | 5 |
| M1 | Auth, warehouses, and products | 15 |
| M2 | Stock movements and adjustments | 20 |
| M3 | Real time dashboard, discrepancies, and alerts | 20 |
| M4 | Reporting and exports | 10 |
| M5 | Security, tests, deployment, and docs | 10 |
| **Total** | **Planned work ahead** | **80** |

### M0 — Setup and repo hygiene (5 hours)

- Repo, README, MIT licence, `.gitignore`, project structure, local run instructions, fake data plan

### M1 — Auth, warehouses, and products (15 hours)

- Registration, login, roles, warehouse records, product records, product categories
- Fake warehouse and product data

### M2 — Stock movements and adjustments (20 hours)

- Stock in, stock out, transfers between warehouses
- Adjustment records with reasons
- Movement history that cannot be edited in place

### M3 — Real time dashboard, discrepancies, and alerts (20 hours)

- Dashboard by warehouse and by product
- Discrepancy view comparing expected stock from movements against counted stock
- Low stock alerts, search, and filters

### M4 — Reporting and exports (10 hours)

- Stock reports by date range and movement reports
- Export as a generated file from fake data

### M5 — Security, tests, deployment, and docs (10 hours)

- Role based access and input validation
- Unit and integration tests, deployment guide, README demo script

## Definition of done

- [ ] Tested app with at least two fake warehouses
- [ ] Stock movements across those warehouses
- [ ] Dashboard that updates from movement history
- [ ] Discrepancy report
- [ ] Docs explaining why totals are derived from movements, not edited directly

