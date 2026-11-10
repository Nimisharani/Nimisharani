<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/timeline-dark.svg" />
  <img src="./assets/timeline-light.svg" alt="Sai Nimisha Kakarla: career timeline" width="100%" />
</picture>

## The story so far

I started out cleaning operational data at Kone, then spent two years at Relevance Lab on supply-chain analytics, where shipment analysis cut delivery time by **25%** and automated pipelines saved about **9 hours of manual work per week**. At Baylor Scott & White I delivered healthcare claims analytics tracking turnaround time, denials and payment discrepancies.

Since April 2023 at Neiman Marcus Group, I have unified **7 sources** (OMS, POS, product master, marketplace reconciliation, marketing, customer and inventory) into one PostgreSQL warehouse.

I design fact and dimension models with slowly changing dimensions and define KPIs with finance, merchandising and marketing. I automate data-quality checks in Python, diagnose slow SQL with `EXPLAIN ANALYZE`, and deliver Tableau dashboards with parameters and drill-downs. I lead validation and UAT for every KPI and maintain code in Git with documented schemas and lineage.

## Experience

| Role | Company | Dates | Highlights |
|------|---------|-------|------------|
| **Data Analyst** | Neiman Marcus Group · Dallas, TX | Apr 2023 – Present | 7-source PostgreSQL warehouse, star schema with SCDs, **20+ KPIs**, ~**50%** faster dashboard refresh |
| **Data Analyst** | Baylor Scott & White · Irving, TX | Oct 2022 – Mar 2023 | Claims KPIs (volume, turnaround, denials, payment discrepancies), Python data-quality scripts, weekly Tableau reporting |
| **Jr Data Analyst** | Relevance Lab · Bengaluru, India | Jun 2020 – May 2022 | **25%** shorter delivery time, ~**9 hrs/week** automated, API ingestion into Delta Lake on AWS S3 |
| **Data Analyst Intern** | Kone · Chennai, India | Aug 2019 – May 2020 | Cleaned and standardized operational data in Excel and SQL; monthly trend reporting |

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

## Toolkit

- **SQL & databases:** PostgreSQL, CTEs, window functions, query tuning, `EXPLAIN ANALYZE`, indexing
- **Python:** pandas, NumPy, boto3, data profiling, workflow automation
- **Modeling & cloud:** ETL/ELT, star schema, fact/dimension design, slowly changing dimensions, Delta Lake, AWS S3, EC2
- **BI:** Tableau (calculated fields, parameters, interactive dashboards), Excel, KPI reporting
- **Analytics:** KPI design, hypothesis testing, segmentation, trend and root-cause analysis
- **Data quality:** completeness, duplicate and integrity checks, source reconciliation, UAT test design
- **Domains:** retail and e-commerce, marketplace, inventory, returns, healthcare claims, supply chain

## Credentials

- **MTech Integrated, Software Engineering** – VIT University, Chennai, *June 2015 – June 2020*

## Projects

- [retail-analytics-customer-segmentation](https://github.com/Nimisharani/retail-analytics-customer-segmentation) — Customer purchasing behavior, seasonal sales trends and category performance from retail transactions, turned into revenue, targeting and inventory recommendations.
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

## Let's connect

Looking for an analyst who turns multi-source data into KPIs teams trust? Reach out by email or connect on LinkedIn.

[Portfolio](https://sairani.com) · [Resume](https://sairani.com/assets/files/sai-kakarla-resume.pdf) · [LinkedIn](https://www.linkedin.com/in/nimisha-reddy-810a84141) · [Email](mailto:nimmishareddy@gmail.com) · [GitHub](https://github.com/Nimisharani)
