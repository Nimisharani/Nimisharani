<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/timeline-dark.svg" />
  <img src="./assets/timeline-light.svg" alt="Sai Nimisha Kakarla: career timeline" width="100%" />
</picture>

## The story so far

At a healthcare system I delivered claims analytics tracking turnaround time, denials, and payment discrepancies. Over **6+ years** at Neiman Marcus I unified **7 sources**—OMS, POS, product master, marketplace reconciliation, marketing, customer, and inventory—into one PostgreSQL warehouse.

I design fact and dimension models with slowly changing dimensions and define KPIs with stakeholders. I automate data-quality checks in Python, diagnose slow SQL with `EXPLAIN ANALYZE`, and deliver Tableau dashboards with parameters and drill-downs. I lead validation and UAT for every KPI and maintain code in Git with documented schemas and lineage.

## Milestone work

| Initiative | Scope | Outcome |
|------------|-------|---------|
| Retail data warehouse | Unified **7 sources** (OMS, POS, product master, marketplace, marketing, customer, inventory) into PostgreSQL star schema with sales/returns facts and slowly changing dimensions | Defined **20+ KPIs** |
| Dashboard performance tuning | Diagnosed slow queries with `EXPLAIN ANALYZE`; restructured joins, filters, and indexes | Cut dashboard refresh times by approximately **50%** |
| Automated data quality | Python/pandas profiling of daily OMS, POS, and marketplace feeds | Removed recurring manual checks; made every run reproducible |
| OMS-to-marketplace reconciliation | Traced mismatches to timing gaps, missing files, and conflicting business rules | Documented fixes that became the standard reconciliation process |
| Supply-chain delay analysis | Analyzed shipment data in Python | Reduced delivery time by **25%** |
| Delta Lake ingestion | Built API-based ingestion from inventory processing application into Delta Lake on AWS S3 | Automated extraction saved approximately **9 hours per week** |

<details>
<summary>Behind the retail data warehouse</summary>

I designed a star schema with sales and returns facts, product and customer dimensions, and slowly changing dimensions. I built SQL transformations using CTEs and window functions for running revenue, category-level return rates, and repeat-customer metrics.

I partnered with stakeholders to define **20+ KPIs** and delivered Tableau dashboards with parameters and drill-downs. I led validation and UAT for every KPI and maintained all code in Git with documented schemas and lineage.

</details>

## Credentials

- **MTech Integrated, Software Engineering** – VIT University, *June 2015 – June 2020*

@@

## What's next

[Email](mailto:nimmishareddy@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nimisha-reddy-810a84141) · [GitHub](https://github.com/Nimisharani)

## Projects

- [marginbridge](https://github.com/Nimisharani/marginbridge) — A price-volume-mix margin bridge plus elasticity estimated against discount confounding, scored against a synthetic ground truth so the pricing advice is not…
- [upliftpolicy](https://github.com/Nimisharani/upliftpolicy) — Retention targeting by uplift rather than churn propensity, with Qini curves and doubly-robust policy evaluation that surfaces customers contact drives away.
- [consentgraph](https://github.com/Nimisharani/consentgraph) — Identity resolution where per-purpose consent gates the graph join itself, with match quality measured as precision against planted ground truth and a…
- [pacingloop](https://github.com/Nimisharani/pacingloop) — Real-time campaign pacing with hour-of-week median/MAD baselines and a damped, rate-limited controller that avoids false alarms on normal seasonal peaks.
- [dagcache](https://github.com/Nimisharani/dagcache) — A content-addressed, parallel pipeline runner for reproducible ML workflows that hashes code, params and data, explains staleness and traces artifact lineage.
- [erasure](https://github.com/Nimisharani/erasure) — GDPR erasure driven by column-level lineage across multiple data stores, verified by an adversary that tries to re-identify the person who was just deleted.
- [permitflow](https://github.com/Nimisharani/permitflow) — A municipal permitting workflow where a declared statechart compiles to PostgreSQL constraints and a trigger, so illegal status transitions are rejected by the…
- [ratevault](https://github.com/Nimisharani/ratevault) — A motor insurance quote engine with bitemporal rate tables, so any past quote reprices exactly using the rates and rules in force at the time, with a live…
- [pickpath](https://github.com/Nimisharani/pickpath) — An offline-first warehouse picking PWA where reconnect conflicts become supervisor exception tasks instead of silently overwritten picks.
- [lastknowngood](https://github.com/Nimisharani/lastknowngood) — A backup recovery drill harness that measures real RTO and RPO by running restores and tests backup immutability by attempting deletion in a sealed lab.
